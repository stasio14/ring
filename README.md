# Bot do Discorda klasy 2E PLOPŁ
[![](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/downloads/release/python-378/) [![](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)

##Instalacja:
1. ```git clone https://github.com/stasio14/ring```
2. Uruchom cmd; ```cd folderPath```
3. Upewnij się, że posiadasz skonfigurowanego Pythona
4. ```pip install -r requirements.txt```
5. Podstaw token w pliku `secrets.py`
6. ```python bot1.py```

##Komendy bota
**Ogólne**
`//trans <lang> fraza` - przetłumaczenie frazy (język wykrywany automatycznie) na podany
`//ru fraza` - tłumaczenie frazy (język wyjrywany automatycznie) na język rosyjski
`//grant <perm> <@użytkownik>` - nadanie uprawnienia dla użytkownika (głosowanie)
- daje uprawnienie kategorii _user_
`//ungrant <perm> <@użytkownik>` - odebranie uprawnienia dla użytkownika (głosowanie)
- próba odebrania uprawnienia kategorii _admin_ skutkuje komunikatem o błędzie

**Dla osób z uprawnieniami**
`//ring` - Dołączenie do kanału autora; włączenie sygnału; opuszczenie kanału
`//volume <volume>` - zmiana głośności bota
`//grant <perm> <@użytkownik>` - nadanie uprawnienia dla użytkownika
- _admin_ daje uprawnienia _admin_
- _user_ daje uprawnienia _user_
`//ungrant <perm> <@użytkownik>` - odebranie uprawnienia dla użytkownika
- _user_ może odebrać tylko uprawnienie _user_ (inaczej błąd)

## Dzienik zmian

### 1.4.3
**Zmiany**
- zgoda admina na przyznawanie uprawnień
- release

### 1.4.2
**Zmiany**
- Zmiana struktury pliku `perms.json`
- Uporządkowanie przyznawania uprawnień
- Zgoda admina na odbieranie uprawnień
- Zmiana odpowiedzi na komendę `perms`

**Do zrobienia**
- Dostosowanie komendy `grant`
- Utworzenie nowej komendy do zmiany minimum głosów
- komenda do sprawdzenia osób z uprawnieniami admina
- systematyczniej prowadzić README
- utworzyć _release_

### 1.4.0
**Zmiany**
- Dodanie głosowania przy przyznawaniu uprawnienia `grant`
- użycie elementu `discord.Embed`

**Problemy**
- za mało adminofaszyzmu

### 1.3.1
**Zmiany**
- Rozdzielenie komendy `trans` do `ru`
- Zmiana prefixu bota

### 1.3.0
**Zmiany**
- komendy ```trans```
- skrócenie trwania dzwonka do 3 sekund

**Problemy**
- błędy Google API

### 1.2.1
**Zmiany**
- dodanie opisów

### 1.2.0
**Zmiany**
- komendy ```grant``` i ```ungrant```
- komenda ```perms```

**Problemy**
- brak opisów
- adminofaszyzm

### 1.1.0
**Zmiany**
- próba komendy ```volume```
- usunięcie komendy ```stop```

**Problemy**
- zarządzanie botem

### 1.0.0
**Zmiany**
- komenda ```ring```
- komenda ```stop```

**Problemy**
- problemy z dołączaniem do kanału
- nie działająca komenda stop
- brak opuszczania kanału

❤ Specjalne podziękowanie dla @michkied za inspirację w tworzeniu głosowania
