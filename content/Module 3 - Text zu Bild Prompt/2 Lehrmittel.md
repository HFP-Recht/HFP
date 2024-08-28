# Text-to-Image: Bilder mit Worten erschaffen: Theoretische Grundlagen 

> [!info] Wieso Text-to-Image?
> - **Bilder** sind aus der heutigen **Kommunikation** nicht mehr wegzudenken und oft effektiver als reine Texte.
> - **Text-to-Image** ermöglicht die **Erstellung von Bildern** ohne spezielle Designkenntnisse.
> - **KI-Modelle** können aus **Textbeschreibungen** eine **Vielzahl von Bildern** generieren, die man sich so vielleicht nicht hätte vorstellen können.
> - **Personalisierte Bilder** können für **Marketing**, **Werbung** oder **Social Media** einfach erstellt werden.
> - **Text-to-Image** ist ein spannendes Beispiel für die **künstliche Intelligenz** und ihre Möglichkeiten.

---
## Inhalte
- Einführung in die Text-to-Image-Generierung
- Prompting-Techniken für bessere Bilder

---
### Einführung in die Text-to-Image-Generierung
>[!info]- Grundlagen
>- **Künstliche Intelligenz (KI)** kann Bilder aus Textbeschreibungen, sogenannten **"Prompts"**, erstellen.
>- **Text-to-Image-Modelle** werden mit riesigen Datensätzen von Bildern und Texten trainiert, um die Beziehung zwischen Wörtern und visuellen Elementen zu lernen.
>- Ein **Prompt** kann einfache Begriffe, komplexe Beschreibungen oder sogar Emotionen enthalten.
>- Die **Qualität des generierten Bildes** hängt stark von der **Genauigkeit und Detailliertheit des Prompts** ab.
>- **KI-Modelle** für Text-to-Image sind noch in der Entwicklung, aber ihre Fähigkeiten verbessern sich ständig.

>[!abstract]- Funktionsweise
>- **Trainingsphase**: Dem KI-Modell werden Millionen von Bild-Text-Paaren gezeigt, um die **Zusammenhänge** zwischen **Sprache** und **visuellen Elementen** zu lernen.
>- **Eingabe des Prompts**: Der Benutzer gibt eine **Textbeschreibung** des gewünschten Bildes ein.
>- **Analyse und Interpretation**: Das KI-Modell **analysiert den Text**, **identifiziert Schlüsselwörter** und **interpretiert** die Beschreibung.
>- **Bildgenerierung**: Basierend auf dem Prompt und seinem Training generiert das Modell ein neues Bild, das der Beschreibung entsprechen soll.
>- **Ausgabe**: Das generierte Bild wird dem Benutzer angezeigt.

>[!example]- Demonstration
> **Einfache Bildgenerierung mit Craiyon (früher DALL-E mini):**
> 1. Besuchen Sie die Website von Craiyon: https://www.craiyon.com/
> 2. Geben Sie im Textfeld einen einfachen Prompt ein, z.B. "Eine Katze mit Hut auf einem Skateboard".
> 3. Klicken Sie auf "zeichnen".
> 4. Craiyon generiert nun verschiedene Bildvarianten basierend auf Ihrem Prompt.

>[!tip]- Anwendungen
>- **Konzeptkunst**: Künstler und Designer können Text-to-Image nutzen, um schnell **Ideen zu visualisieren** und **verschiedene Konzepte** zu erkunden.
>- **Illustration**: Illustratoren können mit KI **unterschiedliche Stile** und **Kompositionen** ausprobieren, bevor sie sich für eine finale Version entscheiden.
>- **Marketing und Werbung**: **Individuelle Bilder** für **Werbezwecke** können schnell und einfach generiert werden, ohne auf teure Fotoshootings angewiesen zu sein.

