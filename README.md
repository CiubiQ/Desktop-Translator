# Screen Translator

**Screen Translator** to aplikacja desktopowa, która umożliwia użytkownikom przechwytywanie wybranego obszaru ekranu, wyodrębnianie tekstu z obrazu za pomocą technologii OCR (Optical Character Recognition) i tłumaczenie go na wybrany język. Narzędzie to jest idealne do tłumaczenia tekstu widocznego na ekranie, takiego jak obrazy, filmy czy inne treści, których nie można łatwo skopiować.

## Funkcje
- Łatwe przechwytywanie wybranego obszaru ekranu.
- Wyodrębnianie tekstu z obrazów za pomocą OCR.
- Tłumaczenie wyodrębnionego tekstu na wybrany język.
- Przyjazny interfejs użytkownika, który pozostaje na wierzchu innych okien.
- Lekka i wydajna konstrukcja.

## Użyte technologie
- **C#** z **WPF** do tworzenia interfejsu graficznego.
- **Tesseract.NET** do rozpoznawania tekstu (OCR).
- **Google Translate API** lub **MyMemory API** do tłumaczenia.
- **System.Drawing** do przechwytywania ekranu.

## Wymagania wstępne
Aby uruchomić ten projekt, upewnij się, że masz zainstalowane:
- [.NET Framework](https://dotnet.microsoft.com/download) (wersja 4.7.2 lub wyższa).
- [Visual Studio](https://visualstudio.microsoft.com/) (Community Edition lub wyższe) do budowania projektu.
- [Git](https://git-scm.com/) do klonowania repozytorium.

## Instrukcje konfiguracji

Postępuj zgodnie z poniższymi krokami, aby skonfigurować projekt na swoim komputerze:

### 1. Sklonuj repozytorium
Sklonuj projekt na swój lokalny system za pomocą poniższego polecenia:
```bash
git clone https://github.com/yourusername/ScreenTranslator.git
cd ScreenTranslator

