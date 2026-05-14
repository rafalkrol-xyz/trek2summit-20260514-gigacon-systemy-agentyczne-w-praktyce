---
title: "Systemy agentyczne w praktyce: Jak firmy (naprawdę) korzystają z agentów na AWS?"
author: Rafał Król
theme:
  name: catppuccin-latte
---

# Agenda

## 1. Krótko o Trek2Summit i o mnie
## 2. Dlaczego AI nie jest lekiem na całe zło?
## 3. Kiedy warto, a kiedy to jest bez sensu
## 4. Czym jest agent AI i co się stało z przedrostkiem Gen?
## 5. Duże wdrożenie, memy, małe wdrożenia
## 6. Co polecam na start
## 7. Q&A

<!-- end_slide -->

# Trek2Summit

![image:width:90%](./images/trek2summit.png)

<!-- pause -->

## Spejaliści chmurowi i nie tylko: AI, DevOps, Security, FinOps, Backup, Managed Services

<!-- pause -->

## Biura w Polsce i Wielkiej Brytanii

<!-- pause -->

## Klienci głównie z SMB, ale także Public i Enterprise

<!-- end_slide -->

# O mnie

## Rafał Król

<!-- pause -->

## 10 lat pracy z AWS | 10+ zdanych egzaminów AWSowych | AWS Community Builder

<!-- pause -->

## obecnie Head of AWS Technologies | wcześniej Principal Solutions Architect, Cloud SRE, Software Engineer...

<!-- pause -->

![image:width:100%](./images/flight_attendant.jpeg)

<!-- pause -->

### Ze Stewarda w DevOpsa 👉 *https://www.youtube.com/@ZmieniamNaIT*

<!-- end_slide -->

# Dlaczego AI nie jest lekiem na całe zło?

<!-- column_layout: [1, 1] -->
<!-- column: 0 -->

<!-- pause -->

![image:width:100%](./images/autoland.jpeg)

<!-- pause -->

## Airbus A320

<!-- pause -->

## W służbie komercyjnej od 1988

<!-- pause -->

## Potrafi sam lądować

<!-- pause -->

<!-- column: 1 -->
![image:width:100%](./images/hbr_when_and_how_to_use_ai.png)

<!-- end_slide -->

# Kiedy warto, a kiedy to jest bez sensu

![image:width:60%](./images/hbr_shortened.png)

<!-- column_layout: [1, 1] -->
<!-- column: 0 -->
<!-- pause -->
### Dobry kandydat
- Zadanie **wieloetapowe**, wymaga decyzji
- Dane są **dostępne i w miarę czyste**
- Błąd jest **odwracalny** lub wykrywalny
- **Setki/tysiące** przypadków dziennie
- Człowiek robi to samo, tylko **wolniej i drożej** lub niechętnie
- Wynik probabilistyczny jest akceptowalny, np. klasyfikacja zgłoszeń, podsumowania
<!-- column: 1 -->
<!-- pause -->
### Zły kandydat
- **Jednorazowe** zadanie o niskim poziomie skomplikowania
- Dane **wrażliwe bez odpowiedniego nadzoru (governance)**
- Błąd jest **katastrofalny i nieodwracalny**
- Brak możliwości **ewaluacji jakości**
- Wymagana **100% pewność** odpowiedzi
- Bardzo niski wolumen (< kilkanaście zapytań/mc)
- Wynik musi być deterministyczny, np. naliczanie podatku, dawkowanie leku

<!-- end_slide -->

# Czym jest agent AI i co się stało z przedrostkiem Gen?

<!-- column_layout: [1, 1] -->
<!-- column: 0 -->
<!-- pause -->
![image:width:100%](./images/ai_onion.png)
<!-- column: 1 -->
<!-- pause -->
![image:width:100%](./images/agentic_ai.png)
<!-- reset_layout -->
<!-- pause -->
## Zmiana obietnicy biznesowej od *tworzenia* do *działania*
<!-- column_layout: [1, 1] -->
<!-- column: 0 -->
<!-- pause -->
### GenAI
* **Główna funkcja:** Tworzenie nowych treści (tekst, kod, obrazy, wideo)
* **Tryb pracy:** Reaktywny (czeka na prompt/polecenie użytkownika)
* **Interakcja:** Zazwyczaj krótka, jednoetapowa (Q&A)
* **Autonomia:** Niska; wymaga ciągłego nadzoru człowieka
* **Przykład:** Napisz e-mail, stwórz grafikę, podsumuj dokument
* **Rola:** Narzędzie zwiększające produktywność
<!-- column: 1 -->
<!-- pause -->
### Agentic AI
* **Główna funkcja:** Podejmowanie działań i realizacja złożonych zadań
* **Tryb pracy:** Proaktywny (działa samodzielnie po otrzymaniu celu)
* **Interakcja:** Długotrwała, wieloetapowe planowanie i rozumowanie
* **Autonomia:** Wysoka; podejmuje decyzje i koryguje działanie
* **Przykład:** *Zaplanuj podróż służbową*, co oznacza: znalezienie lotu, rezerwację hotelu, wpisanie do kalendarza
* **Rola:** Autonomiczny wykonawca procesów
<!-- reset_layout -->
<!-- pause -->
> Google zmieniło nazwę serwisu Vertex AI na Gemini Enterprise Agent Platform by odzwierciedlić powyższe,
> a AWS stworzył zupełnie nowy serwis Amazon Bedrock AgentCore do orkiestracji agentów.
<!-- end_slide -->
<!-- end_slide -->

<!-- column_layout: [2, 2] -->

<!-- column: 0 -->
<!-- jump_to_middle -->

# Dziękuję!

## 🌐 www.trek2summit.com
## 🌐 linkedin.com/company/trek2summit
## 🤝 linkedin.com/in/rafal-krol
### 🛠️ kiro.dev
### 🛠️ github.com/rafalkrol-xyz/mAI-consigliere

# Pytania?

<!-- column: 1 -->
![image:width:100%](./images/coffee_talk.jpeg)
