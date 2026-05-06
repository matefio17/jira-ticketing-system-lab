# Jira Ticketing System Lab 🎟️




![Status](https://img.shields.io/badge/status-completed-brightgreen)

![Platform](https://img.shields.io/badge/platform-Jira%20Cloud-blue)

![Type](https://img.shields.io/badge/type-portfolio%20project-orange)





**Profesjonalna symulacja operacji IT Support z wykorzystaniem Jira Service Management (Atlassian) i diagnostyki Windows. Scenariusze oparte na celach certyfikacji CompTIA A+.**



---



## Spis treści



- [O projekcie](#o-projekcie)

- [Technologie](#technologie)

- [Struktura projektu](#struktura-projektu)

- [Scenariusze zgłoszeń](#scenariusze-zgłoszeń)

- [Workflow](#workflow)

- [Screenshoty](#screenshoty)

- [Czego się nauczyłem](#czego-się-nauczyłem)

- [Autor](#autor)



---



## O projekcie



Projekt został zaprojektowany tak, aby odwzorować realne zadania wykonywane na stanowisku Helpdesk / IT Support Specialist. Główne cele:



   • Praktyczna nauka obsługi systemu ticketowego Jira Service Management w kontekście wsparcia IT

   • Poznanie cyklu życia zgłoszenia: przyjęcie, diagnoza, rozwiązanie, zamkniecie

   • Ćwiczenie priorytetyzacji zadań (Low / Medium / High) i reakcji na incydenty

   • Dokumentowanie rozwiązań w sposób zrozumiały zarówno dla użytkownika, jak i dla kolejnego technika

   • Symulacja komunikacji z użytkownikiem końcowym

   • Zbudowanie portfolio technicznego z konkretnym, weryfikowalnym przykładem pracy



## Technologie



| Narzędzie | Wersja / Plan | Zastosowanie |
|-----------|--------------|--------------|
| Jira Service Management (Atlassian) | Free |  system ticketowy  |
| Windows 11 | — |  środowisko docelowe  |
| PowerShell / CMD | wbudowany |  diagnostyka  |
| GitHub | — |  dokumentacja  |



## Struktura projektu



```
jira-ticketing-system-lab

├── README.md
├── screenshots
│   ├── 01_ticketting_system_board.png
│   ├── 02_ticket_list.png
│   ├── 03_JTSL1_resolved.png
│   ├── 04_JTSL3_spooler.png
│   ├── 05_JTSL4_ipconfig.png
│   └── 06_JTSL8_security.png
└── tickets
     └── tickets_summary.md
```



## Scenariusze zgłoszeń



| ID | Tytuł | Priorytet | Kategoria | Status |
|----|-------|-----------|-----------|--------|
| JTSL1 | Nie mogę się zalogować – konto zablokowane | 🔴 HIGH | Konta |  OPEN  |
| JTSL2 | Brak dysku Z: | 🟡 MEDIUM | Sieć | OPEN  |
| JTSL3 | Drukarka w pokoju 204 nie drukuje – czeka kilka osób | 🟡 MEDIUM | Sprzęt |  OPEN  |
| JTSL4 | Brak internetu i brak dostępu do CRM – nie mogę pracować | 🔴 HIGH | Sieć |  OPEN  |
| JTSL5 | Komputer działa bardzo wolno, nie mogę otworzyć pliku Excel | 🟡 MEDIUM | Wydajność |  OPEN  |
| JTSL8 | Kliknąłem link w mailu i chyba coś się stało – proszę o pomoc | ‼️ HIGHEST | Bezpieczeństwo |  ESCALATED  |



## Workflow


- Diagram statusów

```

OPEN → IN PROGRESS → [AWAITING USER] → [ESCALATED] → RESOLVED → CLOSED

```


## Opis każdego statusu

**OPEN** - oznacza, że ticket został utworzony przez użytkownika i czeka aż któryś z techników go podejmie

**IN PROGRESS** - oznacza, że technik rozpoczął pracę nad rozwiązaniem problemu

**AWAITING USER** - Technik zrobił co mógł po swojej stronie ale żeby rozwiązać problem potrzebne jest konkretne działanie użytkownika

**ESCALATED** - Technik zbadał problem ale nie ma uprawnień lub kompetencji aby go rozwiązać. Problem przeniesiono wyżej.

**RESOLVED** - Problem został pomyślnie rozwiązany


## Zasady ogólne

- Podczas obsługi zgłoszeń istotne jest aby priorytetyzować swoje działanie. Służy do tego wbudowana funkcja ustalania priorytetu zgłoszenia. Przykładowo JTSL6 (Incydent bezpieczeństwa) będzie miał zdecydowanie wyższy priorytet niż JTSL5 (Wolne działanie komputera) z powodu wpływu dany problem może wywieść na całą firmę i ciągłość biznesową.

- Praca ze zgłoszeniami wymaga od technika jasnej i klarownej komunikacji z użytkownikiem na każdym etapie rozwiązywania problemu. Użytkownik musi być informowany o postępach w formie zrozumiałej dla osoby nietechnicznej. Technik powinien unikać używania żargonu lub slangu branżowego.

- Praca z użytkownikiem często wiąże się ze zdenerwowaniem lub irytacją użytkownika. Kluczowym elementem tego procesu jest opanowanie i empatia. Użytkownik powinien czuć się zrozumiany i wysłuchany.

- Technik nie powinien zakładać, że zna rozwiązanie problemu nawet gdy wydaje mu się, że jest o tym przekonany. Ważnym etapem rozwiązywania zgłoszeń jest dopytywanie użytkownika o szczegóły problemu tak aby poszerzyć swoje spojrzenie na daną nieprawidłowość.



## Przykłady z projektu

- Zgłoszenie JTSL 1 (Konta) - in progress

- Zgłoszenie JTSL 2 (Sieć) - in progress

- Zgłoszenie JTSL 3 (Sprzęt) - in progress

- Zgłoszenie JTSL 4 (Wydajność) - in progress

- Zgłoszenie JTSL 5 (Konta) - in progress

- Zgłoszenie JTSL 8 (Bezpieczeństwi) to krytyczna sytuacja zagrażająca całej firmie. Zgłoszenie zostało eskalowane wyżej, a do użytkownika wysłano zrozumiałą instrukcję postepowania (izolacja sieci)




## Screenshoty



- Widok Board – Jira Service Management

> [screenshots/01_ticketting_system_board.png](screenshots/01_ticketting_system_board.png)



- Lista zgłoszeń

> [screenshots/02_ticket_list.png](02_ticket_list.png)




- Przykładowy ticket (JTSL8)

> [screenshots/06_JTSL8_security.png](screenshots/06_JTSL8_security.png)




## Czego się nauczyłem



- Konfiguracja Jira Service Management na platformie Atlassian
- Obsługa workflow i zarządzanie statusami zgłoszeń
- Diagnostyka sieci: (`ipconfig`, `ping`, `tracert`)
- Reakcja na incydent bezpieczeństwa (phishing)


---



## **👨‍💻** Autor



**Mateusz Markiewicz** - Projekt zrealizowany w ramach praktycznej nauki i stanowi część portfolio

