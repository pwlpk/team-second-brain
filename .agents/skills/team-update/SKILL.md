---
name: team-update
description: Zaktualizuj wiedzę po badaniu, eksperymencie lub decyzji zespołu i otwórz Draft PR na GitHubie. Obsłuż także materiał przekazany przez team-share.
---
# Zaktualizuj wiedzę

Wynikiem jest gałąź w repo zespołu i rzeczywisty Draft PR na GitHubie. Przy zleceniu zmiany doprowadź do tego wyniku bez osobnego pytania o push lub utworzenie PR-a. Wyraźne ograniczenie użytkownika do planu, podglądu albo pracy lokalnej ma pierwszeństwo.

1. Przeczytaj wejście i dotknięte strony z [potwierdzonego SHA](../../../8-System/git-read.md). Dla prywatnego materiału, także z `team-share`, zastosuj [zasady awansowania](references/awansowanie.md); uwzględnij już udzieloną akceptację dokładnego zakresu.
2. Pracuj na osobnej gałęzi `codex/` repo zespołu od tego SHA; przy cudzych zmianach użyj osobnego worktree. Zaktualizuj strony, źródła, indeksy i powiązania według [kontraktu strony](../../../6-Templates/README.md). Zapisuj decyzje rzeczywiście podjęte przez ludzi. Uruchom `ruby scripts/check.rb`.
3. Przygotuj diff, uzasadnienie i ograniczenia. Wskaż [właściciela lub zastępcę](../../../8-System/owners.md) innego niż autor; brak przydziału zaznacz w PR-ze dla opiekuna. Dla prywatnego wejścia uzyskaj brakującą akceptację przygotowanego zakresu przed pushem. Nie zapisuj patcha ani szkicu PR-a w prywatnym `9-Outputs/`.
4. Commituj wyłącznie tę zmianę, wypchnij gałąź i utwórz Draft PR do domyślnej gałęzi zweryfikowanego repo według [szablonu](../../../.github/PULL_REQUEST_TEMPLATE.md). Przy kontynuacji zaktualizuj istniejący PR tej gałęzi. Odczytaj z GitHuba i podaj URL, stan Draft oraz wynik kontroli; lokalny diff nie jest PR-em. Przy braku dostępu lub błędzie podaj konkretną przeszkodę i zachowany stan gałęzi, zamiast ogłaszać zakończenie.

Utworzenie Draft PR-a nie oznacza przyjęcia wiedzy. Nie oznaczaj go jako gotowego do review ani nie scalaj bez zlecenia; obowiązuje [obieg review](../../../docs/uruchomienie-github.md).
