---
layout: post
title: "Podświetlanie Kodu w Jekyllu – Test"
date: 2025-11-20 00:00:00 +0100
categories: [programowanie, jekyll]
tags: [markdown, code, tutorial]
---
layout: post title: "🚀 Stwórz Swój Techniczny Blog w 1 Minutę! (GitHub Pages + Jekyll)" date: 2025-11-21 00:00:00 +0100 categories: [tutorial, github, jekyll] tags: [blogowanie, programowanie, github-pages, szybki-start]

Uruchom własnego, darmowego bloga technicznego w mniej niż minutę, wykorzystując GitHub Pages i Jekyll — idealne rozwiązanie do prezentowania kodu!

Krok 1: Repozytorium

Zaloguj się na GitHub.
Utwórz nowe, Publiczne repozytorium o nazwie: username.github.io.
Adres URL: Twoja strona będzie dostępna pod adresem: https://username.github.io.

Krok 2: Konfiguracja (_config.yml)

W głównym katalogu utwórz plik _config.yml z minimalną konfiguracją i włączonym podświetlaniem składni (Syntax Highlighting):

```yaml

Ustawienia Podstawowe

title: Mój Blog description: Blog techniczny na GitHub Pages. url: "https://TWOJA_NAZWA.github.io"

Ustawienia Jekyll

remote_theme: jekyll/minima markdown: kramdown

Włącz podświetlanie kodu

kramdown: syntax_highlighter_opts: block: css: class ``` Zatwierdź (Commit) ten plik.

Krok 3: Dodanie Posta

Utwórz katalog _posts.
Wewnątrz dodaj plik RRRR-MM-DD-witaj-swiecie-kodowania.md.
Wklej do niego szablon posta z sekcją Front Matter i blokami kodu:

```markdown

layout: post title: "Witaj Świecie Kodowania!" date: 2025-11-21 00:00:00 +0100 categories: [test, start]

Pierwszy post! Oto przykład kodu z automatycznym podświetlaniem składni:

```python

Prosty przykład Pythona

def hello_world(): print("Gratulacje, Twój blog działa!") hello_world() ``` ```

Krok 4: Opublikowanie

Zatwierdź wszystkie zmiany. GitHub Pages automatycznie zbuduje Twoją stronę. Odwiedź adres https://username.github.io w ciągu około 60 sekund. Gotowe!
