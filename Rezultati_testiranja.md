# Rezultati testiranja

## Jedinični testovi

| Test naziv              | Očekivani rezultat | Status  |
|-------------------------|--------------------|---------|
| testCalculateAddition   | 5                  | ✅       |
| testCalculateMultiplication | 20            | ✅       |
| testDivisionByZero      | Infinity           | ✅       |
| testOperatorPrecedence  | 20                 | ✅       |

## Zaključci
1. Svi testovi su uspešno prošli, što potvrđuje ispravnost osnovne logike kalkulatora.
2. Deljenje nulom je ispravno obrađeno i rezultat je `Infinity`.
3. Prioritet operacija (npr. množenje pre sabiranja) funkcioniše prema očekivanjima.
4. Nema detektovanih grešaka u testovima.
