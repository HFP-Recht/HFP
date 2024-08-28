# Einführung in Prompt Engineering: Den LLMs neue Informationen beibringen: Theoretische Grundlagen
> [!info] Wieso "Einführung in Prompt Engineering: Den LLMs neue Informationen beibringen"?
>- **LLMs (Large Language Models)** wie ChatGPT revolutionieren die Art und Weise, wie wir mit Computern interagieren.
>- **Prompt Engineering** ist der Schlüssel, um das volle Potenzial von LLMs auszuschöpfen.
>- Durch geschicktes Prompting können wir LLMs **neue Informationen** beibringen und sie für **spezifische Aufgaben** optimieren.
>- Das Verständnis der **theoretischen Grundlagen** von Prompt Engineering ist essenziell, um effektive Prompts zu erstellen.
>- **Prompt Engineering** ist eine **zukunftsweisende Fähigkeit**, die in vielen Bereichen relevant sein wird.

---

## Inhalte
- LLMs und die Notwendigkeit neuer Informationen
- Prompt Size Limitations: Mit Informationsgrenzen umgehen

---
### LLMs und die Notwendigkeit neuer Informationen
>[!info]- Grundlagen
>- **LLMs** sind **künstliche Intelligenzen**, die auf riesigen Textmengen trainiert werden.
>- Sie können **Texte generieren**, **Fragen beantworten** und **verschiedene Aufgaben** ausführen.
>- **LLMs** haben jedoch einen **begrenzten Wissensstand**, der auf den Zeitpunkt ihres letzten Trainings datiert ist.
>- Um auf **aktuelle Informationen** oder **private Daten** zuzugreifen, müssen wir LLMs diese **im Prompt bereitstellen**.
>- **Prompt Engineering** ist die Kunst, **effektive Prompts** zu erstellen, die LLMs mit den notwendigen Informationen versorgen.

>[!abstract]- Funktionsweise
>- **LLMs** lernen aus den **Mustern und Beziehungen** in den Trainingsdaten.
>- Sie können diese Muster **verallgemeinern**, um auch auf **neue, unbekannte Informationen** zu reagieren.
>- **Prompts** dienen als **Eingabesignal** für LLMs und geben ihnen den **Kontext** und die **gewünschte Aufgabe** vor.
>- Durch die Bereitstellung von **neuen Informationen im Prompt** können wir LLMs dazu bringen, **über ihren ursprünglichen Wissensstand hinaus** zu denken und zu handeln.
>- **Prompt Engineering** ermöglicht es uns, LLMs für **spezifische Anwendungsfälle** zu **personalisieren** und zu **optimieren**.

>[!example]- Demonstration
> **ChatGPT nach einem aktuellen Ereignis fragen:**
> 1. Fragen Sie ChatGPT nach einem Ereignis, das nach seinem letzten Training stattgefunden hat, z.B. "Was waren die wichtigsten Ereignisse im Jahr 2023?".
> 2. ChatGPT wird wahrscheinlich antworten, dass es keinen Zugriff auf Informationen nach seinem letzten Training hat.
> 3. Stellen Sie nun die gleiche Frage, aber fügen Sie im Prompt Informationen über das aktuelle Jahr hinzu, z.B. "Es ist jetzt Januar 2024. Was waren die wichtigsten Ereignisse im Jahr 2023?".
> 4. ChatGPT kann nun auf die neuen Informationen zugreifen und eine Antwort generieren.

>[!tip]- Anwendungen
>- **Recherche**: LLMs können mit aktuellen Informationen versorgt werden, um bei der Recherche zu helfen.
>- **Personalisierung**: LLMs können mit privaten Daten gefüttert werden, um personalisierte Antworten zu generieren.
>- **Entscheidungsunterstützung**: LLMs können mit relevanten Informationen versorgt werden, um bei der Entscheidungsfindung zu unterstützen.
>- **Kreativität**: LLMs können mit neuen Informationen inspiriert werden, um kreative Inhalte zu generieren.
>- **Problemlösung**: LLMs können mit spezifischen Informationen versorgt werden, um bei der Lösung von Problemen zu helfen.

