# Лабораторная работа №1
Для запуска работы потребуется:
- Docker Desktop
- VS Code 
- Git
1. Склонируйте проект:
- git clone https://github.com/dimansipl/sobd
2. Скачайте датасет:
- https://www.kaggle.com/datasets/coni57/f1-2020-race-data?select=ParticipantData_17192138584092610649.csv
(Размер 12.32 ГБ)
3. Расспакуйте архив в папку notebooks/ 
Используются только файлы TelemetryData_*.csv, поэтому можете скопировать только их или же удалить в папке notebooks/
Так же можно удалить из папки командами (через Git Bash или Linux):

- rm -f SessionData_*.csv
- rm -f ParticipantData_*.csv
- rm -f RaceTimeData_*.csv

4. Запусти:
- docker compose up -d
5. Открой Visual Code
