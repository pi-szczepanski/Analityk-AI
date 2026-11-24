# Analityk AI

## Cel projektu

Celem projektu jest zbudowanie modułowego systemu „Analityk AI”,
w którym model językowy (LLM) jest wywoływany przez API, a jego
odpowiedzi w formacie JSON są automatycznie sprawdzane i oceniane.
System rozwijamy etapami, dodając kolejne moduły: `travel`, `finance`,
`plates`, `scholar` i `rag`.

### Cele szczegółowe

1. Przygotowanie uporządkowanego środowiska projektu: struktura
   katalogów, `README.md` i `requirements.txt`.
2. Wysyłanie zapytań do modelu przez API ze skryptu, z kluczem
   przechowywanym wyłącznie w sekretach (nigdy w kodzie ani w plikach
   projektu).
3. Kontrola jakości odpowiedzi walidatorem: zgodność ze schematem JSON,
   brakujące pola, błędy reguł.
4. Ocena modeli na podstawie czasu odpowiedzi, liczby tokenów
   i poprawności JSON oraz wybór API i modelu do dalszej pracy.
5. Zadbanie o bezpieczeństwo i wersjonowanie: historia wersji
   i procedura postępowania po wycieku klucza API.

## Lista zespołów

1. Fabian Misztela,
   Zuzanna Wikieł,
   Piotr Szczepański,
2. Kornel Pakulski,
   Wojciech Banasiak,
3. Jakub Pawlik,
   Bartłomiej Dawczyński,
4. Kacper Augustyniak,
   Paweł Kajmers

## Jak uruchomić moduły

