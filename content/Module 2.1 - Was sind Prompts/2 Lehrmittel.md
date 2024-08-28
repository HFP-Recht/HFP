# Prompts und Prompt Engineering: Theoretische Grundlagen

> [!info] Wieso Prompts und Prompt Engineering?
>- **Prompts** sind der **Schlüssel** zur **effektiven Nutzung** von **grossen Sprachmodellen (LLMs)**.
>- **Prompt Engineering** ermöglicht es uns, **LLMs** für **spezifische Aufgaben** zu **optimieren** und **präzise Ergebnisse** zu erzielen.
>- **LLMs** werden in immer mehr **Bereichen** eingesetzt, von der **Texterstellung** über die **Softwareentwicklung** bis hin zur **Forschung**.
>- **Prompt Engineering** ist eine **zukunftsweisende Fähigkeit**, die in vielen **Berufen** immer wichtiger wird.
>- Das **Verständnis von Prompts** und **Prompt Engineering** ist essenziell, um die **Möglichkeiten** und **Grenzen** von **LLMs** zu verstehen.

---

## Inhalte
- Was ist ein Prompt?
- Dimensionen eines Prompts

---
### Was ist ein Prompt?
>[!info]- Grundlagen
>- Ein **Prompt** ist eine **Anweisung** oder **Frage**, die an ein **grosses Sprachmodell (LLM)** gerichtet wird, um eine bestimmte **Ausgabe** zu generieren.
>- **Prompts** können in **verschiedenen Formen** auftreten, z.B. als **Fragen**, **Aufforderungen**, **Anweisungen** oder **Kombinationen** davon.
>- **LLMs** verarbeiten den **Prompt** und **generieren** basierend darauf eine **Antwort**, die dem **gewünschten Ergebnis** entsprechen soll.

>[!abstract]- Funktionsweise
>- **Eingabe**: Der Benutzer gibt einen **Prompt** in das **LLM** ein.
>- **Verarbeitung**: Das **LLM** analysiert den **Prompt** und **interpretiert** die **Anweisungen** oder **Fragen**.
>- **Generierung**: Das **LLM** **generiert** eine **Ausgabe** basierend auf dem **Prompt** und seinem **internen Wissen**.
>- **Ausgabe**: Das **LLM** präsentiert dem Benutzer die **generierte Ausgabe**, z.B. einen Text, eine Antwort auf eine Frage oder eine Zusammenfassung.

>[!example]- Demonstration
> **Prompt an ChatGPT:**
> 1. Öffnen Sie die ChatGPT-Webseite.
> 2. Geben Sie den folgenden **Prompt** ein: "Schreibe eine kurze Zusammenfassung des Märchens 'Rotkäppchen'."
> 3. Beobachten Sie, wie ChatGPT eine **Zusammenfassung** des Märchens generiert.

>[!tip]- Anwendungen
>- **Textgenerierung**: **Prompts** können verwendet werden, um **LLMs** dazu zu bringen, **Texte** in verschiedenen Stilen und Formaten zu generieren.
>- **Informationsbeschaffung**: **Prompts** können **LLMs** dazu anleiten, **spezifische Informationen** aus ihren Trainingsdaten zu extrahieren.
>- **Kreative Aufgaben**: **Prompts** können **LLMs** inspirieren, **Geschichten**, **Gedichte** oder **Songs** zu schreiben.
>- **Problemlösung**: **Prompts** können **LLMs** dazu bringen, **Lösungen** für komplexe Probleme zu finden.

## Übungen 
>[!question] Auftrag:  Einen Prompt für eine Produktbeschreibung erstellen
> Stellen Sie sich vor, Sie arbeiten für ein Unternehmen, das ein neues Smartphone auf den Markt bringt. Formulieren Sie einen Prompt, der ein LLM dazu bringt, eine ansprechende Produktbeschreibung für das Smartphone zu generieren.
>>[!todo]- Anleitung 
>>1. Überlegen Sie, welche **wichtigen Eigenschaften** und **Vorteile** das Smartphone hat.
>>2. Formulieren Sie einen **Prompt**, der diese Informationen enthält und das **LLM** dazu auffordert, eine **Produktbeschreibung** zu schreiben.
>>3. Achten Sie darauf, dass der **Prompt** klar und prägnant ist und den **gewünschten Stil** der Produktbeschreibung vorgibt.
>
>>[!example]- Beispiel
>>"Schreibe eine Produktbeschreibung für ein neues Smartphone mit folgenden Eigenschaften: 6,7-Zoll-Display, 128 GB Speicherplatz, 50-Megapixel-Kamera. Betone die Vorteile des Smartphones für mobile Fotografie und Gaming."

>[!tip]- Weitere Hinweise
>- Verwenden Sie **Schlüsselwörter**, die für die **Zielgruppe** relevant sind.
>- Geben Sie dem **LLM** **Beispiele** für den gewünschten Stil der Produktbeschreibung.
>- **Testen** Sie den **Prompt** mit verschiedenen **LLMs**, um die besten Ergebnisse zu erzielen.
>### Probieren Sie selber
>- Wie könnten Sie einen Prompt formulieren, um ein LLM dazu zu bringen, einen Werbetext für ein neues Getränk zu schreiben?
>- Wie könnten Sie einen Prompt formulieren, um ein LLM dazu zu bringen, eine Anleitung für den Bau eines Vogelhauses zu schreiben?
>- Wie könnten Sie einen Prompt formulieren, um ein LLM dazu zu bringen, einen Brief an den Gemeinderat zu schreiben, in dem Sie sich für den Bau eines neuen Spielplatzes einsetzen?

> [!question]- Diskussionsfragen
>- Welche Rolle spielt die **Qualität** eines **Prompts** für die **Ausgabe** eines **LLMs**?
>- Welche **Herausforderungen** seht ihr bei der **Formulierung effektiver Prompts**?

