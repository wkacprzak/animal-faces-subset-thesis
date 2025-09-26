# Animal Faces Subset – PCA Dataset

Repozytorium zawiera okrojony fragment zbioru **Animal Faces** z Kaggle, użyty w pracy dyplomowej:

*"Wpływ analizy składowych głównych na skuteczność rozpoznawania wzorców przy pomocy sieci neuronowych"*.

## Zawartość

Folder główny: `PetImages/`  

Struktura podfolderów:

- `train_small/` – dane treningowe (klasy: `cat` i `dog`)  
- `test_small/` – dane testowe (klasy: `cat` i `dog`)  
- `train_small_90/`, `test_small_90/` – warianty po kompresji metodą PCA zachowujące 90% wariancji  
- `train_small_95/`, `test_small_95/` – warianty po kompresji metodą PCA zachowujące 95% wariancji  

Każdy folder zawiera podfoldery dla klas (`cat`, `dog`). Dane są przygotowane do uczenia modeli CNN i porównywania wpływu redukcji wymiarowości metodą PCA na skuteczność klasyfikacji.

## Cel repozytorium

Repozytorium zawiera **subset danych przygotowany do celów edukacyjnych i badawczych**. Umożliwia:

- odtworzenie eksperymentów z wykorzystaniem CNN,  
- testowanie wpływu redukcji wymiarowości PCA na dokładność modeli,  
- porównanie wyników dla różnych wariantów danych (oryginalne i po PCA).

## Licencja / Zasady użycia

Dane pochodzą z publicznego zbioru **Animal Faces** ([Kaggle](https://www.kaggle.com/datasets/andrewmvd/animal-faces)) i zostały ręcznie okrojone oraz przetworzone do celów edukacyjnych i badawczych związanych z pracą dyplomową.

Repozytorium może być wykorzystywane **wyłącznie do celów edukacyjnych i naukowych**.
