# Fortgeschrittene Prompting-Techniken: Theoretische Grundlagen

> [!info] Wieso fortgeschrittene Prompting-Techniken?
>- **Fortgeschrittene Prompting-Techniken** ermöglichen eine **effizientere** und **präzisere** **Interaktion** mit **grossen Sprachmodellen (LLMs)**.
>- Sie helfen, die **Leistungsfähigkeit** von **LLMs** für **komplexe Aufgaben** zu nutzen, die über die reine **Textgenerierung** hinausgehen.
>- **Fortgeschrittene Prompts** können **LLMs** dazu bringen, **strukturierte Daten** zu extrahieren, **Code** zu schreiben oder **kreative Inhalte** in **verschiedenen Formaten** zu generieren.
>- Das Verständnis dieser **Techniken** ist entscheidend, um **LLMs** in **realen Anwendungen** effektiv einzusetzen, z.B. in der **Softwareentwicklung**, im **Marketing** oder im **Kundenservice**.
>- **Fortgeschrittene Prompting-Techniken** sind ein **Schlüssel** zur **Entwicklung innovativer Anwendungen** im Bereich der **künstlichen Intelligenz**.

---

## Inhalte
- Das Gameplay-Muster
- Das Template-Muster

---
### Das Gameplay-Muster
>[!info]- Grundlagen
>- Das **Gameplay-Muster** nutzt die Fähigkeit von **LLMs**, **Spiele** zu **verstehen** und zu **spielen**.
>- Es ermöglicht, **spielerische Lernumgebungen** zu schaffen, in denen Benutzer mit **LLMs** interagieren und ihre **Fähigkeiten** verbessern können.
>- **LLMs** können als **Spielmaster** fungieren, **Regeln** festlegen, **Herausforderungen** generieren und **Feedback** geben.
>- Das **Gameplay-Muster** eignet sich besonders für das **Erlernen neuer Konzepte**, das **Testen von Wissen** und die **Förderung von Kreativität**.

>[!abstract]- Funktionsweise
>- **Spieldefinition**: Der Benutzer definiert das **Thema** und die **grundlegenden Regeln** des Spiels.
>- **Rollenverteilung**: Das **LLM** übernimmt die Rolle des **Spielmasters**, während der Benutzer als **Spieler** agiert.
>- **Spielverlauf**: Das **LLM** generiert **Aufgaben** oder **Herausforderungen** basierend auf den **Spielregeln**.
>- **Benutzerinteraktion**: Der Benutzer interagiert mit dem **LLM**, indem er **Antworten** gibt, **Aktionen** ausführt oder **Entscheidungen** trifft.
>- **Feedback und Bewertung**: Das **LLM** gibt **Feedback** auf die Aktionen des Benutzers und **bewertet** seinen **Fortschritt**.

>[!example]- Demonstration
>**Quiz-Spiel mit ChatGPT:**
>1. Öffnen Sie die ChatGPT-Webseite.
>2. Geben Sie einen Prompt ein, der ChatGPT auffordert, ein Quiz zu einem bestimmten Thema zu erstellen, z.B. "Erstelle ein Quiz mit 5 Fragen zum Thema Schweizer Geschichte."
>3. ChatGPT generiert die Fragen und die Antwortmöglichkeiten.
>4. Beantworten Sie die Fragen und ChatGPT wertet Ihre Antworten aus.
>5. ChatGPT gibt Ihnen Feedback zu Ihrem Ergebnis und zeigt Ihnen die richtigen Antworten.

>[!tip]- Anwendungen
>- **Quizspiele**: **LLMs** können **Quizfragen** zu **verschiedenen Themen** generieren und die **Antworten** der Benutzer **auswerten**.
>- **Rätselspiele**: **LLMs** können **Rätsel** erstellen, **Hinweise** geben und die **Lösungen** der Benutzer **überprüfen**.
>- **Abenteuerspiele**: **LLMs** können **interaktive Geschichten** generieren, in denen Benutzer **Entscheidungen** treffen und den **Verlauf der Geschichte** beeinflussen.
>- **Lernspiele**: **LLMs** können **spielerische Lernumgebungen** schaffen, in denen Benutzer **neue Konzepte** lernen und ihr **Wissen** testen können.

