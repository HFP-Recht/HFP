```json
{
  "type": "object",
  "properties": {
    "Modul": {
      "type": "string",
      "content": "Modul 2: Fortgeschrittene Prompt Engineering Techniken"
    },
    "Zielgruppe": {
      "type": "string",
      "content": "Berufsschüler / Gymnasiasten"
    },
    "Dauer": {
      "type": "string",
      "content": "180 Minuten"
    },
    "Learning goals": [
      "Die Teilnehmenden können die Herausforderungen und Chancen im Zusammenhang mit grossen Sprachmodellen (LLMs) erläutern.",
      "Die Teilnehmenden können verschiedene Prompt Engineering Techniken anwenden, um die Zuverlässigkeit und Qualität von LLM-Antworten zu verbessern.",
      "Die Teilnehmenden können die Vorteile von effektiven Text-Prompts erklären und anwenden.",
      "Die Teilnehmenden können die Interview-Pattern-Technik anwenden, um spezifischere Antworten von LLMs zu erhalten.",
      "Die Teilnehmenden können die Chain-of-Thought- und Tree-of-Thought-Ansätze verwenden, um komplexere Denkvorgänge in LLMs zu fördern."
    ],
    "Kapitel": [
      {
        "KapitelTitel": "Prompt Engineering Techniken für Text-zu-Text",
        "Theoretische Grundlagen": "Prompt Engineering ist der Schlüssel zur Nutzung der Leistungsfähigkeit von grossen Sprachmodellen (LLMs). Es geht darum, präzise Anweisungen zu geben, um die gewünschten Ergebnisse zu erzielen. Stellen Sie sich das so vor: Ein LLM ist wie ein Schweizer Uhrwerk, präzise und komplex. Prompt Engineering ist das Einstellen der Zahnräder, um die gewünschte Ausgabe zu erhalten.",
        "Kleine Übungen": [
          "Formulieren Sie einen Prompt, um eine Zusammenfassung eines Textes über künstliche Intelligenz zu erhalten.",
          "Erstellen Sie einen Prompt, um ein Gedicht im Stil von Friedrich Schiller zu generieren."
        ],
        "Techniken für Prompting": [
          "**Aufgabenspezifikation:** Seien Sie klar und deutlich, was das LLM tun soll. Beispiel: 'Übersetze diesen Satz ins Englische.'",
          "**Kontextbezogene Anleitung:** Geben Sie dem LLM genügend Informationen, um die Anfrage zu verstehen. Beispiel: 'Schreibe eine kurze Geschichte über einen Hund, der in den Schweizer Alpen lebt.'",
          "**Fachwissen:** Verwenden Sie bei Bedarf fachspezifische Terminologie.",
          "**Verzerrungsreduktion:** Fordern Sie explizit neutrale Antworten an, um Vorurteile zu minimieren.",
          "**Framing:** Setzen Sie Grenzen für die Ausgabe, z. B. die Länge oder den Stil.",
          "**Zero-Shot-Prompting:** Nutzen Sie die Fähigkeit des LLMs, Aufgaben ohne vorheriges Training auszuführen.",
          "**User-Feedback-Schleife:** Verfeinern Sie Prompts iterativ basierend auf den Antworten des LLMs.",
          "**Few-Shot-Prompting:** Geben Sie dem LLM einige Beispiele, um das gewünschte Ausgabeformat zu demonstrieren."
        ],
        "Tipps": [
          "Verwenden Sie einfache Sprache und vermeiden Sie Fachbegriffe, es sei denn, sie sind notwendig.",
          "Experimentieren Sie mit verschiedenen Prompt-Formulierungen, um herauszufinden, was am besten funktioniert."
        ],
        "Diskussionsfragen": [
          "Welche Herausforderungen sehen Sie bei der Anwendung von Prompt Engineering?",
          "Wie können wir sicherstellen, dass LLMs ethisch und verantwortungsvoll eingesetzt werden?"
        ],
        "Schlüsselpassagen": [
          "Die Qualität und Relevanz der generierten Ausgabe hängen von der Effektivität des Prompts und der Leistungsfähigkeit des LLMs ab.",
          "Effektive Text-Prompts erhöhen die Erklärbarkeit des Modells, fördern das Vertrauen zwischen Benutzern und Modellen und tragen dazu bei, ethische Bedenken auszuräumen."
        ]
      },
      {
        "KapitelTitel": "Interview Pattern Approach",
        "Theoretische Grundlagen": "Stellen Sie sich vor, Sie führen ein Interview mit dem LLM. Anstatt eine einzelne Frage zu stellen, stellen Sie mehrere, aufeinander aufbauende Fragen, um detailliertere und relevantere Antworten zu erhalten.",
        "Kleine Übungen": [
          "Entwerfen Sie eine Reihe von Fragen, um ein LLM dazu zu bringen, einen Reiseplan für einen Wochenendausflug in die Schweizer Alpen zu erstellen.",
          "Verwenden Sie die Interview-Pattern-Technik, um ein LLM dazu zu bringen, eine fiktive Geschichte über einen Tag im Leben eines Schweizer Uhrmachers zu schreiben."
        ],
        "Techniken für Prompting": [
          "Beginnen Sie mit einer klaren Rollendefinition für das LLM (z. B. Reiseexperte, Journalist).",
          "Stellen Sie offene Fragen, die zu detaillierten Antworten anregen.",
          "Bauen Sie auf den Antworten des LLMs auf und stellen Sie Folgefragen.",
          "Verwenden Sie die Antworten des LLMs, um den Kontext für nachfolgende Fragen zu schaffen."
        ],
        "Tipps": [
          "Seien Sie geduldig und scheuen Sie sich nicht, mehrere Fragen zu stellen.",
          "Versetzen Sie sich in die Lage des Benutzers und überlegen Sie, welche Informationen er benötigt, um die Aufgabe zu erledigen."
        ],
        "Diskussionsfragen": [
          "Welche Vorteile bietet die Interview-Pattern-Technik im Vergleich zu herkömmlichen Prompting-Methoden?",
          "In welchen Situationen ist die Interview-Pattern-Technik besonders nützlich?"
        ],
        "Schlüsselpassagen": [
          "Der Interview-Pattern-Ansatz ist dem konventionellen Prompting-Ansatz überlegen, da er eine dynamischere und iterativere Konversation bei der Interaktion mit generativen KI-Modellen ermöglicht.",
          "Anstatt einen einzigen statischen Prompt bereitzustellen, beinhaltet das Interview-Pattern einen Hin- und Her-Austausch von Informationen mit dem Modell."
        ]
      },
      {
        "KapitelTitel": "Chain-of-Thought und Tree-of-Thought",
        "Theoretische Grundlagen": "Manchmal müssen wir LLMs helfen, komplexe Probleme Schritt für Schritt zu lösen. Chain-of-Thought gibt dem LLM ein Beispiel für einen logischen Denkprozess vor. Tree-of-Thought geht noch einen Schritt weiter und lässt das LLM verschiedene Möglichkeiten erkunden, wie ein Entscheidungsbaum.",
        "Kleine Übungen": [
          "Verwenden Sie Chain-of-Thought, um ein LLM bei der Lösung eines Textaufgabenproblems zu unterstützen.",
          "Entwickeln Sie mithilfe von Tree-of-Thought eine Strategie für ein LLM, um ein Schachspiel zu gewinnen."
        ],
        "Techniken für Prompting": [
          "**Chain-of-Thought:** Gliedern Sie ein komplexes Problem in kleinere, leichter verständliche Schritte auf. Geben Sie dem LLM ein Beispiel für diesen Denkprozess.",
          "**Tree-of-Thought:** Fordern Sie das LLM auf, verschiedene Möglichkeiten in Betracht zu ziehen und zu bewerten, bevor es eine Entscheidung trifft. Visualisieren Sie dies wie einen Entscheidungsbaum."
        ],
        "Tipps": [
          "Verwenden Sie klare und prägnante Sprache, um die einzelnen Schritte im Denkprozess zu beschreiben.",
          "Ermutigen Sie das LLM, seine Argumentation zu erläutern, um Transparenz zu gewährleisten."
        ],
        "Diskussionsfragen": [
          "Wie können Chain-of-Thought und Tree-of-Thought dazu beitragen, die Argumentationsfähigkeiten von LLMs zu verbessern?",
          "Welche Arten von Problemen eignen sich besonders gut für diese Ansätze?"
        ],
        "Schlüsselpassagen": [
          "Der Chain-of-Thought-Ansatz stärkt die kognitiven Fähigkeiten generativer KI-Modelle und fordert einen schrittweisen Denkprozess.",
          "Der Tree-of-Thought-Ansatz ist eine innovative Technik, die auf dem Chain-of-Thought-Ansatz aufbaut und die hierarchische Strukturierung von Prompts beinhaltet."
        ]
      }
    ],
    "Hands-on Labs": [
      {
        "LabTitel": "Erstellen Sie Ihren eigenen Chatbot",
        "Beschreibung": "In diesem Praktikum erstellen Sie Ihren eigenen Chatbot mit einem LLM und den erlernten Prompt Engineering Techniken.",
        "Ziele": [
          "Praktische Erfahrung mit Prompt Engineering Techniken sammeln.",
          "Die Funktionsweise von Chatbots und LLMs besser verstehen.",
          "Kreativität und Problemlösungskompetenz fördern."
        ],
        "Anleitung": "1. Wählen Sie ein Thema für Ihren Chatbot (z. B. Filmempfehlungen, Reiseplanung).\n2. Verwenden Sie eine geeignete Plattform oder ein geeignetes Tool, um Ihren Chatbot zu erstellen.\n3. Wenden Sie die erlernten Prompt Engineering Techniken an, um die Antworten Ihres Chatbots zu optimieren.\n4. Testen Sie Ihren Chatbot und verbessern Sie ihn iterativ."
      }
    ],
    "Hacks": [
      "Verwenden Sie Emojis in Ihren Prompts, um dem LLM den Ton und die Emotionen besser zu vermitteln.",
      "Experimentieren Sie mit verschiedenen Sprachen, um zu sehen, wie das LLM reagiert.",
      "Nutzen Sie Online-Communities und Ressourcen, um sich mit anderen Prompt-Engineers auszutauschen und neue Techniken zu lernen."
    ],
    "Zusammenfassung": "In diesem Modul haben Sie gelernt, wie Sie durch effektives Prompt Engineering die Leistungsfähigkeit von LLMs voll ausschöpfen können. Sie haben verschiedene Techniken kennengelernt, um präzisere, relevantere und kreativere Antworten von LLMs zu erhalten. Denken Sie daran, dass Prompt Engineering ein iterativer Prozess ist. Experimentieren Sie weiter, um herauszufinden, was für Sie am besten funktioniert, und bleiben Sie über die neuesten Entwicklungen in diesem spannenden Bereich auf dem Laufenden!"
  }
}
```