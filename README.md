# dds-python-wektory-2024-2025

Repozytorium z materiałami z kursu [Dane Przestrzenne w Pythonie - wektory](https://www.youtube.com/playlist?list=PLDiotiqXJ72UjlnpDEVsTx-C1ICsGdMyP) z kanału YT Dolina Data Science.

Struktura katalogów:

- materials
  - l4.1
    - ...
  - l4.2
    - ...
  - l5.1
  - l5.2
  - l6
- LICENSE - plik z licencją
- README.md - czytasz ten plik
- requirements.txt - plik z zależnościami

## Instalacja - lokalnie

### Klonowanie repozytorium

```shell
git clone https://github.com/SimonMolinsky/dds-python-wektory-2024-2025.git
```

### Środowisko conda - stworzenie

```shell
conda create -n dds Python="3.10"
```

### Aktywacja conda

```shell
conda activate dds
```

### Instalacja zależności

```shell
conda install -c conda-forge --file requirements.txt
```

## Uruchomienie lokalne

### Aktywuj conda jeśli środowisko nie jest aktywne

```shell
conda activate dds
```

### Włącz notatnik

```shell
jupyter-notebook
```

Otworzy się okno w którym możesz wyszukać notatniki z repozytorium i utworzyć nowy, własny notatnik.

## Google Colab

Jeśli korzystasz z Google Colab to nie musisz przechodzić przez wszystkie w/w kroki. W pierwszej komórce notatnika `Colab` wpisz tylko:

```shell
!pip install mapclassify
```

Pozostałe paczki są zainstalowane domyślnie. Dane przerzuć na swój Google Drive, kliknij na ikonę katalogu po lewej stronie, po czym kliknij na ikonę katalogu z symbolem Google Drive która pojawiła się u góry zakładki. Połącz się z dyskiem i znajdź pliki statyczne - klikając na trzy kropki możesz pobrać ścieżki do tych plików i używać ich jak normalnych ścieżek w lokalnym systemie.
