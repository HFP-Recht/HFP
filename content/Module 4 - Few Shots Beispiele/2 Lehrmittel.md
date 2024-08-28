# Einführung in Few-Shot Prompting: Theoretische Grundlagen

> [!info] Wieso Few-Shot Prompting?
> - **Few-Shot Prompting** ermöglicht es uns, **LLMs** (Large Language Models) für **spezifische Aufgaben** zu **trainieren**, ohne dass wir **Programmierkenntnisse** benötigen.
> - **Few-Shot Prompting** ist eine **effiziente Methode**, um **LLMs** an **neue Aufgaben** anzupassen, da wir nur **wenige Beispiele** benötigen.
> - **Few-Shot Prompting** ermöglicht es uns, **komplexe Aufgaben** in **einfache Schritte** zu zerlegen, was das **Training von LLMs** vereinfacht.
> - **Few-Shot Prompting** ist eine **flexible Technik**, die für eine **Vielzahl von Anwendungen** eingesetzt werden kann, z.B. **Textgenerierung**, **Übersetzung**, **Zusammenfassungen** etc.
> - **Few-Shot Prompting** ist ein **wichtiger Bestandteil des Prompt Engineerings**, einer neuen Disziplin, die sich mit der **effektiven Interaktion mit LLMs** beschäftigt.

---

## Inhalte
- Was ist Few-Shot Prompting?
- Elemente eines Few-Shot Prompts

---
### Was ist Few-Shot Prompting?
>[!info]- Grundlagen
>- **Few-Shot Prompting** ist eine Technik, bei der ein **Sprachmodell** anhand weniger **Beispiele** trainiert wird, eine bestimmte **Aufgabe** zu erfüllen.
>- Anstatt dem Modell **explizite Regeln** beizubringen, lernt es durch **Mustererkennung** und **Verallgemeinerung** aus den Beispielen.
>- **Few-Shot Prompting** ermöglicht es, **Sprachmodelle** schnell an neue **Aufgaben** anzupassen, ohne dass grosse **Trainingsdatensätze** erforderlich sind.

>[!abstract]- Funktionsweise
>- **Vorbereitung**: Der Benutzer definiert die **gewünschte Aufgabe** und wählt **repräsentative Beispiele** aus, die den **Input** und den **gewünschten Output** zeigen.
>- **Prompting**: Der Benutzer gibt dem **Sprachmodell** eine **Anweisung** (**Prompt**), die die **Aufgabe** beschreibt und die **Beispiele** enthält.
>- **Inferenz**: Das **Sprachmodell** analysiert den **Prompt** und die **Beispiele** und versucht, das **Muster** zu erkennen, das den Input mit dem Output verbindet.
>- **Anwendung**: Das **Sprachmodell** wendet das erlernte **Muster** auf neue, unbekannte **Inputs** an, um den **gewünschten Output** zu generieren.

>[!example]- Demonstration
> **Prompt für die Übersetzung von Deutsch nach Englisch:**

> **Aufgabe:** Übersetze die folgenden deutschen Sätze ins Englische.

> **Beispiel 1:**
> **Input:** Hallo Welt!
> **Output:** Hello World!

> **Beispiel 2:**
> **Input:** Wie geht es dir?
> **Output:** How are you?

> **Neuer Input:** Guten Morgen!

> **Erwarteter Output:** Good morning!

>[!tip]- Anwendungen
>- **Textübersetzung**: **LLMs** können mit **Few-Shot Prompting** trainiert werden, um **Texte** zwischen verschiedenen **Sprachen** zu übersetzen.
>- **Textzusammenfassung**: **LLMs** können mit **Few-Shot Prompting** trainiert werden, um **lange Texte** in **kürzere Zusammenfassungen** zu komprimieren.
>- **Sentimentanalyse**: **LLMs** können mit **Few-Shot Prompting** trainiert werden, um die **Stimmung** oder **emotionale Tonalität** eines **Textes** zu erkennen.
>- **Codegenerierung**: **LLMs** können mit **Few-Shot Prompting** trainiert werden, um **Code** in verschiedenen **Programmiersprachen** zu generieren.
>- **Kreatives Schreiben**: **LLMs** können mit **Few-Shot Prompting** trainiert werden, um **kreative Texte** wie **Gedichte**, **Geschichten** oder **Songtexte** zu verfassen.

