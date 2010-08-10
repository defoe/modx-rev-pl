Zasady ogólne
=============

Jeśli ktoś chce pomóc, wówczas zgłasza się do admina via e-mail burclaf(at)gmail.com, lub
wysyła wiadomość via Github. Następnie admin dodaje go do współpracujących nad projektem i już.

Każdy z współpracujących wybiera temat (plik, grupę plików) i tłumaczy aż do skutku, na tyle
na ile pozwala mu czas.

W przypadku wątpliwości co do tłumaczenia danej frazy tworzymy Zgłoszenie (Issue) w Githubie i tam rozważamy
kolektywnie co z fantem zrobić.

**Wszelkie informacje o commitach wpisujemy w języku polskim - z przyzwyczajenia 'initial import' dałem po angielsku :P**

**OGROMNA PRŚBA** - proszę uzupełniać pole COMMIT MESSAGE, jeśli edytujecie coś via WWW. W tym polu wrzucamy ogólny opis/podsumowanie zmian, więc jego uzupełnienie pomoże się nam później zorientować co zostało zmienione.

Uważam też, że najwygodniej sklonować sobie repo z tłumaczeniem za pomocą GIT, następnie pracować lokalnie (u siebie na komputerze), zapisywać do woli, po czym wysłać zmiany na githuba. Jeśli ktoś będzie miał problemy z obsługą git-a proszę o kontakt - bx2.

Wierność tłumaczenia
====================

Przed edycją danej frazy proponuje "remować" jej oryginał, na wszelki wypadek np.
lang['xxxx'] = 'This is default content..'
proponuje przetłumaczyć w następującej formie:
lang['xxxx'] = 'To jest domyślna treść..'  // 'This is defaul content..'

Uważam, że powinniśmy tłumaczyć w miarę dokładnie, ale podarujmy sobie spolszczanie zwrotów typu: "chunk","placeholder".
Jak napisał fixedmachine na forum:

    **Przykładowo:**
    - "chunk" a nie "wlepka", "link" a nie "odsyłacz" ale w przypadku tłumaczenia:
    - "The following Placeholders are replaced by the Content Manager when the message is sent:"
    nie tak jak to jest w obecnym tłumaczeniu:
    - "Następujące zmienne są zamieniane przez Panel Administracyjny kiedy wiadomość jest wysyłana:"
    a dajmy na to: "Podczas wysyłania wiadomości, następujące placeholdery zostaną wypełnione odpowiednimi danymi:"

Uwagi końcowe
=============

Zasady nie są wyryte w marmurze - w razie uwag lub pomysłów śmiało piszcie lub zgłaszajcie Issue :)

Obecny podział zadań
====================

Tutaj dopisujemy co kto robi, albo na co się deklaruje - najlepiej pełna ścieżka do tłumaczone obecnie pliku.

* qcol: pl-core od litery S do końca.
* bx2: pl-setup, całość (na ten moment mogę mieć problemy czasowe stąd mniejszy zakres rezerwuje)
* fixedmachine: pl-core od litery A do E.