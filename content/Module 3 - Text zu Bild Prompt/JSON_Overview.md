```json
{
  "type": "object",
  "properties": {
    "Modul": {
      "type": "string",
      "content": "Text-to-Image: Bilder mit Worten erschaffen"
    },
    "Zielgruppe": {
      "type": "string",
      "content": "Berufsschule / Gymnasium (15-20 Jahre)"
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
          "content": "Die Teilnehmenden verstehen den Zusammenhang zwischen Text und Bildgenerierung durch KI."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden kennen verschiedene Prompting-Techniken zur Bildgenerierung."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden können eigene Bild-Prompts erstellen und verfeinern."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden können die Benutzeroberfläche eines KI-Bildgenerators bedienen."
        }
      ]
    },
    "Kapitel": [
      {
        "KapitelTitel": {
          "type": "string",
          "content": "Einführung in die Text-to-Image-Generierung"
        },
        "Theoretische Grundlagen": {
          "type": "string",
          "content": "Bilder spielen eine wichtige Rolle in der Kommunikation. KI-Modelle können nun Bilder aus Textbeschreibungen generieren. Diese Beschreibungen nennen wir 'Prompts'. Je präziser und detaillierter der Prompt, desto besser das Ergebnis."
        },
        "Kleine Übungen": {
          "type": "array",
          "items": [
            {
              "type": "string",
              "content": "Denken Sie an ein einfaches Bild. Beschreiben Sie es möglichst genau in Worten."
            },
            {
              "type": "string",
              "content": "Vergleichen Sie Ihre Beschreibung mit der eines Partners. Welche Details wurden unterschiedlich formuliert?"
            }
          ]
        },
        "Diskussionsfragen": {
          "type": "array",
          "items": [
            {
              "type": "string",
              "content": "Wo könnten KI-generierte Bilder im Alltag nützlich sein?"
            },
            {
              "type": "string",
              "content": "Welche Herausforderungen seht ihr bei der Bildgenerierung durch KI?"
            }
          ]
        },
        "Schlüsselpassagen": {
          "type": "array",
          "items": [
            {
              "type": "string",
              "content": "Ein Bild-Prompt ist eine Textbeschreibung des gewünschten Bildes."
            },
            {
              "type": "string",
              "content": "Die Qualität des Prompts beeinflusst die Qualität des generierten Bildes."
            }
          ]
        }
      },
      {
        "KapitelTitel": {
          "type": "string",
          "content": "Prompting-Techniken für bessere Bilder"
        },
        "Theoretische Grundlagen": {
          "type": "string",
          "content": "Es gibt verschiedene Techniken, um effektive Prompts zu erstellen: \n- **Style Modifiers:** Beschreiben den Stil des Bildes (z.B. 'Fotografie', 'Cartoon', 'Renaissance Gemälde')\n- **Quality Boosters:** Verbessern die Bildqualität (z.B. 'hochauflösend', 'detailreich', 'scharf')\n- **Repetition:** Hervorhebung wichtiger Elemente durch Wiederholung\n- **Weighted Terms:** Gewichtung einzelner Wörter für stärkere Betonung\n- **Fix Deformed Generations:** Vermeidung von Fehlern in der Bildgenerierung (z.B. verzerrte Hände)"
        },
        "Kleine Übungen": {
          "type": "array",
          "items": [
            {
              "type": "string",
              "content": "Wählen Sie ein Bild aus einer Zeitschrift und schreiben Sie verschiedene Prompts mit unterschiedlichen Style Modifiers."
            },
            {
              "type": "string",
              "content": "Formulieren Sie einen Prompt für ein Objekt und verwenden Sie Quality Boosters, um die Detailgenauigkeit zu erhöhen."
            }
          ]
        },
        "Tipps": {
          "type": "array",
          "items": [
            {
              "type": "string",
              "content": "Nutzen Sie mehrere Techniken in Kombination für optimale Ergebnisse."
            },
            {
              "type": "string",
              "content": "Experimentieren Sie mit verschiedenen Formulierungen und vergleichen Sie die generierten Bilder."
            }
          ]
        },
        "Diskussionsfragen": {
          "type": "array",
          "items": [
            {
              "type": "string",
              "content": "Welche Prompting-Techniken findet ihr am effektivsten? Warum?"
            },
            {
              "type": "string",
              "content": "Können KI-Modelle durch gute Prompts 'kreativer' werden?"
            }
          ]
        },
        "Schlüsselpassagen": {
          "type": "array",
          "items": [
            {
              "type": "string",
              "content": "Style Modifiers und Quality Boosters sind essenziell für die Bildgestaltung."
            },
            {
              "type": "string",
              "content": "Durchdachte Prompts führen zu aussagekräftigeren und qualitativ hochwertigeren Bildern."
            }
          ]
        }
      }
    ],
    "Hands-on Labs": [
      {
        "LabTitel": {
          "type": "string",
          "content": "Kreative Bildgenerierung mit DALL-E 2"
        },
        "Beschreibung": {
          "type": "string",
          "content": "In diesem Lab experimentieren wir mit dem KI-Modell DALL-E 2 und generieren eigene Bilder mithilfe von Text-Prompts. Dabei lernen wir die Benutzeroberfläche kennen und wenden die verschiedenen Prompting-Techniken an."
        },
        "Ziele": {
          "type": "array",
          "items": [
            {
              "type": "string",
              "content": "Einrichtung und Bedienung der DALL-E 2 Plattform"
            },
            {
              "type": "string",
              "content": "Praktische Anwendung der Prompting-Techniken"
            },
            {
              "type": "string",
              "content": "Analyse und Vergleich der generierten Bilder"
            }
          ]
        },
        "Anleitung": {
          "type": "string",
          "content": "1. Melden Sie sich bei der DALL-E 2 Plattform an.\n2. Beginnen Sie mit einem einfachen Bild-Prompt und generieren Sie ein Bild.\n3. Verfeinern Sie den Prompt schrittweise mit Style Modifiers, Quality Boosters etc.\n4. Experimentieren Sie mit verschiedenen Kombinationen von Prompting-Techniken.\n5. Dokumentieren Sie Ihre Ergebnisse und vergleichen Sie die generierten Bilder."
        }
      }
    ],
    "Hacks": {
      "type": "array",
      "items": [
        {
          "type": "string",
          "content": "Nutzen Sie Online-Bibliotheken mit Beispiel-Prompts als Inspiration."
        },
        {
          "type": "string",
          "content": "Analysieren Sie die Bildbeschreibungen von Kunstwerken, um Ihren Schreibstil zu verbessern."
        }
      ]
    },
    "Zusammenfassung": {
      "type": "string",
      "content": "KI-Modelle ermöglichen es uns, Bilder durch die Kraft der Sprache zu erschaffen. Mit den richtigen Prompting-Techniken können wir die Bildgenerierung gezielt beeinflussen und qualitativ hochwertige Ergebnisse erzielen. Die Möglichkeiten sind grenzenlos – Ihrer Kreativität sind keine Grenzen gesetzt!"
    }
  }
}
```