---

### Dimensionen eines Prompts
>[!info]- Grundlagen
>- **Prompts** sind nicht nur einfache **Fragen** oder **Anweisungen**. Sie haben **verschiedene Dimensionen**, die die **Interaktion** mit **LLMs** beeinflussen.
>- **Prompts** können **explizite Anweisungen** enthalten, aber auch **implizite Hinweise** geben, die das **LLM** bei der **Generierung der Ausgabe** berücksichtigt.
>- Das **Verständnis** der **Dimensionen eines Prompts** ist wichtig, um **effektive Prompts** zu erstellen und die **gewünschten Ergebnisse** von **LLMs** zu erzielen.

>[!abstract]- Funktionsweise
>- **Direktheit**: **Prompts** können **direkt** sein, indem sie **explizite Anweisungen** geben, z.B. "Schreibe eine Zusammenfassung des Textes."
>- **Indirektheit**: **Prompts** können auch **indirekt** sein, indem sie **Hinweise** oder **Kontext** liefern, z.B. "Der Text handelt von den Auswirkungen des Klimawandels."
>- **Spezifität**: **Prompts** können **spezifisch** sein, indem sie **detaillierte Anweisungen** geben, z.B. "Schreibe eine Zusammenfassung des Textes, die nicht länger als 100 Wörter ist und die wichtigsten Argumente des Autors hervorhebt."
>- **Allgemeinheit**: **Prompts** können auch **allgemein** sein, indem sie dem **LLM** mehr **Freiheit** bei der **Generierung der Ausgabe** lassen, z.B. "Was sind die wichtigsten Punkte des Textes?"
>- **Tonalität**: **Prompts** können die **Tonalität** der **Ausgabe** beeinflussen, z.B. "Schreibe eine humorvolle Geschichte" oder "Schreibe einen sachlichen Bericht".

>[!example]- Demonstration
> **Dimensionen eines Prompts in ChatGPT:**
> 1. Öffnen Sie die ChatGPT-Webseite.
> 2. Experimentieren Sie mit **Prompts** unterschiedlicher **Direktheit**, **Spezifität** und **Tonalität**.
> 3. Beobachten Sie, wie sich die **Dimensionen des Prompts** auf die **Ausgabe** von ChatGPT auswirken.

>[!tip]- Anwendungen
>- **Kreatives Schreiben**: **Prompts** mit unterschiedlichen **Tonalitäten** können **LLMs** dazu bringen, **Texte** in verschiedenen Stilen zu generieren.
>- **Informationsbeschaffung**: **Spezifische Prompts** helfen, **präzise Informationen** von **LLMs** zu erhalten.
>- **Problemlösung**: **Indirekte Prompts** können **LLMs** dazu anregen, **kreative Lösungen** für Probleme zu finden.

## Übungen 
>[!question] Auftrag:  Einen Prompt für eine Reiseplanung erstellen
> Sie planen eine Reise nach Rom und möchten ein LLM nutzen, um Informationen über Sehenswürdigkeiten, Restaurants und Unterkünfte zu erhalten. Formulieren Sie einen Prompt, der die Dimensionen "Spezifität" und "Tonalität" berücksichtigt.
>>[!todo]- Anleitung 
>>1. Überlegen Sie, welche **spezifischen Informationen** Sie für Ihre Reiseplanung benötigen.
>>2. Entscheiden Sie sich für eine **Tonalität**, die zu Ihren Reisevorlieben passt (z.B. abenteuerlich, romantisch, entspannt).
>>3. Formulieren Sie einen **Prompt**, der diese Informationen enthält und das **LLM** dazu auffordert, Ihnen bei der Reiseplanung zu helfen.
>
>>[!example]- Beispiel
>>"Ich plane eine romantische Reise nach Rom mit meinem Partner. Wir interessieren uns für historische Sehenswürdigkeiten, gemütliche Restaurants mit italienischer Küche und ein charmantes Hotel in der Nähe des Stadtzentrums. Können Sie uns Tipps für unsere Reiseplanung geben?"

>[!tip]- Weitere Hinweise
>- Verwenden Sie **Schlüsselwörter**, die Ihre **Reisevorlieben** widerspiegeln.
>- Geben Sie dem **LLM** **Beispiele** für die gewünschte **Tonalität**.
>- **Testen** Sie den **Prompt** mit verschiedenen **LLMs**, um die besten Ergebnisse zu erzielen.
>### Probieren Sie selber
>- Wie könnten Sie einen Prompt formulieren, um ein LLM dazu zu bringen, eine Rede für eine Hochzeit zu schreiben?
>- Wie könnten Sie einen Prompt formulieren, um ein LLM dazu zu bringen, einen Beschwerdebrief an ein Unternehmen zu schreiben?
>- Wie könnten Sie einen Prompt formulieren, um ein LLM dazu zu bringen, ein Drehbuch für einen Kurzfilm zu schreiben?

> [!question]- Diskussionsfragen
>- Wie können die **Dimensionen eines Prompts** die **Ausgabe** eines **LLMs** beeinflussen?
>- Welche **Dimensionen** sind für welche **Anwendungen** besonders relevant?

---

>[!abstract]- Zusammenfassung
> **Prompts** sind die **Schnittstelle** zwischen **Mensch** und **LLM**. Das **Verständnis** der **Dimensionen eines Prompts** ist essenziell, um **LLMs** effektiv zu nutzen und die **gewünschten Ergebnisse** zu erzielen. Durch die **gezielte Gestaltung** von **Prompts** können wir **LLMs** für eine Vielzahl von **Anwendungen** **optimieren** und unser **Verständnis** von **Sprache** und **künstlicher Intelligenz** erweitern.