## Übungen 
>[!question] Auftrag:  Einen Few-Shot Prompt für die Zusammenfassung von Nachrichtenartikeln erstellen
>Erstellen Sie einen Few-Shot Prompt, der einem LLM beibringt, kurze Zusammenfassungen von Nachrichtenartikeln zu generieren.
>>[!todo]- Anleitung 
>>1. Wählen Sie **zwei Nachrichtenartikel** aus und schreiben Sie jeweils eine **kurze Zusammenfassung** (maximal zwei Sätze).
>>2. Formulieren Sie eine **Anweisung** (**Prompt**), die dem LLM die **Aufgabe** der **Textzusammenfassung** erklärt.
>>3. Fügen Sie die **Nachrichtenartikel** und die dazugehörigen **Zusammenfassungen** als **Beispiele** in den Prompt ein.
>>4. Fügen Sie einen **neuen Nachrichtenartikel** hinzu, den das LLM zusammenfassen soll.
>
>>[!example]- Beispiel
>>**Aufgabe:** Fasse den folgenden Nachrichtenartikel in maximal zwei Sätzen zusammen.

>>**Beispiel 1:**
>>**Input:** *{Nachrichtenartikel 1}*
>>**Output:** *{Zusammenfassung von Nachrichtenartikel 1}*

>>**Beispiel 2:**
>>**Input:** *{Nachrichtenartikel 2}*
>>**Output:** *{Zusammenfassung von Nachrichtenartikel 2}*

>>**Neuer Input:** *{Nachrichtenartikel 3}*

>[!tip]- Weitere Hinweise
>- Wählen Sie **Nachrichtenartikel** aus verschiedenen **Themenbereichen**, um dem LLM ein breiteres **Spektrum** an **Texten** zu zeigen.
>- Achten Sie darauf, dass die **Zusammenfassungen** die **wichtigsten Informationen** des Artikels enthalten.
>- Experimentieren Sie mit verschiedenen **Formulierungen** für die **Anweisung** und die **Beispiele**.
>### Probieren Sie selber
>- Wie könnten Sie Few-Shot Prompting nutzen, um ein LLM zu trainieren, Filmkritiken zu schreiben?
>- Wie könnten Sie Few-Shot Prompting nutzen, um ein LLM zu trainieren, Produktbeschreibungen zu verfassen?
>- Wie könnten Sie Few-Shot Prompting nutzen, um ein LLM zu trainieren, Social-Media-Posts zu generieren?

> [!question]- Diskussionsfragen
>- Welche Vorteile bietet Few-Shot Prompting im Vergleich zu anderen Methoden des maschinellen Lernens?
>- Welche Herausforderungen gibt es beim Few-Shot Prompting?

---

### Elemente eines Few-Shot Prompts
>[!info]- Grundlagen
>- Ein effektiver **Few-Shot Prompt** besteht aus drei Hauptteilen: **Klare Instruktionen**, **repräsentative Beispiele** und **Struktur und Formatierung**.
>- **Klare Instruktionen** geben dem **LLM** eine präzise **Anweisung**, was es tun soll.
>- **Repräsentative Beispiele** zeigen dem **LLM** den **gewünschten Input** und **Output**.
>- **Struktur und Formatierung** helfen dem **LLM**, die **relevanten Informationen** im **Prompt** zu erkennen.

>[!abstract]- Funktionsweise
>- **Klare Instruktionen**: Die **Instruktionen** sollten in **einfacher Sprache** formuliert sein und **keine Fachbegriffe** enthalten, die das **LLM** möglicherweise nicht versteht. 
>- **Repräsentative Beispiele**: Die **Beispiele** sollten die **gewünschte Aufgabe** und den **gewünschten Output** möglichst genau abbilden. Je mehr **Beispiele** Sie geben, desto besser kann das **LLM** das **Muster** erkennen.
>- **Struktur und Formatierung**: Verwenden Sie eine **einheitliche Struktur** und **Formatierung** für Ihre **Beispiele**. Dies hilft dem **LLM**, die **relevanten Informationen** schnell zu erfassen.

>[!example]- Demonstration
> **Prompt für die Zusammenfassung von Texten:**

> **Aufgabe:** Fasse den folgenden Text in einem Satz zusammen.

> **Beispiel 1:**
> **Input:** Der Hund bellte laut. Die Katze rannte weg. Der Vogel sang auf dem Baum.
> **Output:** Ein Hund bellte, eine Katze rannte weg und ein Vogel sang auf einem Baum.

