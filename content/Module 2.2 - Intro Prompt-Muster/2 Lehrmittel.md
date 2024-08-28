# Prompt Engineering: Der Persona Pattern: Theoretische Grundlagen
> [!info] Wieso Prompt Engineering?
>- **Prompt Engineering** ist der **Schlüssel**, um das **volle Potenzial** von **LLMs** (Large Language Models) zu nutzen.
>- Es ermöglicht uns, **präzise Anweisungen** zu geben und die **gewünschten Ergebnisse** zu erzielen.
>- **Gut formulierte Prompts** führen zu **besseren**, **relevanteren** und **kreativeren** Ausgaben von **LLMs**.
>- **Prompt Engineering** ist eine **entscheidende Fähigkeit** in der heutigen Zeit, da **LLMs** immer weiter verbreitet sind.
>- **Mit effektivem Prompt Engineering** können wir **LLMs** in verschiedenen Bereichen einsetzen, von der **Textgenerierung** bis hin zur **Softwareentwicklung**. 

---

## Inhalte
- Einführung in Prompt Patterns
- Der Persona Pattern

---
### Einführung in Prompt Patterns
>[!info]- Grundlagen
>- **Prompt Patterns** sind **vorgefertigte Strukturen** oder **Formulierungen**, die uns helfen, effektive **Prompts** für **LLMs** zu erstellen.
>- Sie bieten einen **Rahmen** für die **Kommunikation** mit **LLMs** und machen sie **verständlicher**.
>- **Prompt Patterns** helfen uns, die **Komplexität** von **LLMs** zu bewältigen und **konsistente Ergebnisse** zu erzielen.
>- Es gibt **verschiedene Arten** von **Prompt Patterns**, die auf **unterschiedliche Anwendungsfälle** zugeschnitten sind.
>- Durch die Verwendung von **Prompt Patterns** können wir die **Genauigkeit**, **Kreativität** und **Nützlichkeit** von **LLM-Ausgaben** verbessern.

>[!abstract]- Funktionsweise
>- **Identifizieren Sie das Ziel**: Was möchten Sie mit dem **LLM** erreichen? 
>- **Wählen Sie den passenden Prompt Pattern**: Je nach **Ziel** und **gewünschter Ausgabe** gibt es verschiedene **Patterns**, die sich anbieten.
>- **Passen Sie den Pattern an**:  Füllen Sie die **Platzhalter** im **Pattern** mit Ihren **spezifischen Informationen** und **Anweisungen**.
>- **Testen und optimieren**:  Experimentieren Sie mit **verschiedenen Formulierungen** und **Parametern**, um die **besten Ergebnisse** zu erzielen.

>[!example]- Demonstration
> **Beispiel für einen Prompt Pattern zur Textzusammenfassung:**
> 1. **Ziel:**  Einen längeren Text automatisch zusammenfassen lassen.
> 2. **Prompt Pattern:** "Fasse den folgenden Text in drei Sätzen zusammen: [Text einfügen]"
> 3. **Anpassung:** Ersetzen Sie "[Text einfügen]" durch den Text, den Sie zusammenfassen möchten.
> 4. **Testen und optimieren:**  Sie können den Prompt anpassen, indem Sie die Anzahl der Sätze ändern oder zusätzliche Anweisungen geben, z.B. "Konzentriere dich auf die wichtigsten Punkte".

>[!tip]- Anwendungen
>- **Texterstellung**:  Generieren Sie kreative Inhalte, übersetzen Sie Sprachen, fassen Sie Texte zusammen.
>- **Ideenfindung**:  Entwickeln Sie neue Konzepte, brainstormen Sie Lösungen, finden Sie Inspiration.
>- **Programmierung**:  Generieren Sie Code, debuggen Sie Programme, kommentieren Sie Code.

## Übungen 
>[!question] Auftrag:  Formulieren Sie einen Prompt
>Entwickeln Sie einen eigenen Prompt, um ein LLM aufzufordern, eine Liste mit fünf Buchtipps für den Sommerurlaub zu erstellen. 
>>[!todo]- Anleitung 
>>1. Überlegen Sie, welche Informationen für die Auswahl der Bücher relevant sind (Genre, Autor, Thema).
>>2. Formulieren Sie einen Prompt, der diese Informationen abfragt.
>>3. Testen Sie Ihren Prompt mit einem LLM und bewerten Sie die Ergebnisse.
>
>>[!example]- Beispiel
>>"Erstelle eine Liste mit fünf spannenden Krimis, die sich gut für den Urlaub eignen.  Nenne Autor und eine kurze Inhaltsangabe."

>[!tip]- Weitere Hinweise
>- Seien Sie präzise in Ihrer Anfrage.
>- Verwenden Sie eine klare und verständliche Sprache.
>- Geben Sie dem LLM genügend Kontextinformationen.
>### Probieren Sie selber
>- Wie könnten Sie einen Prompt formulieren, um ein LLM aufzufordern, einen Businessplan zu erstellen?
>- Wie könnten Sie einen Prompt formulieren, um ein LLM aufzufordern, ein Gedicht im Stil von Friedrich Schiller zu schreiben?
>- Wie könnten Sie einen Prompt formulieren, um ein LLM aufzufordern, die Vor- und Nachteile von Elektroautos aufzulisten?