## Übungen 
>[!question] Auftrag: Beschreiben Sie ein Bild!
>Stellen Sie sich vor, Sie müssten einer Person, die Ihr Bild nicht sehen kann, so genau wie möglich beschreiben, was darauf zu sehen ist. 
>>[!todo]- Anleitung 
>>1. Wählen Sie ein Bild aus (z.B. aus einer Zeitschrift, Ihrem Smartphone oder dem Internet).
>>2. Beschreiben Sie das Bild in Worten, so detailliert wie möglich:
>>>- Was ist das **Hauptmotiv**?
>>>- Welche **Objekte** sind zu sehen?
>>>- Welche **Farben** dominieren?
>>>- Welche **Stimmung** vermittelt das Bild?
>>3. Tauschen Sie Ihre Beschreibung mit einem Partner und lassen Sie ihn das Bild anhand Ihrer Beschreibung erraten.
>
>>[!example]- Beispiel
>>"Auf dem Bild ist ein **kleines Mädchen** zu sehen. Es hat **blonde Haare** und trägt ein **rotes Kleid**. Das Mädchen sitzt auf einer **grünen Wiese** und pflückt **bunte Blumen**. Im Hintergrund sieht man einen **blauen Himmel** mit weissen Wolken. Das Bild wirkt **fröhlich und unbeschwert**."

>[!tip]- Weitere Hinweise
>- Versuchen Sie, Ihre Beschreibung so **präzise** wie möglich zu gestalten.
>- Verwenden Sie **anschauliche Adjektive**, um die **Atmosphäre** des Bildes einzufangen.
>- Überlegen Sie, welche **Details** besonders wichtig sind, um das Bild **eindeutig zu beschreiben**.
>### Probieren Sie selber
>- Beschreiben Sie ein Bild aus Ihrem Alltag und lassen Sie es von einer Person mithilfe eines Text-to-Image-Generators nachbilden.
>- Vergleichen Sie das Originalbild mit dem generierten Bild. Welche Unterschiede fallen Ihnen auf?
>- Wie könnte man den Prompt verbessern, um ein Ergebnis zu erzielen, das dem Originalbild noch ähnlicher ist?

> [!question]- Diskussionsfragen
>- Welche Vorteile bietet die Text-to-Image-Generierung im Vergleich zu traditionellen Methoden der Bilderstellung?
>- Welche Herausforderungen und Grenzen sehen Sie bei dieser Technologie?

---
### Prompting-Techniken für bessere Bilder
>[!info]- Grundlagen
>- **Style Modifiers:** Beschreiben den gewünschten **künstlerischen Stil** des Bildes (z.B. "Fotografie", "Cartoon", "Renaissance Gemälde").
>- **Quality Boosters:** Verbessern die **Bildqualität** (z.B. "hochauflösend", "detailreich", "scharf").
>- **Repetition:** **Hervorhebung** wichtiger Elemente durch Wiederholung im Prompt.
>- **Weighted Terms:** **Gewichtung** einzelner Wörter für stärkere Betonung (z.B. "sehr grosser Baum").
>- **Fix Deformed Generations:** Vermeidung von **Fehlern** in der Bildgenerierung (z.B. "Hände klar und deutlich").

>[!abstract]- Funktionsweise
>- **Style Modifiers** geben dem KI-Modell Hinweise auf den gewünschten **Stil** und die **Ästhetik** des Bildes.
>- **Quality Boosters** fordern das Modell auf, **mehr Ressourcen** in die Generierung bestimmter Aspekte des Bildes zu investieren.
>- **Repetition** hilft dem Modell, die **wichtigsten Elemente** des Prompts zu identifizieren.
>- **Weighted Terms** ermöglichen es, die **Bedeutung** einzelner Wörter zu **verstärken** oder **abzuschwächen**.
>- **Fix Deformed Generations** helfen, häufige **Fehler** bei der Bildgenerierung zu **vermeiden**.

>[!example]- Demonstration
> **Prompt-Verfeinerung mit verschiedenen Techniken:**
> 1. **Einfacher Prompt:** "Ein Hund im Park."
> 2. **Style Modifier:** "Ein **fotorealistischer** Hund im Park."
> 3. **Quality Booster:** "Ein fotorealistischer Hund im Park, **hochauflösend**."
> 4. **Repetition:** "Ein **fröhlicher, fröhlicher** Hund im Park, hochauflösend."
> 5. **Weighted Terms:** "Ein **sehr grosser**, fotorealistischer Hund im Park, hochauflösend."

