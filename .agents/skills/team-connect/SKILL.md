---
name: team-connect
description: Podłącz prywatny Superbrain do lokalnego klonu zespołu i sprawdź połączenie pytaniem o przyjętą wiedzę.
---
# Podłącz zespół

- Ustal prywatny i zespołowy klon, tożsamość repo zespołu i zakres połączenia. Zgodnie z [procedurą Git](../../../8-System/git-read.md) potwierdź `origin`, status `verified` i dostęp do `8-System/context-entry.md`. Przy niepowodzeniu zachowaj istniejącą konfigurację i podaj przyczynę oraz potrzebne działanie.
- Zapisz lub uaktualnij wpis w prywatnym `8-System/team-context.md` według [szablonu](../../../6-Templates/team-context.md). W prywatnym `AGENTS.md` dodaj regułę odczytu tego pliku i użycia `team-query` przy pracy w zakresie zespołu. Dodaj ją też do samodzielnego `CLAUDE.md`, jeśli nie importuje `AGENTS.md`. Zachowaj dotychczasowe instrukcje i inne połączenia.
- Udostępnij prywatny [team-share](../../../6-Templates/private-skills/team-share/SKILL.md). Skopiuj go do `.agents/skills/team-share/SKILL.md` w prywatnym repo, jeśli jeszcze go tam nie ma. Dla Claude Code dodaj względny symlink `.claude/skills/team-share` do tego katalogu. W tej samej regule w instrukcjach kieruj propozycje z prywatnych materiałów do lokalnego `team-share`.
- Wykonaj próbę z [team-query](../team-query/SKILL.md) na pytaniu wymagającym wspólnego źródła. Zakończ odpowiedzią z tym źródłem i SHA oraz listą zmienionych prywatnych plików.
