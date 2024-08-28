---
# Chatbot Entwicklung
### Auftrag Basic Level A 
#### Einfacher Informations-Chatbot

> [!abstract] Einfacher Informations-Chatbot
> In diesem Auftrag erstellen Sie einen einfachen Chatbot, der auf die Begrüssung des Benutzers reagiert und grundlegende Informationen über ein bestimmtes Thema liefert. Ziel ist es, die Grundlagen des Prompt Engineerings für Text-zu-Text-Aufgaben zu verstehen und anzuwenden.

>[!todo]- Ablauf
>- **Themenwahl:** Wählen Sie ein Thema für Ihren Chatbot.
>- **Informationsrecherche:** Recherchieren Sie grundlegende Informationen zu Ihrem Thema.
>- **Prompt-Erstellung:** Erstellen Sie einen Prompt, der das LLM dazu anleitet, auf eine Begrüssung zu reagieren und Informationen zu Ihrem Thema zu liefern.
>- **Chatbot-Test und -Verfeinerung:** Testen Sie Ihren Chatbot und verfeinern Sie Ihren Prompt.

>[!quote]- Prompting
> Für diesen Auftrag verwenden wir die **Aufgabenspezifikation** und die **kontextbezogene Anleitung**.  Die **Aufgabenspezifikation** stellt sicher, dass der Prompt klar und deutlich die gewünschte Aufgabe definiert. Die **kontextbezogene Anleitung** liefert dem LLM genügend Informationen, um die Anfrage zu verstehen und eine relevante Antwort zu generieren.

>[!note]- Material Einfacher Informations-Chatbot
> >[!info] Allgemein
> >**Themenwahl:**
> >Wählen Sie ein Thema, das Sie interessiert und zu dem Sie leicht Informationen finden können. Beispiele:
> >- Schweizer Geschichte
> >- Tourismus in der Schweiz
> >- Schweizer Schokolade
> >- Sport in der Schweiz
> >- Schweizer Erfindungen
> >
> >**Informationsrecherche:**
> >Recherchieren Sie grundlegende Informationen zu Ihrem Thema. Sie können Bücher, Websites oder andere Quellen verwenden. Notieren Sie die wichtigsten Fakten und Details, die Ihr Chatbot den Benutzern vermitteln soll.
>
> >[!quote]- Prompting Beispiele
> >**Beispiel 1:**
> >
> >"Du bist ein Chatbot, der Informationen über die Schweizer Geschichte liefert. Begrüsse den Benutzer und gib ihm eine kurze Einführung in die Schweizer Geschichte."
> >
> >**Beispiel 2:**
> >
> >"Du bist ein Chatbot, der Touristen über die Schweiz informiert. Begrüsse den Benutzer freundlich und frage ihn, welche Region der Schweiz ihn interessiert. Gib ihm dann Informationen über Sehenswürdigkeiten, Aktivitäten und Unterkünfte in dieser Region."
> >
> >**Beispiel 3:**
> >
> >"Du bist ein Chatbot, der Schweizer Schokolade verkauft. Begrüsse den Benutzer und stelle ihm die verschiedenen Schokoladensorten vor. Gib ihm Informationen über die Zutaten, den Geschmack und die Herstellung der Schokolade."
> 
> >[!abstract] Chatbot-Test und -Verfeinerung
> >Nachdem Sie Ihren Prompt erstellt haben, testen Sie Ihren Chatbot, indem Sie verschiedene Begrüssungen und Fragen eingeben. Beobachten Sie die Antworten des LLMs und bewerten Sie deren Qualität und Relevanz.
> >
> >Wenn die Antworten des Chatbots nicht zufriedenstellend sind, verfeinern Sie Ihren Prompt. Sie können den Prompt klarer formulieren, zusätzliche Informationen hinzufügen oder Beispiele für die gewünschte Ausgabe geben.
> >
> >Wiederholen Sie den Test- und Verfeinerungsprozess, bis Ihr Chatbot die gewünschten Antworten liefert.

