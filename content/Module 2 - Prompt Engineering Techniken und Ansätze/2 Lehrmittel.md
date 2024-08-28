# Fortgeschrittene Prompt Engineering Techniken: Theoretische Grundlagen
> [!info] Wieso Fortgeschrittene Prompt Engineering Techniken?
> - **Prompt Engineering** ist essenziell, um das volle Potenzial von **grossen Sprachmodellen (LLMs)** auszuschöpfen.
> - **Fortgeschrittene Techniken** ermöglichen es uns, **LLMs** für komplexere Aufgaben und kreativere Anwendungen einzusetzen.
> - Durch **effektives Prompt Engineering** können wir die **Qualität und Relevanz** der Antworten von **LLMs** verbessern.
> - **Fortgeschrittene Prompt Engineering Techniken** helfen uns, **LLMs** besser zu verstehen und ihre **Grenzen** zu erkennen.
> - **Prompt Engineering** ist ein sich ständig weiterentwickelndes Feld, das uns neue Möglichkeiten eröffnet, mit **künstlicher Intelligenz** zu interagieren.

---

## Inhalte
- Prompt Engineering Techniken für Text-zu-Text
- Interview Pattern Approach
- Chain-of-Thought und Tree-of-Thought

---
### Prompt Engineering Techniken für Text-zu-Text
>[!info]- Grundlagen
>- **Prompt Engineering für Text-zu-Text** fokussiert auf die Erstellung von **Prompts**, die **LLMs** dazu anleiten, **spezifische Text-basierte Ausgaben** zu generieren.
>- **Text-zu-Text Prompts** können für eine Vielzahl von Aufgaben verwendet werden, wie z.B. **Textzusammenfassung**, **Übersetzung**, **Kreatives Schreiben** und **Codegenerierung**.
>- Die **Qualität** des **Prompts** hat einen direkten Einfluss auf die **Qualität** der **Ausgabe** des **LLMs**.
>- **Klare**, **prägnante** und **kontextreiche Prompts** führen zu besseren Ergebnissen.

>[!abstract]- Funktionsweise
>- **Aufgabenspezifikation**: Der Prompt muss die **gewünschte Aufgabe** klar und deutlich definieren.
>- **Kontext**: Der Prompt sollte dem **LLM** genügend **Informationen** liefern, um die Anfrage zu verstehen und eine relevante Antwort zu generieren.
>- **Beispiele**: In einigen Fällen kann es hilfreich sein, dem **LLM** **Beispiele** für die gewünschte Ausgabe zu geben.
>- **Iteration**: **Prompt Engineering** ist oft ein **iterativer Prozess**, bei dem der Benutzer den Prompt basierend auf den Antworten des **LLMs** verfeinert.

>[!example]- Demonstration
> **Prompt für Textzusammenfassung:**
> 1. **Text**: "Die Schweiz ist ein Binnenstaat in Mitteleuropa. Sie grenzt an Deutschland, Frankreich, Italien, Österreich und Liechtenstein. Die Schweiz ist bekannt für ihre Berge, Schokolade und Uhren."
> 2. **Prompt**: "Fasse den folgenden Text in einem Satz zusammen."
> 3. **Mögliche Ausgabe des LLMs**: "Die Schweiz ist ein Binnenstaat in Mitteleuropa, der für seine Berge, Schokolade und Uhren bekannt ist."

>[!tip]- Anwendungen
>- **Automatische Textgenerierung**: Erstellen Sie **Produktbeschreibungen**, **Social-Media-Posts** oder **Nachrichtenartikel** mit **LLMs**.
>- **Übersetzung**: Übersetzen Sie Texte in verschiedene Sprachen mit **LLMs**.
>- **Kreatives Schreiben**: Nutzen Sie **LLMs** als **Ideengeber** oder **Co-Autoren** für Geschichten, Gedichte oder Drehbücher.
>- **Codegenerierung**: Generieren Sie **Code** in verschiedenen Programmiersprachen mit **LLMs**.

