# Tickets Summary – Jira Ticketing System Lab

> **Uwaga:** Wszystkie dane w tym dokumencie są fikcyjne. Użytkownicy, nazwiska, działy i opisy zgłoszeń zostały stworzone wyłącznie na potrzeby projektu portfolio symulującego pracę supportu IT. Żadne dane nie odnoszą się do rzeczywistych osób ani organizacji.

---

## Użytkownicy (symulowani pracownicy)

Fikcyjni pracownicy zostali dodani do projektu Jira Service Management jako klienci (portal-only accounts) przy użyciu metody aliasów Gmail. Każdy alias w formacie `twojmail+imie.nazwisko@gmail.com` jest traktowany przez Atlassian jako osobne konto — zaproszenie trafia na jedną skrzynkę, co pozwala na aktywację wszystkich kont bez potrzeby zakładania wielu adresów e-mail.

Konta portal-only nie zajmują licencji agenta i są bezpłatne na planie Free.

| Imię i nazwisko | Dział | Adres (alias) | Rola w Jira |
|---|---|---|---|
| Anna Kowalska | Finanse | twojmail+anna.kowalska@gmail.com | Customer (portal-only) |
| Marek Tomaszewski | Marketing | twojmail+marek.tomaszewski@gmail.com | Customer (portal-only) |
| Katarzyna Wróbel | Sekretariat | twojmail+katarzyna.wrobel@gmail.com | Customer (portal-only) |
| Piotr Zając | Sprzedaż | twojmail+piotr.zajac@gmail.com | Customer (portal-only) |
| Joanna Nowak | HR | twojmail+joanna.nowak@gmail.com | Customer (portal-only) |
| Robert Michalski | Logistyka | twojmail+robert.michalski@gmail.com | Customer (portal-only) |

---

## Zgłoszenia (tickets)

| ID | Tytuł | Reporter | Priorytet | Kategoria | Status końcowy |
|---|---|---|---|---|---|
| JTSL1 | Nie mogę się zalogować – konto zablokowane | Anna Kowalska | High | Zarządzanie kontami | Resolved |
| JTSL2 | Zniknął dysk Z: po powrocie z urlopu | Marek Tomaszewski | Medium | Sieć / Uprawnienia | Resolved |
| JTSL3 | Drukarka w pokoju 204 nie drukuje | Katarzyna Wróbel | Medium | Sprzęt / Hardware | Resolved |
| JTSL4 | Brak internetu i dostępu do CRM | Piotr Zając | High | Sieć / Łączność | Resolved |
| JTSL5 | Komputer działa bardzo wolno | Joanna Nowak | Medium | Wydajność / Software | Escalated |
| JTSL8 | Kliknąłem link w mailu – podejrzenie phishingu | Robert Michalski | High | Bezpieczeństwo IT | Escalated |

---

## Opisy zgłoszeń

### JTSL1 · Anna Kowalska · High

**Zgłoszone:** 06.05.2025, 08:14 · Pokój 112

> Dzień dobry, od rana nie mogę zalogować się do komputera. Wpisuję hasło i wyskakuje komunikat że konto jest zablokowane. Próbowałam kilka razy wczoraj wieczorem bo hasło mi nie działało po tym jak je zmieniłam zdalnie i chyba za dużo razy się pomyliłam.
>
> Mam teraz pilne zestawienie do wysłania przed 10:00 – proszę o pomoc jak najszybciej!
>
> Komputer: FINANSE-PC04 · Użytkownik: a.kowalska

---

### JTSL2· Marek Tomaszewski · Medium

**Zgłoszone:** 06.05.2025, 09:02 · Open space, biurko M14

> Hej, wróciłem 06.05.2025 z 2-tygodniowego urlopu i nie widzę dysku Z: w eksploratorze. Przed urlopem wszystko działało normalnie. Inne dyski (C: i D:) są widoczne.
>
> Próbowałem wyłączyć i włączyć komputer – nie pomogło. Kolega z biurka obok ma ten dysk bez problemu, więc chyba coś z moim kontem?
>
> Na Z: mam foldery projektów które są mi teraz potrzebne.

---

### JTSL3 · Katarzyna Wróbel · Medium

**Zgłoszone:** 06.05.2025, 09:47 · Pokój 204

> Dzień dobry, drukarka HP w pokoju 204 przestała działać. Wysyłam wydruk, system pokazuje że wysłano, ale nic nie wychodzi z drukarki. Drukarka jest włączona, świeci się normalnie, żadnego błędu na wyświetlaczu nie widać.
>
> Sprawdziłam czy jest papier – jest. Prosiłam też Pana Krzysztofa żeby spróbował ze swojego komputera – u niego też nie działa.
>
> Czekamy już z 3 osoby, mamy dokumenty do wydrukowania.

---

### JTSL4 · Piotr Zając · High

**Zgłoszone:** 06.05.2025, 09:11 · Biuro sprzedaży, stanowisko 12B

> Cześć, od ok. 9:00 nie mam internetu ani dostępu do niczego firmowego. Strony nie ładują, CRM nie działa, Teams się rozłączył. Kabel siedzi w komputerze, lampka na karcie sieciowej nie miga (normalnie miga).
>
> Kolega po drugiej stronie biurka (stanowisko 13A) ma internet bez problemu. Restartowałem komputer dwa razy – bez efektu.
>
> Mam 06.05.2025 kilka ważnych telefonów z klientami i muszę mieć dostęp do systemu. To pilne.
>
> Stanowisko: 12B · Komputer: SALES-PC12

---

### JTSL5 · Joanna Nowak · Medium

**Zgłoszone:** 06.05.2025, 10:22 · HR, pokój 301

> Dzień dobry, mój komputer od kilku dni działa coraz wolniej, ale 06.05.2025 jest już naprawdę nieznośnie. Otwarcie Outlooka zajmuje ponad 5 minut, a jak próbuję otworzyć plik Excel z bazą pracowników (ok. 3000 wierszy) to komputer się zawiesza i muszę go wyłączać z przycisku.
>
> Nie instalowałam ostatnio żadnych nowych programów. Nie wiem co się dzieje, może jakiś wirus?
>
> Komputer ma chyba ze 4 lata, nie wiem czy to ma znaczenie.

---

### JTSL8 · Robert Michalski · High

**Zgłoszone:** 06.05.2025, 08:51 · Magazyn, biuro logistyki

> Hej, dostałem 06.05.2025 rano maila od "IT Dział Wsparcia" z informacją że moje hasło wygasa i muszę je natychmiast zmienić przez link. Kliknąłem, otworzyła się strona która wyglądała jak nasza firmowa, wpisałem login i hasło...
>
> Ale potem mnie uderzyło że adres strony był dziwny – coś w stylu "firma-it-support.info" a nie nasza normalna domena. Myślę że to był phishing.
>
> Nie wiem czy podałem dane czy nie, trochę się spiąłem. Co mam teraz zrobić? Czy mam się odłączyć od internetu?

---