## Übungen 
>[!question] Auftrag:  ChatGPT über ein aktuelles Ereignis informieren
>Wählen Sie ein aktuelles Ereignis aus und recherchieren Sie Informationen dazu. Erstellen Sie einen Prompt, der ChatGPT über das Ereignis informiert und eine Frage dazu stellt.
>>[!todo]- Anleitung 
>>1. Wählen Sie ein Ereignis aus, das nach dem letzten Training von ChatGPT stattgefunden hat.
>>2. Recherchieren Sie Informationen zu diesem Ereignis aus vertrauenswürdigen Quellen.
>>3. Fassen Sie die wichtigsten Informationen in wenigen Sätzen zusammen.
>>4. Formulieren Sie eine Frage zu dem Ereignis, die ChatGPT beantworten soll.
>>5. Erstellen Sie einen Prompt, der die Informationen und die Frage enthält.
>
>>[!example]- Beispiel
>>**Ereignis:** Die Fussball-Weltmeisterschaft 2022 in Katar
>>**Informationen:** Die Fussball-Weltmeisterschaft 2022 fand vom 20. November bis zum 18. Dezember 2022 in Katar statt. Argentinien gewann das Finale gegen Frankreich im Elfmeterschiessen.
>>**Frage:** Wer hat die Fussball-Weltmeisterschaft 2022 gewonnen?
>>**Prompt:** Die Fussball-Weltmeisterschaft 2022 fand vom 20. November bis zum 18. Dezember 2022 in Katar statt. Argentinien gewann das Finale gegen Frankreich im Elfmeterschiessen. Wer hat die Fussball-Weltmeisterschaft 2022 gewonnen?

>[!tip]- Weitere Hinweise
>- Achten Sie darauf, dass die Informationen im Prompt korrekt und relevant sind.
>- Formulieren Sie die Frage klar und prägnant.
>- Testen Sie den Prompt mit ChatGPT und überprüfen Sie die Antwort.
>### Probieren Sie selber
>- Informieren Sie ChatGPT über ein aktuelles Sportereignis.
>- Informieren Sie ChatGPT über eine neue wissenschaftliche Entdeckung.
>- Informieren Sie ChatGPT über ein politisches Ereignis.

> [!question]- Diskussionsfragen
>- Welche Herausforderungen ergeben sich aus der Notwendigkeit, LLMs mit neuen Informationen zu versorgen?
>- Wie können wir sicherstellen, dass die Informationen, die wir LLMs geben, korrekt und vertrauenswürdig sind?

---

### Prompt Size Limitations: Mit Informationsgrenzen umgehen
>[!info]- Grundlagen
>- **Prompts** sind die **Eingaben**, die wir LLMs geben, um sie zu instruieren.
>- **LLMs** haben jedoch **begrenzte Kapazitäten**, um Informationen in einem Prompt zu verarbeiten.
>- Die **Promptgrösse** ist begrenzt, d.h. wir können nicht unbegrenzt viele Informationen in einem Prompt unterbringen.
>- **Prompt Size Limitations** können dazu führen, dass LLMs **Aufgaben nicht ausführen** können oder **fehlerhafte Antworten** generieren.
>- **Prompt Engineering** beinhaltet auch die **Optimierung der Promptgrösse**, um die **Effektivität von LLMs** zu maximieren.

>[!abstract]- Funktionsweise
>- LLMs verarbeiten Informationen in **Tokens**, d.h. in einzelnen Wörtern oder Wortbestandteilen.
>- Die **maximale Anzahl von Tokens** in einem Prompt ist **modell- und API-abhängig**.
>- Wenn die **Promptgrösse** die maximale Tokenanzahl überschreitet, kann der LLM den Prompt **nicht verarbeiten**.
>- **Strategien zur Informationsverdichtung** sind wichtig, um die **Promptgrösse** zu reduzieren.
>- **Zusammenfassen**, **Priorisieren** und **Strukturieren** von Informationen sind wichtige Techniken, um **effektive Prompts** zu erstellen, die die **Prompt Size Limitations** berücksichtigen.