>[!tip]- Weitere Hinweise
>- Verwenden Sie einfache Sprache und vermeiden Sie Fachbegriffe, es sei denn, sie sind notwendig.
>- Experimentieren Sie mit verschiedenen Prompt-Formulierungen, um herauszufinden, was am besten funktioniert.
>- Seien Sie kreativ und haben Sie Spass beim Erstellen Ihres Chatbots!
>### Probieren Sie selber
>- Wie könnten Sie einen Chatbot erstellen, der als virtueller Assistent für Ihren Alltag fungiert?
>- Wie könnten Sie einen Chatbot erstellen, der Schülern bei den Hausaufgaben hilft?
>- Wie könnten Sie einen Chatbot erstellen, der als Spielfigur in einem Videospiel agiert?

> [!warning]- Präsentation
> Am Ende des Auftrags präsentieren Sie Ihren Chatbot der Klasse. Zeigen Sie, wie Ihr Chatbot funktioniert und welche Prompt Engineering Techniken Sie verwendet haben. Erklären Sie, welche Herausforderungen Sie bei der Entwicklung des Chatbots hatten und wie Sie diese gelöst haben.

---
# Chatbot Entwicklung
### Auftrag Basic Level B
#### Reiseführer-Chatbot

> [!abstract] Reiseführer-Chatbot
> In diesem Auftrag erstellen Sie einen Chatbot, der als Reiseführer für eine bestimmte Region der Schweiz fungiert. Der Chatbot soll auf Fragen zu Sehenswürdigkeiten, Aktivitäten und Unterkünften antworten können. Ziel ist es, die Anwendung des Interview Pattern Approach zu üben.

>[!todo]- Ablauf
>- **Region auswählen:** Wählen Sie eine Region in der Schweiz, für die Sie einen Reiseführer-Chatbot erstellen möchten.
>- **Informationsrecherche:** Recherchieren Sie Informationen über Sehenswürdigkeiten, Aktivitäten und Unterkünfte in der Region.
>- **Fragenkatalog erstellen:** Erstellen Sie einen Katalog mit Fragen, die typischerweise von Touristen gestellt werden.
>- **Prompt erstellen:**  Definieren Sie die Rolle des Chatbots als 'Reiseführer für [Region]' und erstellen Sie einen Prompt, der den Interview Pattern Approach verwendet.
>- **Chatbot testen und verfeinern:** Testen Sie den Chatbot und verfeinern Sie den Prompt.

>[!quote]- Prompting
> Beim **Interview Pattern Approach** simulieren wir ein Interview mit dem LLM. Wir definieren eine Rolle für das LLM und stellen offene Fragen, die zu detaillierten Antworten anregen. Basierend auf den Antworten des LLMs stellen wir Folgefragen, um den Kontext zu verfeinern und die gewünschten Informationen zu erhalten.