## Übungen 
>[!question] Auftrag:  Einen Prompt für eine Produktbeschreibung erstellen
> Sie arbeiten für ein Unternehmen, das Schweizer Schokolade verkauft. Formulieren Sie einen Prompt, der ein LLM dazu anleitet, eine ansprechende Produktbeschreibung für eine neue Schokoladensorte zu generieren.
>>[!todo]- Anleitung 
>>1. Überlegen Sie sich die **wichtigsten Eigenschaften** der neuen Schokoladensorte (z.B. Geschmack, Zutaten, Herkunft).
>>2. Formulieren Sie einen **Prompt**, der das **LLM** dazu auffordert, eine **Produktbeschreibung** zu erstellen, die diese Eigenschaften hervorhebt.
>>3. Achten Sie darauf, dass der **Prompt** klar, prägnant und informativ ist.
>
>>[!example]- Beispiel
>>"Erstelle eine Produktbeschreibung für eine neue Schweizer Schokolade mit Haselnüssen und einem Hauch von Meersalz. Betone den intensiven Schokoladengeschmack und die knackigen Haselnüsse. Erwähne auch, dass die Schokolade aus nachhaltig angebauten Kakaobohnen hergestellt wird."

>[!tip]- Weitere Hinweise
>- Verwenden Sie **ansprechende Adjektive**, um den Geschmack und das Aussehen der Schokolade zu beschreiben.
>- Heben Sie die **einzigartigen Merkmale** der Schokolade hervor.
>- Sprechen Sie die **Zielgruppe** direkt an.
>### Probieren Sie selber
>- Wie könnten Sie einen Prompt erstellen, um ein LLM dazu zu bringen, einen Werbetext für ein neues Schweizer Taschenmesser zu generieren?
>- Wie könnten Sie einen Prompt erstellen, um ein LLM dazu zu bringen, eine Zusammenfassung eines wissenschaftlichen Artikels über künstliche Intelligenz zu schreiben?
>- Wie könnten Sie einen Prompt erstellen, um ein LLM dazu zu bringen, ein Gedicht über die Schönheit der Schweizer Alpen zu verfassen?

> [!question]- Diskussionsfragen
>- Welche Herausforderungen sehen Sie bei der Erstellung von effektiven Prompts für Text-zu-Text-Aufgaben?
>- Wie können wir sicherstellen, dass die von LLMs generierten Texte qualitativ hochwertig und relevant sind?

---
### Interview Pattern Approach
>[!info]- Grundlagen
>- Der **Interview Pattern Approach** ist eine **Prompt Engineering Technik**, die die Interaktion mit einem **LLM** wie ein **Interview** gestaltet.
>- Anstatt eine einzelne Frage zu stellen, werden **mehrere, aufeinander aufbauende Fragen** gestellt, um **detailliertere** und **spezifischere Antworten** zu erhalten.
>- Der **Interview Pattern Approach** ermöglicht es, den **Kontext** der Anfrage schrittweise zu erweitern und das **LLM** zu präziseren Antworten zu führen.

>[!abstract]- Funktionsweise
>- **Rollendefinition**: Der Prompt definiert eine **Rolle** für das **LLM**, z.B. "Reiseexperte", "Journalist" oder "Koch".
>- **Offene Fragen**: Der Prompt beginnt mit **offenen Fragen**, die das **LLM** zu **detaillierten Antworten** anregen.
>- **Folgefragen**: Basierend auf den Antworten des **LLMs** werden **Folgefragen** gestellt, um den **Kontext** zu verfeinern und die **gewünschten Informationen** zu erhalten.
>- **Kontextbildung**: Die Antworten des **LLMs** werden genutzt, um den **Kontext** für nachfolgende Fragen zu schaffen.

>[!example]- Demonstration
> **Prompt für Reiseplanung:**
> 1. **Rolle**: "Agieren Sie als Reiseexperte für die Schweiz."
> 2. **Erste Frage**: "Welche Region in der Schweiz würden Sie für einen einwöchigen Urlaub im Sommer empfehlen?"
> 3. **Folgefragen**: (basierend auf der Antwort des LLMs) "Welche Sehenswürdigkeiten gibt es in dieser Region?", "Welche Outdoor-Aktivitäten sind dort möglich?", "Welche Unterkünfte empfehlen Sie?"

>[!tip]- Anwendungen
>- **Informationsbeschaffung**:  Nutzen Sie den **Interview Pattern Approach**, um **detaillierte Informationen** zu einem bestimmten Thema zu erhalten.
>- **Planung und Organisation**: Erstellen Sie **Reisepläne**, **Projektpläne** oder **Veranstaltungspläne** mit Hilfe von **LLMs**.
>- **Kreatives Schreiben**: Entwickeln Sie **Geschichten**, **Dialoge** oder **Charaktere** durch ein **"Interview"** mit dem **LLM**.