>[!tip]- Anwendungen
>- **Kreativitätssteigerung:** Durch die Kombination verschiedener Prompting-Techniken können Sie die **Grenzen der KI** austesten und **einzigartige Bilder** kreieren.
>- **Effizienzsteigerung:** Mit den richtigen Techniken können Sie dem KI-Modell **klare Anweisungen** geben und so die **Qualität** der generierten Bilder **verbessern**.
>- **Experimentierfreude:** Haben Sie keine Angst, **verschiedene Kombinationen** von Prompting-Techniken auszuprobieren und zu sehen, welche Ergebnisse Sie erzielen.

## Übungen 
>[!question] Auftrag:  Vom Text zum Traumbild
>Wählen Sie einen einfachen Satz als Ausgangspunkt und verfeinern Sie ihn schrittweise mit den verschiedenen Prompting-Techniken, die wir kennengelernt haben.
>>[!todo]- Anleitung 
>>1. Schreiben Sie einen **einfachen Satz**, der ein Bild beschreibt (z.B. "Ein Haus am See").
>>2. Fügen Sie einen **Style Modifier** hinzu, um den **Stil** des Bildes festzulegen (z.B. "Ein Haus am See im Stil von Claude Monet").
>>3. Verwenden Sie einen **Quality Booster**, um die **Bildqualität** zu verbessern (z.B. "Ein detailreiches Haus am See im Stil von Claude Monet").
>>4. **Wiederholen** Sie wichtige Wörter, um ihre **Bedeutung** zu **hervorzuheben** (z.B. "Ein **gemütliches, gemütliches** Haus am See im Stil von Claude Monet").
>>5. Nutzen Sie **Weighted Terms**, um die **Ausprägung** bestimmter Elemente zu **steuern** (z.B. "Ein gemütliches, gemütliches Haus mit **einem grossen Garten** am See im Stil von Claude Monet").
>
>>[!example]- Beispiel
>>1. **Einfacher Satz:** "Eine Katze auf einem Baum."
>>2. **Style Modifier:** "Eine Katze auf einem Baum, im Stil einer **japanischen Tuschezeichnung**."
>>3. **Quality Booster:** "Eine **detaillierte** Katze auf einem Baum, im Stil einer japanischen Tuschezeichnung."
>>4. **Repetition:** "Eine **schwarze, schwarze** Katze auf einem Baum, im Stil einer japanischen Tuschezeichnung."
>>5. **Weighted Terms:** "Eine schwarze, schwarze Katze auf einem **sehr hohen** Baum, im Stil einer japanischen Tuschezeichnung."

>[!tip]- Weitere Hinweise
>- Achten Sie auf die **Grammatik** und **Satzzeichensetzung** in Ihren Prompts.
>- Verwenden Sie **eindeutige Begriffe**, um Missverständnisse zu vermeiden.
>- **Versetzen Sie sich in die Rolle des KI-Modells** und überlegen Sie, wie es Ihren Prompt interpretieren könnte.
>### Probieren Sie selber
>- Erstellen Sie mehrere Prompts für dasselbe Bild, aber mit unterschiedlichen Stilen und Schwerpunkten.
>- Generieren Sie die Bilder mit einem Text-to-Image-Generator und vergleichen Sie die Ergebnisse.
>- Analysieren Sie, wie die verschiedenen Prompting-Techniken die Bildgenerierung beeinflusst haben.

> [!question]- Diskussionsfragen
>- Welche Prompting-Techniken findet ihr besonders hilfreich, um die gewünschten Ergebnisse zu erzielen?
>- Inwiefern schränkt oder erweitert die Text-to-Image-Generierung die menschliche Kreativität?

---

>[!abstract]- Zusammenfassung
>Die **Text-to-Image-Generierung** ist eine vielversprechende Technologie mit grossem Potenzial. Durch das Verständnis der **theoretischen Grundlagen** und die Anwendung von **effektiven Prompting-Techniken** können wir die Möglichkeiten dieser Technologie optimal nutzen und unsere eigenen kreativen Visionen zum Leben erwecken. 