> [!question]- Diskussionsfragen
>- Welche Herausforderungen seht ihr beim Formulieren von effektiven Prompts?
>- Wie können wir sicherstellen, dass die Ausgabe eines LLMs unseren Erwartungen entspricht?


---
### Der Persona Pattern
>[!info]- Grundlagen
>- Der **Persona Pattern** ist ein **spezieller Prompt Pattern**, der es uns ermöglicht, **LLMs** anzuweisen, aus der **Perspektive einer bestimmten Persona** zu antworten.
>- Eine **Persona** kann eine **reale Person** (z.B. Albert Einstein, Oprah Winfrey) oder eine **fiktive Figur** (z.B. Harry Potter, Sherlock Holmes) sein.
>- Durch die Verwendung des **Persona Patterns** können wir **LLM-Ausgaben** **personalisieren** und **interessantere** und **einzigartigere** Ergebnisse erzielen.

>[!abstract]- Funktionsweise
>- **Definieren Sie die Persona**:  Wählen Sie eine **Persona**, die zum **Thema** und **Ziel** Ihres Prompts passt.
>- **Geben Sie dem LLM die Rolle**:  Weisen Sie dem **LLM** die **Persona** zu, indem Sie im Prompt formulieren: "Antworte als [Persona]".
>- **Stellen Sie Ihre Fragen**:  Formulieren Sie Ihre Fragen so, als würden Sie mit der **Persona** sprechen.
>- **Bewerten Sie die Antworten**:  Achten Sie darauf, ob die Antworten der **Persönlichkeit** und dem **Wissen** der **gewählten Persona** entsprechen.

>[!example]- Demonstration
> **Beispiel für den Persona Pattern:**
> 1. **Persona:** Albert Einstein
> 2. **Prompt:** "Antworte als Albert Einstein.  Was ist deine Meinung zur Bedeutung von Kreativität in der Wissenschaft?"
> 3. **Erwartete Ausgabe:**  Eine Antwort, die Einsteins Ansichten über Kreativität und Wissenschaft widerspiegelt, möglicherweise mit Anekdoten oder Zitaten aus seinem Leben.

>[!tip]- Anwendungen
>- **Kreatives Schreiben**:  Schreiben Sie Dialoge, Geschichten oder Gedichte aus der Perspektive verschiedener Charaktere.
>- **Marketing und Werbung**:  Erstellen Sie personalisierte Marketingbotschaften, die auf die Interessen der Zielgruppe zugeschnitten sind.
>- **Kundenservice**:  Entwickeln Sie Chatbots, die auf Kundenanfragen mit Empathie und Persönlichkeit reagieren.

## Übungen 
>[!question] Auftrag:  Der Persona Pattern im Einsatz
>Wählen Sie eine historische Figur oder eine fiktive Figur und formulieren Sie einen Prompt, der das LLM auffordert, aus der Perspektive dieser Persona zu antworten.
>>[!todo]- Anleitung 
>>1.  Wählen Sie eine Persona, die Sie interessant finden.
>>2.  Recherchieren Sie die Persona, um mehr über ihre Persönlichkeit, ihren Hintergrund und ihre Ansichten zu erfahren.
>>3.  Formulieren Sie einen Prompt, der die Persona klar definiert und eine Frage stellt, die für diese Persona relevant ist.
>
>>[!example]- Beispiel
>>**Persona:** Marie Curie
>>**Prompt:**  "Antworte als Marie Curie.  Was sind die grössten Herausforderungen für Frauen in der Wissenschaft?"

>[!tip]- Weitere Hinweise
>- Seien Sie kreativ bei der Auswahl Ihrer Persona.
>- Stellen Sie Fragen, die zum Charakter und zur Geschichte der Persona passen.
>- Experimentieren Sie mit verschiedenen Formulierungen, um die besten Ergebnisse zu erzielen.
>### Probieren Sie selber
>- Wie könnten Sie den Persona Pattern nutzen, um ein Interview mit einer historischen Figur zu simulieren?
>- Wie könnten Sie den Persona Pattern nutzen, um eine Geschichte aus der Perspektive eines Tieres zu schreiben?
>- Wie könnten Sie den Persona Pattern nutzen, um ein Rollenspiel mit mehreren Charakteren zu erstellen?

> [!question]- Diskussionsfragen
>- Welche ethischen Überlegungen sollten wir bei der Verwendung des Persona Patterns berücksichtigen?
>- Kann der Persona Pattern dazu führen, dass LLMs verzerrte oder stereotype Antworten generieren?
>- Wie können wir sicherstellen, dass der Persona Pattern verantwortungsvoll eingesetzt wird?

---

>[!abstract]- Zusammenfassung
> **Prompt Engineering** ist eine **essenzielle Fähigkeit**, um das Beste aus **LLMs** herauszuholen. Der **Persona Pattern** ist ein **leistungsstarkes Werkzeug**, mit dem wir **LLM-Ausgaben** **personalisieren** und **kreativere** und **einzigartigere** Ergebnisse erzielen können. Durch **Experimentieren** und **Üben** können wir lernen, **effektive Prompts** zu erstellen und das **volle Potenzial** von **LLMs** zu entfalten. 
