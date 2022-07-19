# Recruitment Task Custommerce

Zadanie rekrutacyjne na stanowisko Front-end developera

Materiał referencyjny:
https://xd.adobe.com/view/690ceadd-d8d0-4459-98fa-414be9814006-3c5f/specs/

Dla twojej wygody możesz skorzystać z rozpoczętego juz kodu lub stworzyć własny.

Projekt zbudowany jest pod SCSS, jednak zadanie możesz wykonać w CSS.


### Zadanie:
Sklonuj repozytorium i wykonaj reprezentacje projektu graficznego za pomocą HTML i CSS. 

Gotowy projekt wyślij mailowo jako plik `.zip` na oba adresy:

* tomasz.draber@custommerce.pl
* jordan.andrzejczak@custommerce.pl


W razie jakichkolwiek pytań technicznych wyślij zapytanie mailowe.


### Wymagania:
* Stwórz odpowiednią strukturę pliku HTML oraz ostyluj go zgodnie z powyższym projektem możliwie 1 do 1,
* Nie używaj JavaScriptu,
* Zadbaj o responsywność karty (najlepiej do 320px szerokości ekranu),
* Maksymalna szerokość kontenera - dla potrzeb tego zadania niech będzie to 1440px,
* Nagłówki pisz czcionką Montserrat, teksty (copy) - Open Sans,
* W pliku Adobe XD pamiętaj o widoku deweloperskim, uzyskasz dostęp do treści oraz poglądowych styli i wymiarów elementów,
* Wykonaj animację bloków sekcji "Co nas wyróżnia", zastosuj alternatywną wersję dla urządzeń mobilnych,
* Struktura klas powinna funkcjonować na zasadzie drzewa, zawsze dzedziczyć od ojca, w tym przypadku `cm-custommerce-product`,
* Maksymalna ilość znaków to 64 000,
* Zwróć uwagę na estetykę kodu, nie twórz niepotrzebnych zagnieżdzeń,
* Nie zostawiaj samotnych spójników na końcach linii, używaj twardej spacji `&nbsp;` (np. z i u o),
* Wypisz problemy jakie napotkałeś podczas tworzenia karty produktowej.


### Dodatkowe informacje:

- Uważaj na overflow sekcji,
- Jeśli nie musisz, nie stosuj Media queries,
- Nie stosuj identyfikatorów elementów np. `<div id="cm-ico-1">`, używaj klas
- Dozwolone jest używanie znaczników semantycznych HTML5

Skorzystaj z preprocesora SCSS takiego jak Live Sass Compiler

Ustawienia dla przyspieszenia działania:

```    "liveSassCompile.settings.generateMap": false,
    "liveSassCompile.settings.excludeList": [
    
    "/node_modules/", ".vscode/**"],
    "liveSassCompile.settings.formats": [

      {
        "format": "expanded",
        "extensionName": ".css",
        "savePath": "~../css/"
      }
    ],
```