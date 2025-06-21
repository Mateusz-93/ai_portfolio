<h1 align="center" style="margin-bottom: 0.2em;">🖋️ <strong>MrEchoScribe</strong> 🎬</h1>
<h2 align="center" style="margin-top: 0;">Twój dżentelmen od napisów filmowych</h2>

---

<h4 align="center" style="margin-top: 2em; margin-bottom: 0;">To inteligentny asystent, który z gracją i precyzją zamienia dźwięk z filmu na tekst.</h4>
<h4 align="center" style="margin-top: 0.2em;">On już wie, co robić!</h4>

---

<div style="text-align: center;">
  <a href="https://mr-echo-scribe.streamlit.app/" class="md-button md-button--primary" target="_blank">Zobacz aplikację w nowej karcie</a>
</div>

---

## 🧠 Co potrafi?

1. **Wideo? Poproszę!** – przeciągnij plik (MP4, MPEG4, do 200 MB) i wrzuć go do eleganckiego drop-zone’u.
2. **Wyodrębnij audio** – film to nie tylko obraz. MrEchoScribe wydzieli z niego samą ścieżkę dźwiękową.
3. **Transkrybuj audio** – tekst z dźwięku, błyskawicznie i dokładnie. Dzięki AI, ale z ludzką jakością.
4. **Edytuj** – masz pełną kontrolę. Popraw, dopisz, przesuń. Napisy są Twoje.
5. **Zapisz i pobierz** – napisy w formacie `.srt` i audio w `.mp3` gotowe do pobrania jednym kliknięciem.

---

## 🎯 Dla kogo?

Dla filmowców, twórców internetowych, edukatorów, tłumaczy, montażystów – wszystkich, którzy chcą, by ich treść była czytelna, dostępna i gotowa na więcej.

---

<h3 align="center">MrEchoScribe – bo każde echo zasługuje na swój zapis.</h3>

---

## 🛠️ **Technologie**
- **Python** – główny język aplikacji: logika, przetwarzanie dźwięku, integracje API
- **Streamlit** – szybki framework do budowy aplikacji webowych opartych na Pythonie
- **OpenAI API (Whisper)** – automatyczna transkrypcja mowy do formatu `.srt`
- **Pydub** – ekstrakcja i konwersja ścieżki dźwiękowej z pliku wideo do formatu `.mp3`
- **hashlib / base64 / io** – narzędzia pomocnicze do identyfikacji plików, pracy z buforami i osadzania obrazów
- **Qdrant Client** – klient bazy wektorowej (w projekcie obecny jako komponent przyszłościowy)
- **dotenv** – bezpieczne wczytywanie danych konfiguracyjnych (np. kluczy API)

---

## 🔑 Wymagania
- **Klucz API OpenAI** – to Twoja wejściówka do świata transkrypcji. Wprowadź go, a MrEchoScribe zacznie działać.

---

## 🎬 Jak to działa?

### 1. Wprowadź swój klucz API OpenAI  
To pierwszy krok. Bez niego MrEchoScribe nie ruszy w świat dźwięków.

![Wprowadź API](mr_echo_1.png)

---

### 2. Przeciągnij plik wideo (drag & drop)  
Załaduj film w formacie MP4/MPEG4 (do 200MB). Możesz zmienić plik w dowolnym momencie.

![Upload wideo](mr_echo_2.png)

---

### 3. Wyodrębnij audio  
Kliknij „Wyodrębnij audio”, a MrEchoScribe z gracją oddzieli dźwięk od obrazu.

![Wyodrębnij audio](mr_echo_3.png)

---

### 4. Transkrybuj audio / Edytuj napisy
Teraz czas na magię AI. Kliknij „Transkrybuj audio”, a pojawią się napisy – gotowe do edycji.

Nie jesteś zdany tylko na maszynę. Możesz poprawić, dopisać lub przestawić tekst przed zapisaniem.
![Transkrypcja](mr_echo_4.png)

---

### 5. Zapisz i pobierz  
Zadowolony? Zapisz transkrypcję, a następnie pobierz gotowe pliki:  
🎞️ Napisy `.srt`  
🎧 Audio `.mp3`

![Pobieranie](mr_echo_5.png)

---

#### 🎉 Gotowe!
Twój film ma już głos i tekst – elegancko zsynchronizowane.

---

<div style="text-align: center; font-size: 0.85em; color: #999; margin-top: 3em;">
  <em>Utworzono: 2025-06-21</em><br>
  © 2025 Mateusz Wilczewski
</div>

---