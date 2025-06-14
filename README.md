# Panic Disorder Project
Projekt został wykonany na zajęcia z przedmiotu Metody walidacji modeli statystycznych. Problematyka projektu obejmuje klasyfikację pacjentów w celu postawienia diagnozy, czy u danej osoby występuje zespół lęku napadowego (ang. panic disorder).

Utworzony model klasyfikacyjny może stanowić wsparcie pakistańskich lekarzy psychiatrów z Kliniki Ayeshy w podejmowaniu lepszych decyzji nt. diagnozy pozytywnej lub negatywnej występowania u pacjenta zespołu lęku napadowego.

## Zbiór danych
Zbiór danych wykorzystany w projekcie został pobrany ze strony Kaggle: https://www.kaggle.com/datasets/muhammadshahidazeem/panic-disorder-detection-dataset/data.
Zawiera on łącznie 120 000 rekordów pacjentów (100 000 rekordów w zbiorze zatytułowanym jako treningowy oraz 20 000 rekordów w zbiorze zatytułowanym jako testowy). W zbiorze znajduje się 17 zmiennych, z czego ostatnia dotyczy wystąpienia u pacjenta zespołu lęku napadowego. Dane zostały zebrane przez Muhammada Shahida Azeema, wykładowcę informatyki (ang. Computer Science) z Departamentu Szkolnictwa Wyższego Pendżab w Pakistanie (ang. Higher Education Department Punjab Pakistan), na podstawie analizy dokumentów z kliniki Ayeshy (ang. Ayesha Clinic).

## Etapy pracy
Kolejne etapy pracy nad projektem obejmowały:
1. Przeprowadzenie opisu zbioru badawczego
2. Wstępne przygotowanie danych
3. Selekcję cech (Filter methods)
4. Przygotowanie danych (Preprocessing)
5. Określenie modeli (utworzenie przepływu pracy)
6. Tuning modeli
7. Ewaluację modeli
8. Wyciągnięcie wniosków

Kolejne etapy pracy nad projektem zostały szczegółowo opisane w pliku Panic_Disorder_Project.html oraz Panic_Disorder_Project.qmd.

## Dalsze kierunki rozwoju
W każdym projekcie znajduje się przestrzeń na wprowadzenie ulepszeń. W tym projekcie warto byłoby w przyszłości pozyskać dane z innych klinik zajmujących się diagnostyką i leczeniem zespołu lęku napadowego, aby móc generalizować wyniki na szerszą populację. Pozwoliłoby to na sprawdzenie, czy zespół lęku napadowego objawia się podobnie w różnych miejsach na świecie i czy utworzone modele byłyby przydatne w diagnostyce. Gdyby wyniki okazały się dalekie od satysfakcjonujących, można byłoby powtórzyć proces modelowania w celu utworzenia modeli diagnostycznych dla każdego kraju lub kliniki oddzielnie.

## Informacje dodatkowe
W repozytorium znajdują się pliki:

Panic_Disorder_Project.html - plik html w formie raportu, obejmujący tekst i wizualizacje, bez kodu,
Panic_Disorder_Project.qmd - plik z kodem projektu,
race_results_grid20.RDS - wyniki uzyskane po tuningu modeli metodą wyścigów,
trained_model_boost.rds - najlepszy model XGBoost (uzyskany po treningu z najlepszymi wartościami hiperparametrów wybranymi podczas tuningu),
trained_model_nnet.rds - najlepszy model sieci neuronowej (uzyskany po treningu z najlepszymi wartościami hiperparametrów wybranymi podczas tuningu),
Panic_Project_dataset_info_Polish - informacje o zbiorze danych w języku polskim.
____________________________________________________________________________________________________________________________
Autorem projektu jest Faustyna Smarzewska, studentka kierunku IAD II st. Politechniki Lubelskiej w roku akademickim 2024/25.