## Übungen 
>[!question] Auftrag:  Ein Interview mit einem virtuellen Koch führen
> Stellen Sie sich vor, Sie möchten ein LLM als virtuellen Koch nutzen, um ein Rezept für ein traditionelles Schweizer Gericht zu erhalten. Formulieren Sie eine Reihe von Fragen, die Sie dem LLM im Rahmen eines "Interviews" stellen würden.
>>[!todo]- Anleitung 
>>1. Definieren Sie die **Rolle** des **LLMs** als "Koch für Schweizer Küche".
>>2. Beginnen Sie mit einer **offenen Frage**, z.B. "Welches traditionelle Schweizer Gericht würden Sie empfehlen?"
>>3. Stellen Sie **Folgefragen**, um **Details zum Rezept** zu erhalten, z.B. "Welche Zutaten benötige ich?", "Wie bereite ich das Gericht zu?", "Gibt es besondere Tipps für die Zubereitung?"
>
>>[!example]- Beispiel
>>1. **Rolle**: "Agieren Sie als Koch für Schweizer Küche."
>>2. **Erste Frage**: "Welches traditionelle Schweizer Gericht würden Sie für ein Abendessen mit Freunden empfehlen?"
>>3. **Folgefragen**: (basierend auf der Antwort des LLMs) "Welche Zutaten benötige ich für dieses Gericht?", "Können Sie mir die Zubereitung Schritt für Schritt erklären?", "Gibt es Variationen dieses Gerichts?"

>[!tip]- Weitere Hinweise
>- Stellen Sie **klare und prägnante Fragen**.
>- Achten Sie darauf, dass Ihre Fragen aufeinander aufbauen und den **Kontext** der Anfrage erweitern.
>- Notieren Sie die Antworten des **LLMs**, um den Überblick zu behalten.
>### Probieren Sie selber
>- Wie könnten Sie den Interview Pattern Approach nutzen, um ein LLM bei der Planung eines Geburtstagsgeschenks zu unterstützen?
>- Wie könnten Sie den Interview Pattern Approach nutzen, um ein LLM dazu zu bringen, eine Geschichte über ein historisches Ereignis zu erzählen?
>- Wie könnten Sie den Interview Pattern Approach nutzen, um ein LLM bei der Erstellung eines Businessplans zu unterstützen?

> [!question]- Diskussionsfragen
>- Welche Vorteile bietet der Interview Pattern Approach im Vergleich zu herkömmlichen Prompting-Methoden?
>- In welchen Situationen ist der Interview Pattern Approach besonders nützlich?

---
### Chain-of-Thought und Tree-of-Thought
>[!info]- Grundlagen
>- **Chain-of-Thought (CoT)** und **Tree-of-Thought (ToT)** sind **fortgeschrittene Prompt Engineering Techniken**, die **LLMs** bei der Lösung von **komplexen Problemen** unterstützen.
>- **CoT** leitet das **LLM** durch einen **schrittweisen Denkprozess**, indem es ein **Beispiel für eine logische Argumentation** vorgibt.
>- **ToT** erweitert **CoT**, indem es das **LLM** dazu anregt, **verschiedene Lösungswege** zu erkunden, ähnlich einem **Entscheidungsbaum**.

>[!abstract]- Funktionsweise
>- **Chain-of-Thought:**
>    - Der Prompt enthält eine **Frage** und eine **detaillierte Antwort**, die den **Denkprozess** Schritt für Schritt darstellt.
>    - Das **LLM** wird aufgefordert, eine neue Frage mit dem gleichen **logischen Ansatz** zu beantworten.
>- **Tree-of-Thought:**
>    - Der Prompt fordert das **LLM** auf, **verschiedene Möglichkeiten** zu betrachten und zu bewerten, bevor es eine Entscheidung trifft.
>    - Das **LLM** erstellt einen **"Gedankenbaum"**, der verschiedene **Lösungswege** darstellt.

