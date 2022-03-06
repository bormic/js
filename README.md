# js
Palindrom Checker
Zwraca true, jeśli podany ciąg jest palindromem. W przeciwnym razie zwraca false. Palindrom to słowo lub zdanie zapisane w ten sam sposób zarówno w przód, jak i w tył, z pominięciem interpunkcji, wielkości liter i odstępów.

Sprawdzenie palindromu, przeze usunięcie wszystkich znaków niealfanumerycznych (interpunkcyjne, spacje i symbole) i zamiana liter na tej samej wielkości (małe).

Roman Numeral Converter
Przekształcenie podanej liczby na liczbę rzymską.

Caesars Cipher
Jednym z najprostszych i najbardziej znanych szyfrów jest szyfr Cezara , znany również jako szyfr przesuwny . W szyfrze tym znaczenia liter są przesunięte o określoną wartość.

Powszechnym współczesnym zastosowaniem jest szyfr ROT13, w którym wartości liter są przesunięte o 13 miejsc. Tak A ↔ N i B ↔ O i tak dalej.

Walidator numeru telefonu
Zwróci true, jeśli przekazany ciąg wygląda jak prawidłowy numer telefonu w USA, w przeciwnym razie zwróci false.

Kasa
Funkcja szuflady kasy, checkCashRegister() która jako pierwszy argument przyjmuje cenę zakupu (price), jako drugi argument płatność (cash), a jako trzeci argument kasę w kasie (cid). Funkcja checkCashRegister() zwraca obiekt z kluczem status i kluczem change:

return {status: "INSUFFICIENT_FUNDS", change: []}, jeśli gotówka w szufladzie jest mniejsza niż należna reszta lub jeśli nie możesz zwrócić dokładnej reszty.

return {status: "CLOSED", change: [...]} jeśli change, należna reszta, jest równa nominałowi gotówki w kasie.

W przeciwnym razie return {status: "OPEN", change: [...]}, z należną resztą w nominale, posortowaną w kolejności od najwyższej do najniższej, jako wartość klucza change.