## Übungen 
>[!question] Auftrag:  Ein Quiz mit dem Gameplay-Muster erstellen
>Entwerfen Sie ein Quizspiel mit ChatGPT zum Thema "Hauptstädte Europas".
>>[!todo]- Anleitung 
>>1. Definieren Sie die **Regeln** des Spiels, z.B. wie viele Fragen gestellt werden, wie die Punktevergabe erfolgt.
>>2. Schreiben Sie einen **Prompt**, der ChatGPT auffordert, als **Spielmaster** zu fungieren und das Quiz zu starten.
>>3. Testen Sie Ihr Quizspiel, indem Sie es mit ChatGPT spielen.
>
>>[!example]- Beispiel
>>**Prompt:** "Lass uns ein Quiz spielen. Du bist der Spielmaster. Das Thema ist 'Hauptstädte Europas'. Stelle mir 5 Fragen und gib mir nach jeder Frage Feedback, ob meine Antwort richtig oder falsch war."

>[!tip]- Weitere Hinweise
>- Verwenden Sie **klare und präzise Sprache** in Ihrem Prompt.
>- Geben Sie ChatGPT **genügend Kontextinformationen**, damit es das Spiel verstehen kann.
>- Seien Sie **kreativ** bei der Gestaltung der Fragen und Antworten.
>### Probieren Sie selber
>- Wie könnten Sie das Gameplay-Muster nutzen, um ein Spiel zum Lernen von Vokabeln zu erstellen?
>- Wie könnten Sie das Gameplay-Muster nutzen, um ein Spiel zum Üben von mathematischen Aufgaben zu erstellen?
>- Wie könnten Sie das Gameplay-Muster nutzen, um ein Spiel zum Trainieren von Programmierkenntnissen zu erstellen?

> [!question]- Diskussionsfragen
>- Welche Vorteile bietet das Gameplay-Muster im Vergleich zu traditionellen Lernmethoden?
>- Welche Herausforderungen gibt es beim Einsatz des Gameplay-Musters?

---

### Das Template-Muster
>[!info]- Grundlagen
>- Das **Template-Muster** ermöglicht es, die **Ausgabe von LLMs** zu **strukturieren** und in einem **gewünschten Format** zu erhalten.
>- Es basiert auf der Verwendung von **Vorlagen** mit **Platzhaltern**, die vom **LLM** mit den entsprechenden Informationen gefüllt werden.
>- Das **Template-Muster** ist nützlich, um **konsistente** und **übersichtliche Ausgaben** zu erzeugen, z.B. für **Tabellen**, **Listen** oder **Formulare**.

>[!abstract]- Funktionsweise
>- **Vorlage erstellen**: Der Benutzer definiert eine **Vorlage** mit **Platzhaltern** für die gewünschten Informationen.
>- **Platzhalter definieren**: Die **Platzhalter** werden mit **eindeutigen Namen** versehen, die die Art der zu erwartenden Information angeben, z.B. "Name", "Datum" oder "Beschreibung".
>- **Prompt schreiben**: Der Benutzer schreibt einen **Prompt**, der das **LLM** auffordert, die **Vorlage** zu verwenden und die **Platzhalter** mit den entsprechenden Informationen aus dem Kontext zu füllen.
>- **Ausgabe generieren**: Das **LLM** analysiert den Kontext, extrahiert die relevanten Informationen und füllt die **Platzhalter** in der **Vorlage** aus.

