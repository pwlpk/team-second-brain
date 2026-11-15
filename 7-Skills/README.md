# Skille zespołu

| Czynność | Skill |
| --- | --- |
| Podłącz prywatny i zespołowy klon | [team-connect](../.agents/skills/team-connect/SKILL.md) |
| Znajdź odpowiedź i jej podstawę | [team-query](../.agents/skills/team-query/SKILL.md) |
| Zaktualizuj wiedzę lub przygotuj PR z dostarczonej propozycji | [team-update](../.agents/skills/team-update/SKILL.md) |
| Zrób przegląd utrzymania lub przygotuj wybraną poprawkę | [team-garden](../.agents/skills/team-garden/SKILL.md) |

Instrukcje utrzymujemy w `.agents/skills/`. Codex czyta je z tego katalogu. Claude Code czyta te same pliki przez symlinki w `.claude/skills/`. Przy dodaniu skilla dla obu klientów zapisz w Git zarówno jego katalog, jak i odpowiadający mu względny symlink.

Po sklonowaniu otwórz nową sesję w katalogu głównym i wywołaj np. `$team-query` w Codexie albo `/team-query` w Claude Code. Claude Code potrzebuje klonu z zachowanymi symlinkami.

W prywatnym repo użyj `team-connect` albo skonfiguruj połączenie ręcznie. Lokalny `team-share` przygotuje patch i szkic PR-a w prywatnym repo. Zatwierdzoną propozycję może obsłużyć `team-update` w klonie zespołu. [Instalacja i fragment AGENTS.md](../docs/instalacja-w-prywatnym-repo.md)

[Dokumentacja skilli Codexa](https://learn.chatgpt.com/docs/build-skills) · [Dokumentacja Claude Code](https://code.claude.com/docs/en/skills)
