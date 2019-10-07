# Allgemeine Informationen zur FSI-Organisation auf GitHub

Status: Draft/WIP

## Beiträge

Beiträge in Form von Issues oder Pull Requests sind immer willkommen :)

Wer nicht GitHub nutzen möchte kann gerne Git Patches an
fsi@fsi.uni-tuebingen.de senden ([HowTo](https://git-send-email.io/)).

Auf Beiträge sollte stets freundlich und respektvoll reagiert werden. Gibt es
Mängel (ist nicht schlimm), so wird dies angemerkt (sollte nicht persönlich
genommen werden), damit diese entsprechend behoben werden können.

Spezifische Regeln und Tipps finden sich in der `README` des jeweiligen
Repositories.

Bei Fragen steht die Fachschaft gerne zur Verfügung (z.B. per Mail oder Issue).

### Reviews

Sollte auf einen Pull Request oder ein Issue nicht reagiert werden, so liegt
dies wahrscheinlich daran, dass der Beitrag versehentlich übersehen wurde. In
dem Fall können explizit Contributors angepingt werden (z.B. die Personen, die
zuletzt einen Commit gepusht haben). Fachschaftler*innen können auch ein
entsprechendes `fsi-tue` Team pingen (geht leider nur für Mitglieder der GitHub
Organisation).

### Commit Messages

Wie man gute Commit Messages schreibt wird unter anderem in dem Blog-Post
[How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
erklärt. Unter anderem müssen Commit Messages auf Englisch geschrieben sowie
nach Möglichkeit folgende Regeln eingehalten werden:
- Use the imperative mood in the subject line
- Limit the subject line to 72 (better: 50) characters
- Capitalize the subject line
- Do not end the subject line with a period
- Separate subject from body with a blank line
- Wrap the body at 72 characters
- Use the body to explain what and why vs. how

### Git Configuration

Die Konfigurationsoptionen `user.name` und `user.email` sollten auf sinnvolle
Werte gesetzt werden. Die Option `user.name` sollte auf den vollständigen Namen
(Vor- und Nachname) gesetzt werden und die Email-Adresse für `user.email` sollte
mit der Email-Adresse übereinstimmen, die bei GitHub hinterlegt ist, damit die
Commits dem richtigen GitHub Benutzer zugeordnet werden können.

Die Optionen können folgendermaßen konfiguriert werden, wobei die zugewiesenen
Werte entsprechend ersetzt werden müssen:

```
git config --global user.name "John Doe"
git config --global user.email "john.doe@example.org"
```

## Administratives

### Anlegen neuer Repositories

Nur die FSI-Administratoren können neue Repositories unter der `fsi-tue`
Organisation anlegen. Neue Repositories können von jedem per Mail an
fsi-admin@fsi.uni-tuebingen.de oder über ein Issue in diesem Repository
beantragt werden.

Kriterien:
- Es muss eine FLOSS-Lizenz verwendet werden
  - [Informationen zu Lizenzen](https://choosealicense.com/)
  - [SPDX License List](https://spdx.org/licenses/)
  - Empfehlungen:
    - Software: GPL-3.0-or-later, MIT
    - Sonstiges: CC-BY-SA-4.0, CC-BY-4.0, CC0-1.0
- Das neue fsi-tue Repo ist das upstream Repository (nicht ein Fork)
- Das Repo wird zusammen mit der Fachschaft gewartet (es sollten mindestens zwei
  Personen Schreibzugriff haben)
- Es sollte für die Fachschaft bzw. Studierende relevant sein
