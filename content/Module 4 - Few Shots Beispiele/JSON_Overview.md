```json
{
  "type": "object",
  "properties": {
    "Modul": {
      "type": "string",
      "content": "Einführung in Few-Shot Prompting"
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
          "content": "Die Teilnehmenden verstehen das Konzept des Few-Shot Promptings und dessen Bedeutung im Kontext von LLMs."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden können einfache Few-Shot Prompts erstellen, um ein LLM für spezifische Aufgaben zu instruieren."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden erkennen die Bedeutung von klaren Instruktionen, Beispielen und Struktur in Few-Shot Prompts."
        }
      ]
    },
    "Kapitel": {
      "type": "array",
      "items": [
        {
          "KapitelTitel": {
            "type": "string",
            "content": "Was ist Few-Shot Prompting?"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "LLMs wie ChatGPT sind zwar mächtig, benötigen aber klare Anweisungen. Anstatt komplexe Regeln zu programmieren, nutzen wir beim Few-Shot Prompting Beispiele, um dem LLM beizubringen, was wir wollen. Stellen Sie sich vor, Sie bringen einem Kind bei, Objekte nach Farben zu sortieren. Anstatt ihm lange Erklärungen zu geben, zeigen Sie ihm einfach ein paar Beispiele: 'Schau, der Ball ist rot, also kommt er in die rote Kiste. Der Würfel ist blau, also kommt er in die blaue Kiste.' Genauso funktioniert Few-Shot Prompting: Wir geben dem LLM Beispiele für Input und den gewünschten Output, damit es das Muster erkennt und auf neue Eingaben anwenden kann."
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Überlegen Sie sich ein Beispiel für eine Aufgabe, die Sie einem LLM mit Few-Shot Prompting beibringen könnten (z. B. das Übersetzen von kurzen Sätzen, das Zusammenfassen von Texten, das Generieren von kreativen Inhalten)."
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
                "content": "Warum ist Few-Shot Prompting eine effektive Methode, um mit LLMs zu interagieren?"
              },
              {
                "type": "string",
                "content": "Welche Vorteile bietet Few-Shot Prompting im Vergleich zur traditionellen Programmierung?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Anstatt komplexe Regeln zu programmieren, nutzen wir beim Few-Shot Prompting Beispiele, um dem LLM beizubringen, was wir wollen."
              },
              {
                "type": "string",
                "content": "Wir geben dem LLM Beispiele für Input und den gewünschten Output, damit es das Muster erkennt und auf neue Eingaben anwenden kann."
              }
            ]
          }
        },
        {
          "KapitelTitel": {
            "type": "string",
            "content": "Elemente eines Few-Shot Prompts"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "Ein effektiver Few-Shot Prompt besteht aus drei Hauptteilen: \n\n**1. Klare Instruktionen:** Formulieren Sie klar und deutlich, was das LLM tun soll. Vermeiden Sie Fachjargon und komplexe Satzstrukturen. \n**2. Repräsentative Beispiele:** Wählen Sie Beispiele, die die gewünschte Aufgabe und den gewünschten Output möglichst genau abbilden. Je mehr Beispiele Sie geben, desto besser kann das LLM das Muster erkennen. \n**3. Struktur und Formatierung:** Verwenden Sie eine einheitliche Struktur und Formatierung für Ihre Beispiele. Dies hilft dem LLM, die relevanten Informationen schnell zu erfassen."
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Analysieren Sie den folgenden Few-Shot Prompt und identifizieren Sie die drei Hauptteile (Instruktionen, Beispiele, Struktur/Formatierung): \n\n**Aufgabe:** Fasse den folgenden Text in einem Satz zusammen. \n\n**Beispiel 1:** \n**Input:** Der Frosch sprang über den Stein. Die Sonne schien hell. Der Himmel war blau. \n**Output:** Ein Frosch sprang an einem sonnigen Tag über einen Stein. \n\n**Beispiel 2:** \n**Input:** Das Mädchen aß einen Apfel. Der Apfel war rot. Das Mädchen lächelte. \n**Output:** Ein Mädchen aß einen roten Apfel und lächelte."
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
                "content": "Warum ist es wichtig, klare Instruktionen in einem Few-Shot Prompt zu verwenden?"
              },
              {
                "type": "string",
                "content": "Wie können Sie sicherstellen, dass Ihre Beispiele repräsentativ für die gewünschte Aufgabe sind?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Ein effektiver Few-Shot Prompt besteht aus drei Hauptteilen: Klare Instruktionen, Repräsentative Beispiele, Struktur und Formatierung"
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
            "content": "Praktische Übung: Few-Shot Prompting mit ChatGPT"
          },
          "Beschreibung": {
            "type": "string",
            "content": "In diesem praktischen Teil wenden Sie Ihr Wissen über Few-Shot Prompting an, indem Sie eigene Prompts erstellen und mit ChatGPT testen."
          },
          "Ziele": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Erstellen Sie einen Few-Shot Prompt, um ChatGPT beizubringen, kurze Sätze vom Deutschen ins Englische zu übersetzen."
              },
              {
                "type": "string",
                "content": "Testen Sie Ihren Prompt mit verschiedenen Beispielen und bewerten Sie die Genauigkeit der Übersetzungen."
              },
              {
                "type": "string",
                "content": "Dokumentieren Sie Ihre Beobachtungen und identifizieren Sie potenzielle Verbesserungsmöglichkeiten für Ihren Prompt."
              }
            ]
          },
          "Anleitung": {
            "type": "string",
            "content": "1. Öffnen Sie ChatGPT in Ihrem Browser. \n2. Definieren Sie die Aufgabe: Deutsche Sätze ins Englische übersetzen. \n3. Erstellen Sie drei bis fünf Beispiele für Input (deutsche Sätze) und den gewünschten Output (englische Übersetzungen). \n4. Geben Sie die Instruktionen und Beispiele in ChatGPT ein und fügen Sie einen neuen deutschen Satz hinzu, den ChatGPT übersetzen soll. \n5. Analysieren Sie die Qualität der Übersetzung und wiederholen Sie die Schritte 3-5 mit verschiedenen Beispielen und Formulierungen."
          }
        }
      ]
    },
    "Hacks": {
      "type": "array",
      "items": [
        {
          "type": "string",
          "content": "Verwenden Sie konkrete und spezifische Sprache in Ihren Instruktionen."
        },
        {
          "type": "string",
          "content": "Wählen Sie Beispiele, die dem Kontext Ihrer Aufgabe entsprechen."
        },
        {
          "type": "string",
          "content": "Experimentieren Sie mit verschiedenen Formulierungen und Beispielen, um die besten Ergebnisse zu erzielen."
        }
      ]
    },
    "Zusammenfassung": {
      "type": "string",
      "content": "Few-Shot Prompting ist eine leistungsstarke Technik, um LLMs wie ChatGPT für spezifische Aufgaben zu trainieren. Durch die Bereitstellung klarer Instruktionen, repräsentativer Beispiele und einer einheitlichen Struktur können Sie die Genauigkeit und Effizienz von LLMs verbessern und diese vielseitig einsetzen."
    }
  }
}
```