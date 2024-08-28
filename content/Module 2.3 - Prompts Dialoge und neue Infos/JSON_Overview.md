{
  "type": "object",
  "properties": {
    "Modul": {
      "type": "string",
      "content": "Einführung in Prompt Engineering: Den LLMs neue Informationen beibringen"
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
          "content": "Die Teilnehmenden verstehen die Notwendigkeit, LLMs mit neuen Informationen zu versorgen."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden lernen, wie man neue Informationen in Prompts einfügt."
        },
        {
          "type": "string",
          "content": "Die Teilnehmenden erkennen die Grenzen der Promptgrösse und lernen Strategien zur Informationsverdichtung kennen."
        }
      ]
    },
    "Kapitel": {
      "type": "array",
      "items": [
        {
          "KapitelTitel": {
            "type": "string",
            "content": "LLMs und die Notwendigkeit neuer Informationen"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "LLMs wie ChatGPT werden mit riesigen Datenmengen trainiert, haben aber einen Wissensstand vom Zeitpunkt ihres letzten Trainings. Um Informationen nach diesem Zeitpunkt oder private Daten zu verarbeiten, müssen wir sie direkt im Prompt bereitstellen."
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Überlegen Sie sich Beispiele für Informationen, die ChatGPT möglicherweise nicht kennt (z.B. aktuelle Sportergebnisse, neue wissenschaftliche Erkenntnisse)."
              }
            ]
          },
          "Techniken für Prompting": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Fügen Sie die neuen Informationen direkt im Prompt ein, bevor Sie Ihre Frage stellen oder eine Aufgabe erteilen."
              }
            ]
          },
          "Tipps": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Achten Sie darauf, dass Sie keine vertraulichen Informationen in den Prompt einfügen, die nicht für die Öffentlichkeit bestimmt sind."
              }
            ]
          },
          "Diskussionsfragen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Welche Herausforderungen könnten sich aus der Notwendigkeit ergeben, LLMs ständig mit neuen Informationen zu versorgen?"
              },
              {
                "type": "string",
                "content": "Welche Auswirkungen könnte es haben, wenn LLMs Zugang zu privaten Daten erhalten?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Large language models are going to be trained up to some point and then there's going to be a cut-off and they don't know what's happened after that cutoff."
              },
              {
                "type": "string",
                "content": "Anytime we want to go and introduce new information to the large language model that it didn't have access to when it was trained, all we have to do is put it into the prompt."
              }
            ]
          }
        },
        {
          "KapitelTitel": {
            "type": "string",
            "content": "Prompt Size Limitations: Mit Informationsgrenzen umgehen"
          },
          "Theoretische Grundlagen": {
            "type": "string",
            "content": "Prompts haben eine begrenzte Grösse. Zu viele Informationen können dazu führen, dass der LLM die Aufgabe nicht ausführen kann. Daher ist es wichtig, Informationen zu filtern, zusammenzufassen und zu priorisieren."
          },
          "Kleine Übungen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Versuchen Sie, einen langen Text in wenigen Sätzen zusammenzufassen, ohne wichtige Informationen zu verlieren."
              }
            ]
          },
          "Techniken für Prompting": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Verwenden Sie Listen und Tabellen, um Informationen zu strukturieren."
              },
              {
                "type": "string",
                "content": "Konzentrieren Sie sich auf die wichtigsten Schlüsselwörter und Fakten."
              }
            ]
          },
          "Tipps": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Nutzen Sie die Möglichkeiten von LLMs, um Informationen zusammenzufassen. Geben Sie dem LLM den Auftrag, einen Text zu kürzen und nur die wichtigsten Punkte beizubehalten."
              }
            ]
          },
          "Diskussionsfragen": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Welche ethischen Überlegungen könnten bei der Auswahl und Priorisierung von Informationen für LLMs eine Rolle spielen?"
              }
            ]
          },
          "Schlüsselpassagen": {
            "type": "array",
            "items": [
              "type": "string",
              "content": "A really critical thing to understand is that a prompt is fundamentally the input that we have into the model and we have a limitation on the size of the prompt that we can create."
            ],
            [
              "type": "string",
              "content": "One of the goals that we have as users is to try to select and use only the information that we need in order to perform the task that we're asking ChatGPT to perform."
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
            "content": "Aktuelles Ereignis mit ChatGPT analysieren"
          },
          "Beschreibung": {
            "type": "string",
            "content": "In diesem Lab suchen Sie Informationen zu einem aktuellen Ereignis und lassen ChatGPT dieses analysieren."
          },
          "Ziele": {
            "type": "array",
            "items": [
              {
                "type": "string",
                "content": "Einen geeigneten Prompt erstellen, der ChatGPT mit den notwendigen Informationen versorgt."
              },
              {
                "type": "string",
                "content": "Die Antwort von ChatGPT kritisch bewerten."
              }
            ]
          },
          "Anleitung": {
            "type": "string",
            "content": "1. Wählen Sie ein aktuelles Ereignis aus (z.B. eine neue technologische Entwicklung, ein politisches Ereignis). \n2. Recherchieren Sie Informationen zu diesem Ereignis aus vertrauenswürdigen Quellen. \n3. Erstellen Sie einen Prompt, der ChatGPT über das Ereignis informiert und eine Analyse anfordert (z.B. 'Informieren Sie sich über [Ereignis] und erklären Sie die möglichen Auswirkungen auf die Gesellschaft.'). \n4. Geben Sie den Prompt in ChatGPT ein und analysieren Sie die Antwort. \n5. Diskutieren Sie die Ergebnisse im Kurs: War die Antwort von ChatGPT hilfreich? Waren die Informationen korrekt und vollständig? Wie könnte der Prompt verbessert werden?"
          }
        }
      ]
    },
    "Hacks": {
      "type": "array",
      "items": [
        {
          "type": "string",
          "content": "Verwenden Sie verschiedene Prompt-Formulierungen, um die bestmöglichen Ergebnisse von LLMs zu erzielen."
        },
        {
          "type": "string",
          "content": "Experimentieren Sie mit verschiedenen Arten von Informationen (z.B. Text, Listen, Tabellen), um herauszufinden, welche Formate am besten funktionieren."
        }
      ]
    },
    "Zusammenfassung": {
      "type": "string",
      "content": "In diesem Modul haben wir gelernt, wie wichtig es ist, LLMs mit neuen Informationen zu versorgen, um ihre volle Leistungsfähigkeit zu nutzen. Durch geschicktes Prompt Engineering können wir sicherstellen, dass LLMs auch bei begrenzter Promptgrösse effektiv mit aktuellen und spezifischen Daten umgehen können."
    }
  }
}
