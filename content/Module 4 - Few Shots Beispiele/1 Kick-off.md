# Einführung in Few-Shot Prompting

> [!tip] Alltag
> Stellen Sie sich vor, Sie bringen einem Hund einen neuen **Trick** bei. Anstatt ihm lange zu erklären, was er tun soll, zeigen Sie ihm den **gewünschten Ablauf** Schritt für Schritt und belohnen ihn, wenn er es richtig macht. Durch **Wiederholung** und **positive Verstärkung** lernt der Hund - ganz ähnlich wie ein **Sprachmodell** beim **Few-Shot Prompting**.

> [!info]- Was ist möglich?
> - Sie können einem Sprachmodell beibringen, **Texte zusammenzufassen**.
> - Sie können ein Sprachmodell dazu bringen, **verschiedene Programmiersprachen zu verstehen und Code zu generieren**.
> - Sie können ein Sprachmodell nutzen, um **Gedichte oder Songtexte zu schreiben**.

>[!question]- Diskussion
>- Wie lernen Menschen neue Dinge?
>- Wie unterscheidet sich das Lernen von Computern vom Lernen von Menschen?
>- Welche Rolle spielen **Beispiele** beim Lernen?

> [!success]- Lernziele
> In dieser Einheit lernen wir das **Few-Shot Prompting** kennen, eine Methode, um **grosse Sprachmodelle** (LLMs) für spezifische Aufgaben zu trainieren. 
> Das Ziel dieser Einheit ist, dass Sie...
> - das **Konzept des Few-Shot Prompting** verstehen.
> - die **Elemente eines effektiven Few-Shot Prompts** kennenlernen.
> - **erste eigene Prompts erstellen** können.

> [!question]- Wie weiter?
> - **Was ist Few-Shot Prompting?**
> > - **Few-Shot Prompting** ist eine Technik, um **Sprachmodelle** (LLMs) mit wenigen **Beispielen** zu trainieren.
> > - Anstatt dem Modell **explizite Regeln** vorzugeben, lernt es durch **Mustererkennung** aus den Beispielen.
> > - **Few-Shot Prompting** ermöglicht es, LLMs schnell an neue **Aufgaben** anzupassen.
> - **Elemente eines Few-Shot Prompts:**
> > - Ein **Few-Shot Prompt** besteht aus **klaren Instruktionen**, **repräsentativen Beispielen** und einer **einheitlichen Struktur**.
> > - **Klare Instruktionen** beschreiben die **gewünschte Aufgabe** in einfachen Worten.
> > - **Repräsentative Beispiele** zeigen dem Modell den **gewünschten Input** und **Output**.
> > - **Struktur und Formatierung** helfen dem Modell, die **relevanten Informationen** zu erkennen. 
