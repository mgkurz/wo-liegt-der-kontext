# Workshop: Kontext statt perfektem Prompt

## Impuls (Kurzbeschreibung)

Jahrelang hieß es: Wer gute KI-Ergebnisse will, braucht den perfekten Prompt. Das stimmt so nicht mehr. Moderne Sprachmodelle scheitern selten an der Frage, sondern an fehlendem Kontext: Welche Rolle soll die KI einnehmen? Welches Material liegt ihr vor? Für welche Lerngruppe, mit welchem Ziel?

Der Impuls zeigt an Unterrichtsbeispielen, warum dieser Kontext nicht ins Chatfeld gehört, sondern an dauerhafte Orte: in Anweisungen und mitgelieferte Dateien. Das funktioniert in allen gängigen KI-Systemen. In AIS.chat, der datenschutzkonformen Schul-KI des Landes Hessen, wird daraus eine Vorlage, die sich per Link an Lernende weitergeben lässt.

Im zweiten Teil probieren die Teilnehmenden das selbst aus, mit einer eigenen Unterrichtsidee oder an einem vorbereiteten Beispiel.

## Zielgruppe und Rahmen

- Externe Fortbildung, Multiplikatoren
- Praktischer Teil: 30–60 Minuten
- Geräte: eigenes Gerät hilfreich, sonst Pool oder zu zweit
- Zugänge: Gemini Gems, ChatGPT Projects, Claude Projects kostenlos.

## Ablauf des praktischen Teils

Übung: Arbeitsblätter zu zwei unterschiedlichen Themen erstellen, einmal im reinen Chat, einmal im Projekt. Zeigt den Aufwandsunterschied direkt am eigenen Erleben, nicht nur am Ergebnis.

1. Phase 1, Chat ohne Projekt (ca. 10 Min): zwei Arbeitsblätter zu zwei unterschiedlichen Themen anfragen. Format, Operatoren und Sprachniveau müssen bei Thema 2 erneut in den Prompt geschrieben werden.
2. Phase 2, Projekt (ca. 15–20 Min): Materialstil-Vorlage einmal als Projektwissen hinterlegen. Danach nur noch das Thema angeben, für Arbeitsblatt 1 und 2. Formataufwand entfällt beim zweiten Mal.
3. Phase 3, Vergleich zu zweit (ca. 10 Min): Ergebnis vergleichen, außerdem den eigenen Tippaufwand reflektieren, wie oft musste Format/Operatoren erneut eingegeben werden.

Gesamtdauer ca. 35–40 Min, passt ins 30–60-Min-Fenster. Materialstil-Vorlage (siehe Mitzubringendes Material) direkt für diese Übung nutzbar.

## Mitzubringendes Material

- Fertiges Beispielprojekt zum Zeigen
- Kontext-Vorlage mit vier Fragen (Rolle, Material, Zielgruppe, Ziel)
- Fallback-Beispiele für Teilnehmende ohne eigenes Material: Kerncurriculum-Beispiel (fiktiv), Materialstil-Vorlage (Arbeitsblatt-Format plus Operatorenliste), Bewertungsraster-Beispiel mit Erwartungshorizont
- Kurzes Handout „So baue ich selbst eine Vorlage" für Multiplikatoren
- Datenschutz-Hinweis: keine echten Namen oder Personendaten in der Übung verwenden

## Unterrichtsideen / Einsatzszenarien

- **Fachprojekt pro Fach und Jahrgang**: Kerncurriculum, schulinternes Curriculum, Stoffverteilungsplan als Wissen. Jede Stundenplanung wird ein Chat darin.
- **Materialstil-Projekt**: eigene Arbeitsblatt-Vorlagen, Operatorenliste, Anforderungsbereiche, Sprachniveau. Ergebnis sind Aufgaben im immer gleichen Format.
- **Leistungsnachweise**: Bewertungsraster, Musterklausuren, Erwartungshorizonte als Wissen. Claude entwirft neue Aufgaben plus passenden Erwartungshorizont.
- **Lerngruppen-Projekt**: Differenzierungsbedarf, Methodenrepertoire, Sitzordnungslogik, ohne Namen und pseudonymisiert.
- **Langfristige Vorhaben**: Fachkonferenz, Medienbildungskonzept, Schulentwicklung, AG-Planung. Protokolle und Beschlüsse als Wissensdatenbank, damit der Stand nicht in Einzelchats verlorengeht.
- **Kommunikationsprojekt**: Textbausteine für Elternbriefe, Berichte, Förderpläne, ohne Personendaten.
- **Fachschaftsprojekt** als geteiltes Projekt, falls die Schule einen Team-Plan hat.

## Begründung: Warum Projekt-Arbeit besser ist als reiner Chat

1. Kein wiederholtes Eintippen von Rolle, Material und Ziel bei jedem neuen Chat.
2. Keine Vermischung verschiedener Themen im selben Verlauf (in einem Blog-Artikel als „Context Collapse" beschrieben, keine offizielle Herstellerquelle).
3. Dokumentierter „Lost-in-the-Middle"-Effekt: Bei sehr langen Kontexten sinkt die Genauigkeit für Informationen aus der Mitte des Kontextfensters, belegt durch mehrere Forschungsarbeiten (u. a. Liu et al. 2023 und Folgestudien).
4. Tokenaufwand, zwei getrennte Aspekte:
   - Der Chatverlauf selbst wächst bei jeder Anfrage unabhängig davon, ob ein Projekt genutzt wird.
   - Bei der Wissensbasis (Dateien) ruft Claude ab einer bestimmten Größe per RAG nur relevante Ausschnitte ab, statt das ganze Dokument neu zu verarbeiten. Offiziell von Anthropic dokumentiert. Für ChatGPT und Gemini kein vergleichbarer offizieller Beleg gefunden, nur die Organisationsfunktion ist belegt.
5. Teilbarkeit im Team, z. B. für ein Fachschaftsprojekt bei vorhandenem Team-Plan.

