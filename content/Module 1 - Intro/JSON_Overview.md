```json
{
  "type": "object",
  "properties": {
    "Modul": {
      "type": "string",
      "content": "Die Macht der Sprachmodelle: Von einfachen Fragen zu kreativen Meisterleistungen"
    },
    "Zielgruppe": {
      "type": "string",
      "content": "Berufsschüler / Gymnasiasten"
    },
    "Dauer": {
      "type": "string",
      "content": "90 Minuten"
    },
    "Learning goals": {
      "type": "array",
      "items": [
        {
          "type": "string",
          "content": "Die Teilnehmenden verstehen die grundlegende Funktionsweise von grossen Sprachmodellen (LLMs) wie ChatGPT."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden erkennen das Potential von LLMs für kreative Anwendungen und Problemlösungen."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden lernen die Bedeutung von Prompt Engineering für die effektive Nutzung von LLMs kennen."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden setzen sich kritisch mit der Funktionsweise und den Limitationen von LLMs auseinander."
        }
      ]
    },
    "Kapitel": {
      "type": "array",
      "items": [
        {
          "KapitelTitel": {
            "type": "string",
            "content": "Was sind LLMs und wie funktionieren sie?"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "LLMs sind komplexe Algorithmen, die mit riesigen Datenmengen aus Text und Code trainiert werden. Sie lernen Muster und Beziehungen in der Sprache und können so menschenähnlichen Text generieren, Fragen beantworten, Texte übersetzen und vieles mehr. Stellen Sie sich LLMs wie einen sehr gut ausgebildeten Papagei vor, der zwar fliessend sprechen kann, aber nicht wirklich versteht, was er sagt. Er wiederholt einfach die Muster, die er gelernt hat."
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Denken Sie an ein berühmtes Zitat. Geben Sie den Anfang des Zitats in ChatGPT ein und beobachten Sie, wie es versucht, das Zitat zu vervollständigen."
              },
              {
                "type": "string",
                "content": "Geben Sie ChatGPT eine einfache Rechenaufgabe und beobachten Sie, wie es die Aufgabe löst."
              }
            ]
          },
          "Techniken für Prompting": {
            "type": "array",
            "items": []
          },
          "Tipps": {
            "type": "array",
            "items": []
          },
          "Diskussionsfragen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Was sind die Grenzen von LLMs? Was können sie nicht?"
              },
              {
                "type": "string",
                "content": "Welche ethischen Fragen ergeben sich durch die Verwendung von LLMs?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "What are large language models exactly? What do they do? How do they work?"
              },
              {
                "type": "string",
                "content": "Now, though, fundamental thing that you want to know about these large language models is basically what they're doing is they're taking your input and they're trying to generate the next word."
              }
            ]
          }
        },
        {
          "KapitelTitel": {
            "type": "string",
            "content": "Kreative Anwendungen von LLMs: Mehr als nur Textgenerierung"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "LLMs können viel mehr als nur Texte schreiben. Mit etwas Kreativität und den richtigen Prompts können Sie sie nutzen, um: \n- Mahlzeiten zu planen und Rezepte zu erstellen\n- Geschichten und Gedichte zu schreiben\n- Musik zu komponieren\n- Code in verschiedenen Programmiersprachen zu generieren\n- Komplexe Probleme zu analysieren und Lösungen zu finden"
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Verwenden Sie ChatGPT, um einen kurzen Song im Stil Ihrer Lieblingsband zu komponieren."
              },
              {
                "type": "string",
                "content": "Bitten Sie ChatGPT, Ihnen bei der Planung einer Geburtstagsparty zu helfen, einschliesslich Dekoration, Essen und Aktivitäten."
              }
            ]
          },
          "Techniken für Prompting": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Verwenden Sie klare und präzise Sprache in Ihren Prompts."
              },
              {
                "type": "string",
                "content": "Geben Sie dem LLM genügend Kontext, um Ihre Anfrage zu verstehen."
              },
              {
                "type": "string",
                "content": "Experimentieren Sie mit verschiedenen Formulierungen und Ansätzen, um die besten Ergebnisse zu erzielen."
              }
            ]
          },
          "Tipps": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Seien Sie nicht zu kritisch mit Ihren ersten Versuchen. LLMs sind iterative Werkzeuge, die durch Experimentieren und Verfeinern lernen."
              },
              {
                "type": "string",
                "content": "Haben Sie keine Angst, kreativ zu sein und die Grenzen des Möglichen auszuloten!"
              }
            ]
          },
          "Diskussionsfragen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Welche kreativen Anwendungen von LLMs finden Sie besonders spannend?"
              },
              {
                "type": "string",
                "content": "Wo sehen Sie die Grenzen der Kreativität von LLMs?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "I want you to think of ChatGPT and these large language models as tools that you can use to give your ideas form, to give your thoughts, realization."
              },
              {
                "type": "string",
                "content": "These are tools that really allow you to do fascinating things."
              }
            ]
          }
        },
        {
          "KapitelTitel": {
            "type": "string",
            "content": "Zufälligkeit und Variabilität: Umgang mit der Unvorhersehbarkeit von LLMs"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "LLMs basieren auf Wahrscheinlichkeiten. Das bedeutet, dass sie nicht immer die gleiche Antwort generieren, selbst wenn Sie denselben Prompt verwenden. Manchmal ist diese Variabilität erwünscht, z.B. wenn Sie nach neuen Ideen suchen. In anderen Fällen kann sie jedoch problematisch sein, z.B. wenn Sie präzise und konsistente Ergebnisse benötigen."
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Geben Sie ChatGPT mehrmals hintereinander denselben Prompt und beobachten Sie, wie sich die Antworten unterscheiden."
              },
              {
                "type": "string",
                "content": "Versuchen Sie, die Variabilität von ChatGPT zu beeinflussen, indem Sie Ihren Prompt präzisieren oder zusätzliche Informationen hinzufügen."
              }
            ]
          },
          "Techniken für Prompting": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Verwenden Sie spezifische Schlüsselwörter und Formulierungen, um die gewünschten Ergebnisse einzugrenzen."
              },
              {
                "type": "string",
                "content": "Definieren Sie den gewünschten Stil, Ton und die Länge der Antwort in Ihrem Prompt."
              },
              {
                "type": "string",
                "content": "Nutzen Sie die Möglichkeit, dem LLM Beispiele für gewünschte Antworten zu geben."
              }
            ]
          },
          "Tipps": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Seien Sie sich bewusst, dass LLMs keine Gedanken lesen können. Je klarer und präziser Ihr Prompt ist, desto besser wird das Ergebnis sein."
              },
              {
                "type": "string",
                "content": "Experimentieren Sie mit verschiedenen Prompt Engineering-Techniken, um die Kontrolle über die Variabilität von LLMs zu erlangen."
              }
            ]
          },
          "Diskussionsfragen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Wann ist die Variabilität von LLMs hilfreich und wann ist sie hinderlich?"
              },
              {
                "type": "string",
                "content": "Wie können wir sicherstellen, dass LLMs verantwortungsvoll und ethisch eingesetzt werden?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Large language models are unlikely, at least in the near term to give you an exact and repeatable answer every single time."
              },
              {
                "type": "string",
                "content": "There's always going to be the possibility they do something a little bit unexpected and this is by design and can be a really good thing."
              }
            ]
          }
        }
      ]
    },
    "Hands-on Labs": {
      "type": "array",
      "items": [
        {
          "LabTitel": {
            "type": "string",
            "content": "Kreatives Schreiben mit ChatGPT"
          },
          "Beschreibung": {
            "type": "string",
            "content": "In diesem Lab experimentieren Sie mit ChatGPT, um kreative Texte zu erstellen. Sie lernen verschiedene Prompt Engineering-Techniken kennen, um den Stil, Ton und Inhalt der generierten Texte zu beeinflussen."
          },
          "Ziele": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Erstellen Sie eine Kurzgeschichte in einem bestimmten Genre (z.B. Science-Fiction, Fantasy, Krimi)."
              },
              {
                "type": "string",
                "content": "Schreiben Sie ein Gedicht mit einem bestimmten Thema und Reimschema."
              },
              {
                "type": "string",
                "content": "Generieren Sie einen Songtext im Stil Ihres Lieblingsmusikers."
              }
            ]
          },
          "Anleitung": {
            "type": "string",
            "content": "1. Wählen Sie ein Thema und ein Genre für Ihren Text.\n2. Formulieren Sie einen klaren und präzisen Prompt, der ChatGPT die gewünschten Informationen liefert.\n3. Experimentieren Sie mit verschiedenen Prompt Engineering-Techniken, um den Stil, Ton und Inhalt des generierten Textes zu beeinflussen.\n4. Teilen und besprechen Sie Ihre Ergebnisse mit der Gruppe."
          }
        }
      ]
    },
    "Hacks": {
      "type": "array",
      "items": [
        {
          "type": "string",
          "content": "Verwenden Sie die Zeichenfolge \"```\" (drei Backticks), um Codeblöcke in Ihren Prompts zu erstellen. Dies hilft ChatGPT, zwischen Text und Code zu unterscheiden."
        },
        {
          "type": "string",
          "content": "Nutzen Sie die \"Temperature\"-Einstellung in ChatGPT, um die Kreativität der Antworten zu steuern. Eine höhere Temperatur führt zu kreativeren, aber möglicherweise auch weniger genauen Antworten."
        }
      ]
    },
    "Zusammenfassung": {
      "type": "string",
      "content": "Grosse Sprachmodelle sind mächtige Werkzeuge mit dem Potenzial, die Art und Weise, wie wir lernen, arbeiten und kreativ sind, zu revolutionieren. Indem wir die Prinzipien des Prompt Engineerings verstehen und anwenden, können wir die Möglichkeiten dieser Modelle voll ausschöpfen und sie nutzen, um unsere eigenen Fähigkeiten zu erweitern."
    }
  }
}
```