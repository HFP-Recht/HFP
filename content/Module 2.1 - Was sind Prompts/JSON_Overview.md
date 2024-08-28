```json
{
  "type": "object",
  "properties": {
    "Modul": {
      "type": "string",
      "content": "Einführung in Prompts und Prompt Engineering"
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
          "content": "Die Teilnehmenden verstehen die Bedeutung von Prompts in der Interaktion mit grossen Sprachmodellen."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden erkennen die verschiedenen Dimensionen eines Prompts."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden können einfache Prompts erstellen und verstehen, wie diese die Ausgabe eines Sprachmodells beeinflussen."
        }
      ]
    },
    "Kapitel": {
      "type": "array",
      "items": [
        {
          "KapitelTitel": {
            "type": "string",
            "content": "Was ist ein Prompt?"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "Ein Prompt ist mehr als nur eine Frage an ein Sprachmodell. Es ist eine Anweisung, die das Modell dazu bringt, eine bestimmte Ausgabe zu generieren. Stellen Sie sich einen Prompt als eine Reihe von Instruktionen vor, die Sie einem persönlichen Assistenten geben würden."
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Formulieren Sie einen Prompt, der ChatGPT dazu bringt, ein kurzes Gedicht über den Frühling zu schreiben."
              },
              {
                "type": "string",
                "content": "Erstellen Sie einen Prompt, der ChatGPT auffordert, die Geschichte "Rotkäppchen" aus der Sicht des Wolfes zu erzählen."
              }
            ]
          },
          "Techniken für Prompting": {
            "type": "array",
            "items": []
          },
          "Tipps": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Seien Sie so spezifisch wie möglich in Ihren Prompts. Je genauer Sie Ihre Anfrage formulieren, desto präziser wird die Antwort des Sprachmodells ausfallen."
              },
              {
                "type": "string",
                "content": "Verwenden Sie Schlüsselwörter, um das Sprachmodell auf das gewünschte Thema zu lenken."
              }
            ]
          },
          "Diskussionsfragen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Welche Rolle spielen Prompts in der Interaktion mit Sprachmodellen?"
              },
              {
                "type": "string",
                "content": "Welche Herausforderungen sehen Sie bei der Formulierung effektiver Prompts?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "So what does the word prompt actually mean? ... It's more than just a question that you're asking to the large language model."
              },
              {
                "type": "string",
                "content": "So part of what a prompt is, it is a call to action to the large language model ... to start generating words that will form the basis of our output."
              }
            ]
          }
        },
        {
          "KapitelTitel": {
            "type": "string",
            "content": "Dimensionen eines Prompts"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "Prompts können verschiedene Formen annehmen und unterschiedliche Funktionen erfüllen. Sie können als direkte Fragen, Aufforderungen zur Generierung von Inhalten, Anweisungen zur Strukturierung der Ausgabe oder sogar als Kombinationen dieser Elemente dienen."
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Verwandeln Sie die Frage 'Was ist die Hauptstadt von Frankreich?' in einen Prompt, der ChatGPT dazu bringt, eine kurze Beschreibung von Paris zu liefern."
              },
              {
                "type": "string",
                "content": "Formulieren Sie einen Prompt, der ChatGPT dazu auffordert, eine Liste mit fünf Tipps für eine gesunde Ernährung zu erstellen, wobei jeder Tipp mit 'Essen Sie...' beginnen soll."
              }
            ]
          },
          "Techniken für Prompting": {
            "type": "array",
            "items": []
          },
          "Tipps": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Experimentieren Sie mit verschiedenen Arten von Prompts, um herauszufinden, welche Formulierungen die besten Ergebnisse erzielen."
              },
              {
                "type": "string",
                "content": "Nutzen Sie die Möglichkeit, dem Sprachmodell Beispiele zu geben, um die gewünschte Ausgabe zu verdeutlichen."
              }
            ]
          },
          "Diskussionsfragen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Welche verschiedenen Arten von Prompts können Sie sich vorstellen?"
              },
              {
                "type": "string",
                "content": "Wie können Prompts dazu genutzt werden, die Kreativität von Sprachmodellen zu fördern?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Prompts have a lot of different dimensions to them. ... it gives us sort of that nuance to the capabilities of a prompt."
              },
              {
                "type": "string",
                "content": "So prompt could both serve as as a call to action ... Or it can actually be an input, it can be asking us for input."
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
            "content": "Experimentieren mit Prompts"
          },
          "Beschreibung": {
            "type": "string",
            "content": "In diesem praktischen Teil experimentieren die Teilnehmenden mit verschiedenen Prompts und beobachten, wie sich diese auf die Ausgabe von ChatGPT auswirken."
          },
          "Ziele": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Praktische Erfahrung mit der Formulierung von Prompts sammeln."
              },
              {
                "type": "string",
                "content": "Die Auswirkungen verschiedener Prompt-Strukturen und -Formulierungen auf die Ausgabe des Sprachmodells analysieren."
              }
            ]
          },
          "Anleitung": {
            "type": "string",
            "content": "1. Öffnen Sie ChatGPT in Ihrem Browser.\n2. Geben Sie verschiedene Prompts ein, z. B. Fragen, Aufforderungen zur Texterstellung oder Anweisungen zur Strukturierung der Ausgabe.\n3. Beobachten Sie die Antworten von ChatGPT und analysieren Sie, wie sich die verschiedenen Prompts auf die Ausgabe auswirken.\n4. Dokumentieren Sie Ihre Beobachtungen und diskutieren Sie Ihre Erkenntnisse mit anderen Teilnehmenden."
          }
        }
      ]
    },
    "Hacks": {
      "type": "array",
      "items": []
    },
    "Zusammenfassung": {
      "type": "string",
      "content": "In diesem Modul haben wir gelernt, was Prompts sind und welche wichtige Rolle sie bei der Interaktion mit grossen Sprachmodellen spielen. Wir haben die verschiedenen Dimensionen von Prompts kennengelernt und erste Erfahrungen mit der Formulierung effektiver Prompts gesammelt. Dieses Wissen bildet die Grundlage für das weitere Verständnis und die Nutzung von Sprachmodellen."
    }
  }
}
```