>[!note]- Material Reiseführer-Chatbot
> >[!info] Allgemein
> >**Region auswählen:**
> >Wählen Sie eine Region in der Schweiz, die Sie gut kennen oder die Sie gerne besser kennenlernen würden. Beispiele:
> >- Berner Oberland
> >- Graubünden
> >- Wallis
> >- Tessin
> >- Zürich
> >
> >**Informationsrecherche:**
> >Recherchieren Sie Informationen über die Region, die für Touristen relevant sind. Sie können Websites, Reiseführer oder Broschüren verwenden. Sammeln Sie Informationen über:
> >- Sehenswürdigkeiten
> >- Aktivitäten
> >- Unterkünfte
> >- Restaurants
> >- Transportmöglichkeiten
>
> >[!quote]- Fragenkatalog Beispiele
> >**Allgemeine Fragen:**
> >- Was sind die wichtigsten Sehenswürdigkeiten in [Region]?
> >- Welche Aktivitäten kann man in [Region] unternehmen?
> >- Welche Unterkünfte gibt es in [Region]?
> >- Wo kann man in [Region] gut essen?
> >- Wie kommt man am besten nach [Region]?
> >
> >**Spezifische Fragen:**
> >- Gibt es in [Region] familienfreundliche Aktivitäten?
> >- Welche Wanderwege empfehlen Sie in [Region]?
> >- Gibt es in [Region] Museen oder historische Stätten?
> >- Welche Restaurants in [Region] bieten traditionelle Schweizer Küche an?
> >- Kann man in [Region] Fahrräder mieten?
> >
> >**Prompt Beispiele:**
> >
> >"Du bist ein Reiseführer für das Berner Oberland. Begrüsse den Benutzer freundlich und frage ihn, was er in der Region unternehmen möchte. Gib ihm dann massgeschneiderte Empfehlungen."
> >
> >"Du bist ein Reiseführer für Graubünden. Begrüsse den Benutzer und stelle ihm die verschiedenen Regionen Graubündens vor. Frage ihn dann, welche Region ihn am meisten interessiert, und gib ihm detaillierte Informationen."
> 
> >[!abstract] Chatbot testen und verfeinern
> >Testen Sie Ihren Chatbot, indem Sie verschiedene Fragen aus Ihrem Katalog und darüber hinaus stellen. Achten Sie darauf, wie der Chatbot auf die Fragen reagiert und ob die Antworten relevant und hilfreich sind.
> >
> >Wenn der Chatbot nicht die gewünschten Antworten liefert, verfeinern Sie Ihren Prompt. Sie können die Rollendefinition klarer formulieren, die Fragen umformulieren oder zusätzliche Informationen in den Prompt einfügen.
> >
> >Experimentieren Sie mit verschiedenen Prompt-Variationen, um die beste Leistung aus Ihrem Chatbot herauszuholen.

>[!tip]- Weitere Hinweise
>- Verwenden Sie ansprechende Sprache und versuchen Sie, die Persönlichkeit eines echten Reiseführers zu imitieren.
>- Integrieren Sie Bilder, Videos oder Links in die Antworten des Chatbots, um die Informationen ansprechender zu gestalten.
>- Stellen Sie sicher, dass der Chatbot auf Rechtschreibung und Grammatik achtet.
>### Probieren Sie selber
>- Wie könnten Sie einen Chatbot erstellen, der als virtueller Concierge für ein Hotel fungiert?
>- Wie könnten Sie einen Chatbot erstellen, der personalisierte Empfehlungen für Restaurants gibt?
>- Wie könnten Sie einen Chatbot erstellen, der bei der Planung von Events hilft?

> [!warning]- Präsentation
> Präsentieren Sie Ihren Reiseführer-Chatbot der Klasse. Zeigen Sie, wie der Chatbot funktioniert und welche Prompt Engineering Techniken Sie verwendet haben. Demonstrieren Sie die Interaktion mit dem Chatbot anhand von Beispielfragen.

---
# Chatbot Entwicklung
### Auftrag Basic Level C
#### Mathematik-Chatbot

> [!abstract] Mathematik-Chatbot
> In diesem Auftrag erstellen Sie einen Chatbot, der einfache mathematische Textaufgaben lösen kann. Ziel ist es, die Anwendung der Chain-of-Thought Technik zu üben.

>[!todo]- Ablauf
>- **Textaufgaben sammeln:** Sammeln Sie eine Reihe von einfachen mathematischen Textaufgaben.
>- **Chain-of-Thought Prompts erstellen:** Für jede Textaufgabe erstellen Sie einen Prompt, der die Aufgabe, die Lösung und den schrittweisen Denkprozess enthält.
>- **Chatbot testen und verfeinern:** Testen Sie den Chatbot mit den erstellten Prompts und neuen Textaufgaben.

>[!quote]- Prompting
> Die **Chain-of-Thought Technik** hilft dem LLM, komplexe Probleme Schritt für Schritt zu lösen. Der Prompt enthält eine Frage und eine detaillierte Antwort, die den Denkprozess Schritt für Schritt darstellt. Das LLM wird aufgefordert, eine neue Frage mit dem gleichen logischen Ansatz zu beantworten.

