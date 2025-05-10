# FoodVision101

- **Autor:** Igor Bartkowski
- **Kierunek:** Data Scientist. Analityk Danych
- **Uczelnia:** WSB Merito Gdańsk
- **Promotor:** Dr Krzysztof Ziółkowski
- **Data:** Maj 2025

---

## Cel projektu

Celem projektu FoodVision101 jest stworzenie modelu klasyfikującego obrazy jedzenia z wykorzystaniem transfer learningu w TensorFlow. Model został wytrenowany na 10% danych z zestawu Food101, zawierającego 101 kategorii dań.

Zastosowanie wcześniej wytrenowanych konwolucyjnych sieci neuronowych (np. EfficientNet) umożliwiło skuteczne dostosowanie modelu do zadania klasyfikacji bez potrzeby trenowania od zera.

Projekt powstał w ramach pracy dyplomowej i stanowi praktyczne zastosowanie metod uczenia maszynowego w obszarze computer vision.

---

## Zawartość repozytorium

- `FoodVision101.ipynb` – główny notebook projektu
- `helper_functions.py` – plik z własnymi funkcjami pomocniczymi
- `custom_food_images` - folder z customowymi zdjęciami jedzenia 
- `requirements.txt` – lista wymaganych bibliotek

---

## Uruchamianie projektu

Aby uruchomić projekt lokalnie:

```bash
git clone https://github.com/devozik/FoodVision101.git
cd FoodVision101
pip install -r requirements.txt
Przejdź krok po kroku przez plik FoodVision101.ipynb