<p align="center">
  <img src="logo.png" width="128" alt="TopaZ Editing Pro 26">
</p>

<h1 align="center">TopaZ Editing Pro 26</h1>

<p align="center">
  Edytor wideo dla Windows w stylu Premiere Pro, z silnikiem GPU.<br>
  <b>Windows 10 / 11 (64-bit)</b> · wersja <b>26.1</b>
</p>

<p align="center">
  <a href="https://github.com/TopaZ-Hub/TopaZ-HUB"><b>⬇️ Zainstaluj przez TopaZ Creative Hub (zalecane)</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/TopaZ-Hub/TopaZ-Editing-Pro/releases/latest">Pobierz instalator bezpośrednio</a>
</p>

---

## ✨ Co potrafi

**Montaż**
- Wielościeżkowa oś czasu (wideo i audio) z przyciąganiem, połączonymi klipami i znacznikami.
- Narzędzia jak w Premiere: Zaznaczanie, Ripple, Żyletka, Poślizg, Pióro, Tekst.
- **Ctrl+klik** zaznacza pojedynczy klip, więc usuniesz samo audio i zostawisz wideo.
- Monitor źródła i programu, punkty In/Out, wstawianie i nadpisywanie, szybkość klipu.
- Klatki kluczowe z interpolacją dla ruchu, krycia i parametrów efektów.

**Efekty i kolor**
- **90+ efektów wideo** w 15 folderach: rozmycia, zniekształcenia, VHS, glitch, green screen, stylizacja, zaokrąglone rogi i inne.
- **23 efekty audio**: pogłos, kompresor, korektor, echo, chorus, efekt telefonu i inne.
- **30+ przejść**, gotowe ustawienia (Ken Burns, obraz w obrazie, styl kinowy) i ulubione.
- Korekcja kolorów **Lumetri**: balans bieli, krzywe tonalne, gotowe wyglądy, winieta, zakresy.
- Tytuły, napisy i grafika animowana.

**Eksport**
- Kodowanie sprzętowe na karcie graficznej: **AMD AMF, NVIDIA NVENC, Intel Quick Sync**.
- **H.264, H.265 (HEVC) i AV1**, od 720p do **4K i 8K**, 23,976–120 kl./s.
- Gotowe ustawienia dla YouTube, TikToka, Instagrama i Discorda (wybierasz docelowy rozmiar w MB).

**Wydajność**
- Cały obraz liczy się na GPU (WebGL 2), więc podgląd jest płynny i nie robi się czarny.
- W Preferencjach (`Ctrl+,`) wybierasz GPU albo CPU, kartę graficzną, przydział RAM-u i jakość podglądu.

## 📥 Instalacja

### Sposób 1: przez TopaZ Creative Hub (zalecany)

Hub sam zainstaluje program i będzie go aktualizował jednym kliknięciem.

1. Pobierz Hub z repozytorium **[TopaZ-HUB](https://github.com/TopaZ-Hub/TopaZ-HUB)**.
2. W Hubie kliknij **„Zainstaluj”** przy TopaZ Editing Pro 26.

### Sposób 2: ręcznie

1. Wejdź w **[Releases](https://github.com/TopaZ-Hub/TopaZ-Editing-Pro/releases/latest)**.
2. Pobierz `TopaZ_Editing_Pro_26.1_Setup.exe` i uruchom go.

Aktualizacja wgrywa się na starszą wersję. Twoje projekty i ustawienia zostają.

## ⚠️ Czerwone okno „System Windows ochronił ten komputer”

Przy uruchamianiu instalatora Windows może pokazać czerwone ostrzeżenie. **To nie znaczy, że wykryto wirusa.** Pojawia się, bo:

- program **nie ma płatnego certyfikatu podpisu cyfrowego** (stąd napis „Nieznany wydawca”). Taki certyfikat kosztuje kilkaset złotych rocznie, a TopaZ to mały, niezależny projekt;
- plik jest **nowy i pobrało go jeszcze niewiele osób**. Windows ufa plikom stopniowo, w miarę jak uruchamia je więcej ludzi.

Kliknij **„Więcej informacji” → „Uruchom mimo to”**. Jeśli instalujesz przez Hub, okno pokaże się tylko raz, przy instalacji samego Huba.

### Sprawdź sam

Nie musisz wierzyć na słowo:

1. **VirusTotal**: wrzuć instalator na [virustotal.com](https://www.virustotal.com). Sprawdzi go ponad 60 antywirusów naraz.
2. **Suma kontrolna**: upewnij się, że plik nie został podmieniony. W PowerShellu wpisz:

   ```powershell
   Get-FileHash .\TopaZ_Editing_Pro_26.1_Setup.exe -Algorithm SHA256
   ```

   Wynik musi być taki sam jak ten:

   ```
   9CCCE65F56323AFC134A173B5CB1CA8CDF2FC059CDBD80BD0E17A24BD60A7932
   ```

**Prywatność:** program działa w całości na Twoim komputerze. Twoje filmy i projekty nigdy nie są wysyłane do internetu, nie ma reklam ani zbierania danych. Odinstalujesz go normalnie: **Ustawienia → Aplikacje**.

## 💻 Wymagania

| | Minimalne | Zalecane |
|---|---|---|
| System | Windows 10 64-bit | Windows 11 64-bit |
| Procesor | 4 rdzenie | 6+ rdzeni (np. Ryzen 5 5600X) |
| RAM | 8 GB | 16 GB+ |
| Karta graficzna | zgodna z DirectX 11 | AMD RX 6000 / NVIDIA RTX / Intel Arc |
| Dysk | ok. 300 MB na program | dysk SSD na projekty |

Do kodowania H.265 i AV1 potrzebna jest karta, która je obsługuje sprzętowo. Jeśli Twoja nie obsługuje, wybierz H.264.

## 📝 Co nowego w 26.1

- Nowy silnik GPU. Podgląd nie robi się czarny i się nie zacina.
- Eksport nawet kilkadziesiąt razy szybszy dzięki kodowaniu sprzętowemu.
- Nowe rozdzielczości 2K, 4K, 8K, formaty pionowe i kwadratowe, kodeki H.265 i AV1.
- Panel efektów jak w Premiere: 90+ efektów wideo, 23 audio, 30+ przejść, ustawienia wstępne.
- Preferencje: wybór GPU lub CPU, przydział RAM-u, jakość podglądu.
- Ctrl+klik i „Usuń tylko audio / tylko wideo”.
- Poprawiona obsługa pionowych filmów z telefonu.

Pełna lista zmian jest w zakładce **[Releases](https://github.com/TopaZ-Hub/TopaZ-Editing-Pro/releases)**.

## 🐞 Zgłaszanie błędów

Coś nie działa? Załóż zgłoszenie w zakładce **[Issues](https://github.com/TopaZ-Hub/TopaZ-Editing-Pro/issues)**. Napisz:
- co robiłeś, gdy pojawił się błąd;
- jaką masz kartę graficzną;
- z jakiego aparatu lub telefonu jest nagranie.

Zrzut ekranu bardzo pomaga.

---

> ℹ️ Plik `manifest.json` w tym repozytorium to lista wersji, z której korzysta TopaZ Creative Hub. Nie usuwaj go i nie zmieniaj jego nazwy, bo inaczej Hub przestanie widzieć aktualizacje.

<p align="center"><sub>© 2026 TopaZ · Projekt niezależny, niezwiązany z Adobe ani Microsoft.</sub></p>