>[!example]- Demonstration
> **Chain-of-Thought Prompt:**
> 1. **Frage**: "Hans hat 5 Äpfel. Er kauft 3 weitere Äpfel. Wie viele Äpfel hat Hans jetzt?"
> 2. **Antwort**: "Hans hatte 5 Äpfel. Er kaufte 3 weitere Äpfel dazu. Also hat er jetzt 5 + 3 = 8 Äpfel."
> 3. **Neue Frage**: "Maria hat 7 Birnen. Sie isst 2 Birnen. Wie viele Birnen hat Maria jetzt?"

>[!tip]- Anwendungen
>- **Problemlösung**: Nutzen Sie **CoT** und **ToT**, um **LLMs** bei der Lösung von **mathematischen Aufgaben**, **logischen Rätseln** oder **strategischen Entscheidungen** zu unterstützen.
>- **Planung**: Erstellen Sie **komplexe Pläne** oder **Strategien** mit Hilfe von **LLMs**, indem Sie den **Denkprozess** in **Schritte** zerlegen.
>- **Forschung**: Nutzen Sie **CoT** und **ToT**, um **LLMs** bei der **Analyse von Daten** und der **Generierung von Hypothesen** zu unterstützen.

## Übungen 
>[!question] Auftrag:  Ein LLM bei der Routenplanung unterstützen
> Sie planen eine Reise von Zürich nach Genf. Verwenden Sie Chain-of-Thought, um ein LLM bei der Auswahl der besten Route zu unterstützen.
>>[!todo]- Anleitung 
>>1. Formulieren Sie eine **Frage**, die die **Routenplanung** beschreibt, z.B. "Wie komme ich am schnellsten von Zürich nach Genf?"
>>2. Geben Sie ein **Beispiel** für eine **logische Argumentation**, die verschiedene **Faktoren** berücksichtigt, z.B. "Die schnellste Route ist nicht immer die kürzeste. Man muss auch Staus, Baustellen und die Art des Verkehrsmittels berücksichtigen."
>>3. Fordern Sie das **LLM** auf, die **beste Route** unter Berücksichtigung dieser **Faktoren** zu ermitteln.
>
>>[!example]- Beispiel
>>1. **Frage**: "Wie komme ich am bequemsten von Zürich nach Genf?"
>>2. **Antwort**: "Die bequemste Route ist nicht immer die schnellste. Man sollte die Anzahl der Umstiege, die Reisezeit und den Komfort des Verkehrsmittels berücksichtigen. Zum Beispiel könnte ein Direktflug zwar schneller sein, aber eine Zugfahrt mit Panoramablick könnte bequemer sein."
>>3. **Neue Frage**: "Welche Route von Zürich nach Genf bietet das beste Preis-Leistungs-Verhältnis?"

>[!tip]- Weitere Hinweise
>- Gliedern Sie den **Denkprozess** in **klare Schritte**.
>- Verwenden Sie **konkrete Beispiele**, um dem **LLM** die **gewünschte Argumentationsweise** zu demonstrieren.
>- Fordern Sie das **LLM** auf, seine **Entscheidung** zu begründen.
>### Probieren Sie selber
>- Wie könnten Sie Chain-of-Thought nutzen, um ein LLM bei der Lösung eines mathematischen Problems zu unterstützen?
>- Wie könnten Sie Tree-of-Thought nutzen, um ein LLM bei der Entwicklung einer Marketingstrategie zu unterstützen?
>- Wie könnten Sie Chain-of-Thought und Tree-of-Thought kombinieren, um ein LLM bei der Lösung eines komplexen Problems zu unterstützen?

> [!question]- Diskussionsfragen
>- Wie können Chain-of-Thought und Tree-of-Thought dazu beitragen, die Argumentationsfähigkeiten von LLMs zu verbessern?
>- Welche Arten von Problemen eignen sich besonders gut für diese Ansätze?

---

>[!abstract]- Zusammenfassung
> **Fortgeschrittene Prompt Engineering Techniken** ermöglichen es uns, das volle Potenzial von **LLMs** auszuschöpfen. Durch die Anwendung von Techniken wie **Text-zu-Text Prompting**, dem **Interview Pattern Approach**, **Chain-of-Thought** und **Tree-of-Thought** können wir **LLMs** dazu bringen, **komplexere Aufgaben** zu lösen, **kreativere Ergebnisse** zu liefern und **menschenähnlichere Interaktionen** zu ermöglichen. 