> **Beispiel 2:**
> **Input:** Das Auto fuhr schnell. Der Fahrer hupte. Die Ampel war rot.
> **Output:** Ein Auto fuhr schnell, der Fahrer hupte, obwohl die Ampel rot war.

> **Neuer Input:** Der Junge spielte Fussball. Das Mädchen las ein Buch. Die Sonne schien.

> **Erwarteter Output:** Ein Junge spielte Fussball, ein Mädchen las ein Buch und die Sonne schien.

>[!tip]- Anwendungen
>- **Jede Aufgabe, die mit Few-Shot Prompting gelöst werden kann, profitiert von gut formulierten Instruktionen, repräsentativen Beispielen und einer klaren Struktur.**
>- **Die Qualität des Prompts hat einen direkten Einfluss auf die Qualität des Outputs des LLMs.**
>- **Experimentieren Sie mit verschiedenen Formulierungen und Beispielen, um die besten Ergebnisse zu erzielen.**

## Übungen 
>[!question] Auftrag:  Einen Few-Shot Prompt analysieren
>Analysieren Sie den folgenden Few-Shot Prompt und identifizieren Sie die drei Hauptteile (Instruktionen, Beispiele, Struktur/Formatierung):

> **Aufgabe:** Fasse den folgenden Text in einem Satz zusammen.

> **Beispiel 1:**
> **Input:** Der Frosch sprang über den Stein. Die Sonne schien hell. Der Himmel war blau.
> **Output:** Ein Frosch sprang an einem sonnigen Tag über einen Stein.

> **Beispiel 2:**
> **Input:** Das Mädchen aß einen Apfel. Der Apfel war rot. Das Mädchen lächelte.
> **Output:** Ein Mädchen aß einen roten Apfel und lächelte.

>>[!todo]- Anleitung 
>>1. Lesen Sie den **Prompt** sorgfältig durch.
>>2. Identifizieren Sie die **Instruktionen**, die dem **LLM** die **Aufgabe** erklären.
>>3. Identifizieren Sie die **Beispiele**, die den **gewünschten Input** und **Output** zeigen.
>>4. Beschreiben Sie die **Struktur** und **Formatierung** des **Prompts**.
>
>>[!example]- Beispiel
>>**Instruktionen:** "Fasse den folgenden Text in einem Satz zusammen."
>>**Beispiele:** Zwei Beispiele mit jeweils einem Input-Text und einer Zusammenfassung in einem Satz.
>>**Struktur und Formatierung:** Der Prompt verwendet eine klare Struktur mit Überschriften für die Aufgabe und die Beispiele. Der Input und Output sind jeweils durch eine Leerzeile getrennt.

>[!tip]- Weitere Hinweise
>- Achten Sie auf die **Sprache** und **Formulierung** der **Instruktionen**.
>- Bewerten Sie die **Qualität** und **Repräsentativität** der **Beispiele**.
>- Überlegen Sie, ob die **Struktur** und **Formatierung** des **Prompts** für das **LLM** leicht zu verstehen sind.
>### Probieren Sie selber
>- Erstellen Sie einen eigenen Few-Shot Prompt für eine Aufgabe Ihrer Wahl und analysieren Sie die drei Hauptteile.
>- Vergleichen Sie Ihren Prompt mit dem Prompt eines Mitschülers und diskutieren Sie die Unterschiede.
>- Experimentieren Sie mit verschiedenen Formulierungen und Beispielen, um die Qualität Ihres Prompts zu verbessern.

> [!question]- Diskussionsfragen
>- Warum ist es wichtig, klare Instruktionen in einem Few-Shot Prompt zu verwenden?
>- Wie können Sie sicherstellen, dass Ihre Beispiele repräsentativ für die gewünschte Aufgabe sind?
>- Welche Rolle spielt die Struktur und Formatierung eines Few-Shot Prompts?

---

>[!abstract]- Zusammenfassung
> **Few-Shot Prompting** ist eine Technik, die es uns ermöglicht, **LLMs** (Large Language Models) mit **wenigen Beispielen** für **spezifische Aufgaben** zu trainieren. 
> Ein **effektiver Few-Shot Prompt** besteht aus **klaren Instruktionen**, **repräsentativen Beispielen** und einer **einheitlichen Struktur**. 
> Durch die sorgfältige Gestaltung von **Prompts** können wir die **Genauigkeit** und **Effizienz** von **LLMs** verbessern und diese für eine **Vielzahl von Anwendungen** einsetzen.