>[!example]- Demonstration
>**Rezeptgenerierung mit ChatGPT:**
>1. Öffnen Sie die ChatGPT-Webseite.
>2. Definieren Sie eine **Vorlage** für ein Rezept, z.B.:
>   ```
>   ## {Gericht}
>   
>   **Zutaten:**
>   
>   - {Zutat 1}
>   - {Zutat 2}
>   - ...
>   
>   **Zubereitung:**
>   
>   1. {Schritt 1}
>   2. {Schritt 2}
>   3. ...
>   ```
>3. Schreiben Sie einen **Prompt**, der ChatGPT auffordert, die **Vorlage** zu verwenden und ein Rezept für "Spaghetti Carbonara" zu generieren.
>4. ChatGPT generiert ein Rezept im **gewünschten Format**, indem es die **Platzhalter** mit den entsprechenden Informationen füllt.

>[!tip]- Anwendungen
>- **Rezeptgenerierung**: **LLMs** können **Rezepte** in einem **strukturierten Format** generieren, mit **Zutatenlisten**, **Zubereitungsschritten** und **Nährwertangaben**.
>- **Lebenslauferstellung**: **LLMs** können **Lebensläufe** in einem **professionellen Format** erstellen, mit **Platzhaltern** für **persönliche Daten**, **Berufserfahrung** und **Ausbildung**.
>- **Codegenerierung**: **LLMs** können **Code** in **verschiedenen Programmiersprachen** generieren, indem sie **Vorlagen** für **typische Code-Strukturen** verwenden.
>- **Datenauswertung**: **LLMs** können **strukturierte Daten** aus **Texten** extrahieren und in **Tabellen** oder **Listen** darstellen.

## Übungen 
>[!question] Auftrag:  Eine Vorlage für eine Buchrezension erstellen
>Entwerfen Sie eine Vorlage mit Platzhaltern für eine Buchrezension.
>>[!todo]- Anleitung 
>>1. Überlegen Sie, welche Informationen in einer Buchrezension relevant sind, z.B. **Titel**, **Autor**, **Genre**, **Handlungszusammenfassung**, **Bewertung**.
>>2. Erstellen Sie eine **Vorlage** mit **Platzhaltern** für diese Informationen.
>>3. Testen Sie Ihre Vorlage, indem Sie ChatGPT bitten, eine Buchrezension zu einem Buch Ihrer Wahl zu generieren.
>
>>[!example]- Beispiel
>>```
>>## Buchrezension: {Titel} von {Autor}
>>
>>**Genre:** {Genre}
>>
>>**Handlung:** {Handlungszusammenfassung}
>>
>>**Bewertung:** {Bewertung} von 5 Sternen
>>
>>**Fazit:** {Persönliche Meinung zum Buch}
>>```

>[!tip]- Weitere Hinweise
>- Verwenden Sie **beschreibende Platzhalternamen**, die die Art der Information klar angeben.
>- Achten Sie auf die **Formatierung** der Vorlage, z.B. mit **Überschriften**, **Listen** oder **Absätzen**.
>- Testen Sie Ihre Vorlage mit **verschiedenen Büchern**, um sicherzustellen, dass sie flexibel einsetzbar ist.
>### Probieren Sie selber
>- Wie könnten Sie das Template-Muster nutzen, um eine Vorlage für einen Projektantrag zu erstellen?
>- Wie könnten Sie das Template-Muster nutzen, um eine Vorlage für einen Newsletter zu erstellen?
>- Wie könnten Sie das Template-Muster nutzen, um eine Vorlage für einen Blogartikel zu erstellen?

> [!question]- Diskussionsfragen
>- In welchen Situationen ist das Template-Muster besonders hilfreich?
>- Welche Grenzen hat das Template-Muster?

---

>[!abstract]- Zusammenfassung
>Das **Gameplay-Muster** und das **Template-Muster** sind zwei **fortgeschrittene Prompting-Techniken**, die uns helfen, **LLMs** effektiver zu nutzen. Das **Gameplay-Muster** ermöglicht es uns, **spielerische Lernumgebungen** zu schaffen, während das **Template-Muster** die **Ausgabe von LLMs** **strukturiert** und in einem **gewünschten Format** präsentiert.
