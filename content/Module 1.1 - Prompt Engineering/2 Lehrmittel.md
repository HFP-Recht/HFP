# Prompt Engineering: Theoretische Grundlagen
> [!info] Wieso Prompt Engineering?
>- **Prompt Engineering** ist essenziell, um das volle Potenzial von **generativen KI-Modellen** wie ChatGPT auszuschöpfen.
>- Durch **gezielte Prompts** können wir die **KI** steuern und **gewünschte Ergebnisse** erzielen.
>- **Prompt Engineering** ist eine **Schlüsselkompetenz** im Umgang mit **KI** und wird in Zukunft immer wichtiger werden.
>- **Effektive Prompts** ermöglichen es uns, **KI** für eine Vielzahl von **Anwendungen** einzusetzen, z.B. in der **Kommunikation**, im **Marketing** oder in der **Softwareentwicklung**.
>- **Prompt Engineering** ist ein **kreativer Prozess**, der **Experimentierfreude** und **sprachliches Geschick** erfordert.

---

## Inhalte
- [[#Was ist ein Prompt?]]
- [[#Was ist Prompt Engineering?]]
- [[#Best Practices für die Prompt-Erstellung]]
- [[#Gängige Prompt Engineering Tools]]

---
### Was ist ein Prompt?
>[!info]- Grundlagen
>- Ein **Prompt** ist eine **Eingabe**, die an ein **generatives KI-Modell** gerichtet wird.
>- **Prompts** können in Form von **Text**, **Code** oder **anderen Daten** vorliegen.
>- **Prompts** dienen dazu, dem **KI-Modell** **Anweisungen** zu geben oder **gewünschte Ausgaben** zu spezifizieren.
>- **Prompts** können **einfache Fragen** oder **komplexe Anweisungen** sein.
>- Die **Qualität** eines **Prompts** beeinflusst massgeblich die **Qualität** der **KI-generierten Ausgabe**.

>[!abstract]- Funktionsweise
>- **Eingabe**: Der Benutzer gibt einen **Prompt** in das **KI-Modell** ein.
>- **Verarbeitung**: Das **KI-Modell** verarbeitet den **Prompt** und analysiert dessen **Inhalt** und **Struktur**.
>- **Generierung**: Basierend auf dem **Prompt** generiert das **KI-Modell** eine **Ausgabe**, z.B. einen Text, ein Bild oder einen Code.
>- **Ausgabe**: Das **KI-Modell** gibt die generierte **Ausgabe** an den Benutzer zurück.

>[!example]- Demonstration
> **Prompt für ChatGPT:**
> 1. **Prompt:** "Schreibe ein kurzes Gedicht über die Schönheit der Natur."
> 2. **Ausgabe:** (ChatGPT generiert ein Gedicht über die Schönheit der Natur)

>[!tip]- Anwendungen
>- **Textgenerierung**: **Prompts** werden verwendet, um **KI-Modelle** zur Generierung von Texten wie Geschichten, Artikeln oder Gedichten anzuleiten.
>- **Codegenerierung**: **Prompts** können verwendet werden, um **KI-Modelle** zur Generierung von Code in verschiedenen Programmiersprachen zu instruieren.
>- **Bildgenerierung**: **Prompts** werden verwendet, um **KI-Modelle** zur Generierung von Bildern basierend auf Textbeschreibungen zu steuern.
>- **Übersetzung**: **Prompts** können verwendet werden, um **KI-Modelle** zur Übersetzung von Texten in verschiedene Sprachen zu veranlassen.

## Übungen 
>[!question] Auftrag:  Kreative Prompts für ChatGPT
>Formulieren Sie drei kreative Prompts für ChatGPT, die das Modell zu unterschiedlichen Arten von Ausgaben anregen.
>>[!todo]- Anleitung 
>>1. Überlegen Sie sich drei verschiedene **Themen** oder **Aufgaben**, die Sie ChatGPT stellen möchten.
>>2. Formulieren Sie für jedes Thema einen **Prompt**, der **klar**, **präzise** und **kreativ** ist.
>>3. Achten Sie darauf, dass Ihre **Prompts** ChatGPT zu **unterschiedlichen Arten von Ausgaben** anregen, z.B. Text, Code oder eine Liste.
>
>>[!example]- Beispiel
>>1. **Prompt:** "Schreibe eine Kurzgeschichte im Stil von Franz Kafka über einen Mann, der sich in einen Käfer verwandelt."
>>2. **Prompt:** "Generiere Python-Code für ein Programm, das die Fibonacci-Sequenz berechnet."
>>3. **Prompt:** "Erstelle eine Liste mit zehn Tipps für eine nachhaltige Lebensweise."

>[!tip]- Weitere Hinweise
>- Verwenden Sie **anschauliche Sprache** und **detaillierte Beschreibungen**, um ChatGPT zu inspirieren.
>- Experimentieren Sie mit **verschiedenen Prompt-Formulierungen**, um zu sehen, wie sich die Ausgabe von ChatGPT verändert.
>### Probieren Sie selber
>- Wie könnten Sie Prompts verwenden, um ChatGPT dazu zu bringen, einen Song zu schreiben?
>- Wie könnten Sie Prompts verwenden, um ChatGPT dazu zu bringen, ein Rezept zu generieren?
>- Wie könnten Sie Prompts verwenden, um ChatGPT dazu zu bringen, einen Reiseplan zu erstellen?

> [!question]- Diskussionsfragen
>- Welche Rolle spielt die **Kreativität** beim Formulieren von Prompts?
>- Wie können wir sicherstellen, dass unsere **Prompts** ethisch vertretbar sind?

---

### Was ist Prompt Engineering?
>[!info]- Grundlagen
>- **Prompt Engineering** ist der Prozess, **effektive Prompts** für **generative KI-Modelle** zu entwickeln.
>- **Prompt Engineering** zielt darauf ab, die **Qualität** und **Relevanz** der **KI-generierten Ausgaben** zu verbessern.
>- **Prompt Engineering** ist ein **iterativer Prozess**, der **Experimentieren**, **Analysieren** und **Optimieren** umfasst.
>- **Prompt Engineering** erfordert ein **Verständnis** für die **Funktionsweise** von **KI-Modellen** und die **Prinzipien** der **Sprachverarbeitung**.

>[!abstract]- Funktionsweise
>- **Zieldefinition**: Der erste Schritt im **Prompt Engineering** ist die klare Definition des **Ziels**, das mit dem **Prompt** erreicht werden soll.
>- **Prompt-Erstellung**: Basierend auf dem Ziel wird ein **initialer Prompt** formuliert.
>- **Testen und Evaluieren**: Der **Prompt** wird mit dem **KI-Modell** getestet und die generierte **Ausgabe** wird evaluiert.
>- **Prompt-Verfeinerung**: Der **Prompt** wird basierend auf der **Evaluierung** der **Ausgabe** iterativ verfeinert.
>- **Iteration**: Die Schritte **Testen**, **Evaluieren** und **Verfeinern** werden wiederholt, bis das gewünschte Ergebnis erzielt wird.

>[!example]- Demonstration
> **Prompt Engineering für die Zusammenfassung eines Textes:**
> 1. **Ziel:** Eine kurze und prägnante Zusammenfassung eines wissenschaftlichen Artikels generieren.
> 2. **Initialer Prompt:** "Fasse diesen Artikel zusammen."
> 3. **Testen und Evaluieren:** Die generierte Zusammenfassung ist zu lang und enthält irrelevante Details.
> 4. **Prompt-Verfeinerung:** "Fasse diesen Artikel in maximal 200 Wörtern zusammen und konzentriere dich auf die wichtigsten Ergebnisse."
> 5. **Iteration:** Der Prompt wird weiter verfeinert, bis eine zufriedenstellende Zusammenfassung generiert wird.

>[!tip]- Anwendungen
>- **Verbesserung der Textqualität**: **Prompt Engineering** kann verwendet werden, um die **Grammatik**, **Stil** und **Kohärenz** von KI-generierten Texten zu verbessern.
>- **Steuerung der KI-Ausgabe**: **Prompt Engineering** ermöglicht es uns, die **Art** und **Form** der **KI-generierten Ausgabe** zu beeinflussen, z.B. die Länge eines Textes oder die Perspektive einer Geschichte.
>- **Optimierung für spezifische Aufgaben**: **Prompt Engineering** kann verwendet werden, um **KI-Modelle** für **spezifische Aufgaben** zu optimieren, z.B. für die Übersetzung von Fachtexten oder die Generierung von kreativen Inhalten.

## Übungen 
>[!question] Auftrag:  Prompt Engineering für eine Reiseplanung
>Sie planen eine Reise nach Rom und möchten ChatGPT nutzen, um einen Reiseplan zu erstellen. Wenden Sie die Prinzipien des Prompt Engineerings an, um einen effektiven Prompt zu formulieren.
>>[!todo]- Anleitung 
>>1. Definieren Sie Ihre **Reiseziele** und **Interessen** (z.B. Sehenswürdigkeiten, Museen, Restaurants).
>>2. Formulieren Sie einen **initialen Prompt**, der ChatGPT instruiert, einen Reiseplan für Rom zu erstellen.
>>3. **Testen** Sie den Prompt mit ChatGPT und **evaluieren** Sie die generierte Ausgabe.
>>4. **Verfeinern** Sie den Prompt basierend auf Ihrer Evaluierung, um spezifischere und relevantere Ergebnisse zu erhalten.
>>5. **Wiederholen** Sie die Schritte 3 und 4, bis Sie mit dem Reiseplan zufrieden sind.
>
>>[!example]- Beispiel
>>**Initialer Prompt:** "Erstelle einen Reiseplan für eine einwöchige Reise nach Rom."
>>**Verfeinerter Prompt:** "Erstelle einen Reiseplan für eine einwöchige Reise nach Rom, der sich auf antike Sehenswürdigkeiten, italienische Küche und Kunstmuseen konzentriert. Ich interessiere mich besonders für das Kolosseum, das Forum Romanum und die Vatikanischen Museen. Ich möchte auch gerne authentische römische Pasta und Pizza probieren."

>[!tip]- Weitere Hinweise
>- Geben Sie ChatGPT so viele **Details** wie möglich, um den Reiseplan an Ihre Bedürfnisse anzupassen.
>- Verwenden Sie **Keywords**, um die wichtigsten Aspekte Ihrer Reise hervorzuheben.
>- Seien Sie **präzise** in Ihren Anweisungen, z.B. geben Sie die **gewünschte Reisedauer** und die **Art der Aktivitäten** an.
>### Probieren Sie selber
>- Wie könnten Sie Prompt Engineering nutzen, um ChatGPT dazu zu bringen, einen Businessplan zu erstellen?
>- Wie könnten Sie Prompt Engineering nutzen, um ChatGPT dazu zu bringen, eine wissenschaftliche Arbeit zu verfassen?
>- Wie könnten Sie Prompt Engineering nutzen, um ChatGPT dazu zu bringen, einen Marketing-Slogan zu entwickeln?

> [!question]- Diskussionsfragen
>- Warum ist **Prompt Engineering** ein **iterativer Prozess**?
>- Welche **Herausforderungen** sehen Sie beim **Prompt Engineering**?

---

### Best Practices für die Prompt-Erstellung
>[!info]- Grundlagen
>- **Best Practices** für die **Prompt-Erstellung** helfen uns, **effektive Prompts** zu formulieren, die zu **hochwertigen KI-generierten Ausgaben** führen.
>- **Klarheit**, **Kontext**, **Präzision** und **Rollenspiel** sind wichtige Dimensionen bei der **Prompt-Erstellung**.
>- **Best Practices** sollten **an die jeweilige Aufgabe** und das **verwendete KI-Modell** angepasst werden.

>[!abstract]- Funktionsweise
>- **Klarheit**: Verwenden Sie **klare** und **präzise Sprache**, um Missverständnisse zu vermeiden.
>- **Kontext**: Geben Sie dem **KI-Modell** genügend **Kontextinformationen**, um die Anfrage zu verstehen.
>- **Präzision**: Seien Sie **spezifisch** in Ihren Anweisungen und geben Sie **klare Vorgaben** für die gewünschte Ausgabe.
>- **Rollenspiel**: Weisen Sie dem **KI-Modell** eine **Rolle** zu, um Antworten aus einer bestimmten **Perspektive** zu erhalten.

>[!example]- Demonstration
> **Best Practices in der Praxis:**
> 1. **Unklarer Prompt:** "Schreibe etwas über Hunde."
> 2. **Klarer Prompt:** "Schreibe einen informativen Artikel über die Geschichte der Hundezucht."
> 3. **Prompt mit Kontext:** "Du bist ein Reiseblogger. Schreibe einen Blogbeitrag über die besten Reiseziele für Hundebesitzer."
> 4. **Präziser Prompt:** "Schreibe eine Liste mit fünf Tipps für die Erziehung eines Welpen."
> 5. **Prompt mit Rollenspiel:** "Agieren Sie als ein Tierarzt und geben Sie mir Tipps zur Pflege eines älteren Hundes."

>[!tip]- Anwendungen
>- **Verbesserung der Kommunikation mit KI**: **Best Practices** helfen uns, unsere **Anforderungen** an **KI-Modelle** klar und deutlich zu kommunizieren.
>- **Steigerung der Effizienz**: **Gut formulierte Prompts** führen zu **schnelleren** und **präziseren Ergebnissen**.
>- **Reduzierung von Fehlern**: **Klare Anweisungen** minimieren das Risiko von **Missverständnissen** und **Fehlinterpretationen**.

## Übungen 
>[!question] Auftrag:  Optimierung von Prompts
>Sie haben folgende Prompts für ChatGPT formuliert. Analysieren Sie die Prompts anhand der **Best Practices** und **verbessern** Sie sie, um **klarere**, **präzisere** und **effektivere** Anweisungen zu geben.
>1. "Schreibe einen Text."
>2. "Was ist der Sinn des Lebens?"
>3. "Gib mir Informationen."
>>[!todo]- Anleitung 
>>1. **Analysieren** Sie jeden Prompt hinsichtlich **Klarheit**, **Kontext**, **Präzision** und **Rollenspiel**.
>>2. **Identifizieren** Sie **Schwächen** in den Prompts.
>>3. **Formulieren** Sie die Prompts **neu**, um die **Best Practices** zu berücksichtigen.
>
>>[!example]- Beispiel
>>1. **Original:** "Schreibe einen Text."
>>   **Verbessert:** "Schreibe einen Essay über die Vor- und Nachteile von Social Media."
>>2. **Original:** "Was ist der Sinn des Lebens?"
>>   **Verbessert:** "Agieren Sie als ein Philosoph und diskutieren Sie verschiedene Perspektiven auf den Sinn des Lebens."
>>3. **Original:** "Gib mir Informationen."
>>   **Verbessert:** "Gib mir Informationen über die Geschichte der Schweiz im 20. Jahrhundert."

>[!tip]- Weitere Hinweise
>- **Versetzen** Sie sich in die **Lage** von ChatGPT und überlegen Sie, welche **Informationen** das Modell benötigt, um Ihre Anfrage zu verstehen.
>- **Verwenden** Sie **Beispiele**, um die gewünschte Art der Ausgabe zu verdeutlichen.
>- **Testen** Sie Ihre **verbesserten Prompts** mit ChatGPT und beobachten Sie, wie sich die **Ausgabe** verändert.
>### Probieren Sie selber
>- Wie könnten Sie die **Best Practices** anwenden, um einen Prompt für die Generierung eines Marketing-Slogans zu optimieren?
>- Wie könnten Sie die **Best Practices** anwenden, um einen Prompt für die Übersetzung eines technischen Dokuments zu verbessern?
>- Wie könnten Sie die **Best Practices** anwenden, um einen Prompt für die Erstellung eines Businessplans zu präzisieren?

> [!question]- Diskussionsfragen
>- Welche der **Best Practices** halten Sie für am wichtigsten?
>- Wie können wir die **Best Practices** anwenden, um **ethische** und **verantwortungsvolle** Prompts zu erstellen?

---

### Gängige Prompt Engineering Tools
>[!info]- Grundlagen
>- **Prompt Engineering Tools** sind **Softwareanwendungen**, die den Prozess des **Prompt Engineerings** unterstützen.
>- **Prompt Engineering Tools** bieten **Funktionen**, die das **Formulieren**, **Testen** und **Optimieren** von **Prompts** erleichtern.
>- **Prompt Engineering Tools** können sowohl von **Anfängern** als auch von **erfahrenen Prompt Engineers** genutzt werden.

>[!abstract]- Funktionsweise
>- **Prompt-Vorschläge**: Einige Tools bieten **Vorschläge** für **Prompts** basierend auf **Keywords** oder **Beispielen**.
>- **Prompt-Bibliotheken**: Tools können **Bibliotheken** mit **vordefinierten Prompts** für verschiedene Aufgaben und KI-Modelle enthalten.
>- **Prompt-Testing**: Tools ermöglichen es, **Prompts** mit verschiedenen **KI-Modellen** zu **testen** und die **Ergebnisse** zu **vergleichen**.
>- **Prompt-Optimierung**: Tools können **Funktionen** zur **automatischen Optimierung** von **Prompts** bieten, z.B. durch **Parametertuning** oder **maschinelles Lernen**.
>- **Prompt-Management**: Tools können helfen, **Prompts** zu **organisieren**, zu **versionieren** und mit anderen zu **teilen**.

>[!example]- Demonstration
> **PromptPerfect**:
> 1. **Modell auswählen**: Wählen Sie das **KI-Modell**, für das Sie den Prompt optimieren möchten (z.B. ChatGPT).
> 2. **Prompt eingeben**: Geben Sie Ihren **Prompt** in das Tool ein.
> 3. **Optimieren**: Klicken Sie auf die Schaltfläche "Optimieren", um den Prompt zu verbessern.
> 4. **Ergebnis anzeigen**: Das Tool zeigt den **optimierten Prompt** an.

>[!tip]- Anwendungen
>- **Effizienzsteigerung**: **Prompt Engineering Tools** können den Prozess des **Prompt Engineerings** beschleunigen und **zeitaufwändige Aufgaben automatisieren**.
>- **Verbesserung der Prompt-Qualität**: Tools können helfen, **klarere**, **präzisere** und **effektivere** Prompts zu erstellen.
>- **Vereinfachung der Zusammenarbeit**: Tools ermöglichen es, **Prompts** mit anderen zu **teilen** und gemeinsam an **Prompt-Engineering-Projekten** zu arbeiten.

## Übungen 
>[!question] Auftrag:  Recherche zu Prompt Engineering Tools
>Recherchieren Sie drei verschiedene **Prompt Engineering Tools** und stellen Sie deren **Funktionen** und **Vorteile** vor.
>>[!todo]- Anleitung 
>>1. **Suchen** Sie im Internet nach **Prompt Engineering Tools**.
>>2. **Wählen** Sie **drei Tools** aus, die Sie interessant finden.
>>3. **Recherchieren** Sie die **Funktionen** und **Vorteile** der ausgewählten Tools.
>>4. **Erstellen** Sie eine **Präsentation**, in der Sie die **Tools** vorstellen.
>
>>[!example]- Beispiel
>>1. **Tool:** PromptPerfect
>>   **Funktionen:** Prompt-Optimierung, Modell-spezifische Strategien, Add-ons, Autocomplete, Streamline-Modus.
>>   **Vorteile:** Verbessert die Prompt-Qualität, spart Zeit, einfach zu bedienen.
>>2. **Tool:** Spellbook
>>   **Funktionen:** IDE für LLM-Anwendungen, Prompt-Editor, Templates, vordefinierte Prompts.
>>   **Vorteile:** Ermöglicht die Entwicklung von LLM-Anwendungen, bietet eine benutzerfreundliche Oberfläche, unterstützt die Zusammenarbeit.
>>3. **Tool:** Dust
>>   **Funktionen:** Web-UI für Prompt-Chaining, Versionsverwaltung, benutzerdefinierte Programmiersprache, API-Integration.
>>   **Vorteile:** Ermöglicht komplexe Prompt-Workflows, unterstützt die Zusammenarbeit, bietet Flexibilität.

>[!tip]- Weitere Hinweise
>- **Konzentrieren** Sie sich auf Tools, die für **Anfänger** geeignet sind.
>- **Verwenden** Sie **Screenshots** und **Demos**, um die **Tools** zu veranschaulichen.
>- **Vergleichen** Sie die **Tools** anhand ihrer **Funktionen**, **Vorteile** und **Nachteile**.
>### Probieren Sie selber
>- **Testen** Sie eines der vorgestellten **Prompt Engineering Tools** und berichten Sie von Ihren Erfahrungen.
>- **Entwickeln** Sie einen **eigenen Prompt** mit Hilfe eines **Prompt Engineering Tools**.
>- **Vergleichen** Sie die **Ergebnisse** von **Prompts**, die **manuell** erstellt wurden, mit **Prompts**, die mit Hilfe eines **Tools** optimiert wurden.

> [!question]- Diskussionsfragen
>- Welche **Vorteile** bieten **Prompt Engineering Tools** gegenüber der manuellen Erstellung von Prompts?
>- Welche **Herausforderungen** sehen Sie beim Einsatz von **Prompt Engineering Tools**?

---

>[!abstract]- Zusammenfassung
> **Prompt Engineering** ist eine **Schlüsselkompetenz** im Umgang mit **generativen KI-Modellen**. Durch die Anwendung von **Best Practices** und die Nutzung von **Prompt Engineering Tools** können wir **effektive Prompts** erstellen, die zu **hochwertigen KI-generierten Ausgaben** führen. **Prompt Engineering** ist ein **kreativer** und **iterativer Prozess**, der **Experimentierfreude** und **sprachliches Geschick** erfordert. 