>[!note]- Material Mathematik-Chatbot
> >[!info] Allgemein
> >**Textaufgaben sammeln:**
> >Sammeln Sie einfache mathematische Textaufgaben, die für die Altersgruppe der Schüler geeignet sind. Die Aufgaben sollten Addition, Subtraktion, Multiplikation oder Division beinhalten. Sie können Aufgaben aus Schulbüchern, Arbeitsblättern oder Online-Ressourcen verwenden.
> >
> >**Chain-of-Thought Prompts erstellen:**
> >Für jede Textaufgabe erstellen Sie einen Prompt, der die Aufgabe, die Lösung und den schrittweisen Denkprozess enthält.
>
> >[!quote]- Prompting Beispiele
> >**Beispiel 1:**
> >
> >**Aufgabe:** "Anna hat 4 Äpfel. Sie bekommt von ihrer Oma 3 weitere Äpfel. Wie viele Äpfel hat Anna jetzt?"
> >
> >**Prompt:**
> >
> >```
> >Frage: Anna hat 4 Äpfel. Sie bekommt von ihrer Oma 3 weitere Äpfel. Wie viele Äpfel hat Anna jetzt?
> >Antwort: Anna hatte 4 Äpfel. Sie bekam 3 weitere Äpfel. Also hat sie jetzt 4 + 3 = 7 Äpfel.
> >Neue Frage: Peter hat 6 Murmeln. Er verliert 2 Murmeln. Wie viele Murmeln hat Peter jetzt?
> >```
> >
> >**Beispiel 2:**
> >
> >**Aufgabe:** "Ein Bäcker backt 12 Brötchen. Er verkauft 7 Brötchen. Wie viele Brötchen hat er noch übrig?"
> >
> >**Prompt:**
> >
> >```
> >Frage: Ein Bäcker backt 12 Brötchen. Er verkauft 7 Brötchen. Wie viele Brötchen hat er noch übrig?
> >Antwort: Der Bäcker backte 12 Brötchen. Er verkaufte 7 Brötchen. Also hat er noch 12 - 7 = 5 Brötchen übrig.
> >Neue Frage: Ein Bauer hat 8 Kühe. Er kauft 5 weitere Kühe. Wie viele Kühe hat der Bauer jetzt?
> >```
> 
> >[!abstract] Chatbot testen und verfeinern
> >Testen Sie Ihren Chatbot, indem Sie ihm die erstellten Prompts und neue Textaufgaben geben. Beobachten Sie, ob der Chatbot die Aufgaben korrekt löst und ob der Denkprozess klar und nachvollziehbar ist.
> >
> >Wenn der Chatbot Fehler macht oder der Denkprozess unklar ist, verfeinern Sie Ihre Prompts. Sie können die Schritte im Denkprozess detaillierter beschreiben oder zusätzliche Beispiele hinzufügen.
> >
> >Experimentieren Sie mit verschiedenen Prompt-Variationen, um die beste Leistung aus Ihrem Mathematik-Chatbot herauszuholen.

>[!tip]- Weitere Hinweise
>- Achten Sie darauf, dass die mathematischen Aufgaben altersgerecht und verständlich formuliert sind.
>- Verwenden Sie verschiedene Arten von mathematischen Aufgaben, um den Chatbot zu trainieren.
>- Fordern Sie den Chatbot auf, seine Rechenschritte zu erklären.
>### Probieren Sie selber
>- Wie könnten Sie einen Chatbot erstellen, der komplexere mathematische Aufgaben lösen kann?
>- Wie könnten Sie einen Chatbot erstellen, der Schülern bei der Algebra hilft?
>- Wie könnten Sie einen Chatbot erstellen, der mathematische Konzepte erklärt?

> [!warning]- Präsentation
> Präsentieren Sie Ihren Mathematik-Chatbot der Klasse. Zeigen Sie, wie der Chatbot mathematische Textaufgaben löst und welche Prompt Engineering Techniken Sie verwendet haben. Demonstrieren Sie die Chain-of-Thought Technik anhand von Beispielen.

---