>[!example]- Demonstration
> **Prompt Size Limitations in ChatGPT:**
> 1. Kopieren Sie einen sehr langen Text, z.B. einen Wikipedia-Artikel.
> 2. Fügen Sie den Text in ChatGPT ein und stellen Sie eine Frage dazu.
> 3. ChatGPT wird wahrscheinlich eine Fehlermeldung ausgeben, dass der Text zu lang ist.
> 4. Fassen Sie den Text nun in wenigen Sätzen zusammen und stellen Sie die gleiche Frage.
> 5. ChatGPT kann nun den kürzeren Prompt verarbeiten und eine Antwort generieren.

>[!tip]- Anwendungen
>- **Textzusammenfassung**: LLMs können verwendet werden, um lange Texte zu kürzen und die wichtigsten Informationen zu extrahieren.
>- **Informationsfilterung**: LLMs können verwendet werden, um relevante Informationen aus grossen Datensätzen zu filtern.
>- **Priorisierung**: LLMs können verwendet werden, um Informationen nach ihrer Wichtigkeit zu priorisieren.
>- **Strukturierung**: LLMs können verwendet werden, um Informationen in Listen, Tabellen oder andere strukturierte Formate zu bringen.

## Übungen 
>[!question] Auftrag:  Einen langen Text für ChatGPT zusammenfassen
>Wählen Sie einen langen Text aus und fassen Sie ihn in maximal 100 Wörtern zusammen, ohne wichtige Informationen zu verlieren.
>>[!todo]- Anleitung 
>>1. Wählen Sie einen langen Text aus, z.B. einen Zeitungsartikel, einen Blogbeitrag oder einen Wikipedia-Artikel.
>>2. Lesen Sie den Text sorgfältig durch und markieren Sie die wichtigsten Punkte.
>>3. Schreiben Sie eine Zusammenfassung des Textes in eigenen Worten, die die wichtigsten Punkte enthält.
>>4. Achten Sie darauf, dass die Zusammenfassung nicht mehr als 100 Wörter umfasst.
>
>>[!example]- Beispiel
>>**Originaltext:** [Ein langer Text über die Geschichte der künstlichen Intelligenz]
>>**Zusammenfassung:** Die künstliche Intelligenz (KI) hat eine lange Geschichte, die bis ins antike Griechenland zurückreicht. Im 20. Jahrhundert erlebte die KI einen Aufschwung mit der Entwicklung von Computern. In den letzten Jahren hat die KI durch Fortschritte im Bereich des maschinellen Lernens enorme Fortschritte gemacht. LLMs wie ChatGPT sind ein Beispiel für die neuesten Entwicklungen in der KI.

>[!tip]- Weitere Hinweise
>- Konzentrieren Sie sich auf die wichtigsten Schlüsselwörter und Fakten.
>- Vermeiden Sie unnötige Details und Wiederholungen.
>- Verwenden Sie eine klare und prägnante Sprache.
>### Probieren Sie selber
>- Fassen Sie einen wissenschaftlichen Artikel für ein Laienpublikum zusammen.
>- Fassen Sie ein komplexes Thema in einfachen Worten zusammen.
>- Fassen Sie ein langes Meeting-Protokoll in wenigen Punkten zusammen.

> [!question]- Diskussionsfragen
>- Welche ethischen Überlegungen sollten bei der Zusammenfassung von Informationen berücksichtigt werden?
>- Wie können wir sicherstellen, dass wir bei der Informationsverdichtung keine wichtigen Details verlieren?

---

>[!abstract]- Zusammenfassung
> **LLMs** sind leistungsstarke Werkzeuge, die unser Leben in vielerlei Hinsicht verändern können. Um ihr volles Potenzial auszuschöpfen, ist es wichtig, die **theoretischen Grundlagen** von **Prompt Engineering** zu verstehen. Durch die Berücksichtigung der **Notwendigkeit neuer Informationen** und der **Prompt Size Limitations** können wir **effektive Prompts** erstellen, die LLMs zu optimalen Leistungen führen. 
