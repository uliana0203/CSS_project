# Аналіз російських Телеграм-каналів

Це Git репозиторій для проекту з аналізу даних з російських каналів у Telegram в рамках курсу з Обчислювального суспільствознавства у Українському Католицькому Університеті.

Даний проект присвячений аналізу збірки даних, отриманих від російських каналів у Telegram в рамках курсу з обчислювальних соціальних наук у Українському Католицькому Університеті. Дані були надані лектором курсу.

## Вимоги перед запуском

Для коректної роботи проекту потрібно встановити наступні бібліотеки та інструменти:

- Python 3.10
- PySpark
- NetworkX
- PyVis
- TextBlob
- datetime
- pandas
- numpy
- re
- matplotlib
- seaborn

## Використання

1. **Запуск аналізу даних:**
   - Запустіть Jupyter Notebook або Python скрипти для проведення аналізу даних.
  
2. **Візуалізація мережі:**
   - Використовуйте бібліотеку NetworkX та PyVis для візуалізації комунікацій між телеграм каналами.

3. **Аналіз емоційності тексту:**
   - Запустіть Python скрипт для аналізу емоційності текстів з використанням бібліотеки TextBlob.
  
## Структура даних

Датасет містить наступні колонки з даними:

- `id`: унікальний ідентифікатор для кожного повідомлення.
- `date`: дата написання повідомлення.
- `views`: кількість переглядів для кожного повідомлення.
- `reactions`: реакції, які були поставлені на повідомлення (додано починаючи з 2021 року).
- `to_id`: колонка, яка показує кому було відправлено повідомлення (id каналу).
- `fwd_from`: якщо повідомлення було переслане, то в колонці вказується id від кого.
- `message`: саме повідомлення.
- `type`: тип повідомлення (текст, фото, відео, аудіо).
- `duration`: якщо повідомлення аудіо чи відео формату, то тут буде вказана його тривалість.
- `frw_from_title`: назва каналу.
- `frw_from_name`: назва каналу звідки переслане повідомлення.
- `msg_entity`: не зовсім зрозуміло, в описі вказано, що колонка не містить корисної інформації і може бути видалена.

## Висновки

У цьому проекті ми дослідили різні аспекти російських Телеграм-каналів, вивчаючи їхні комунікаційні зв'язки, розподіл постів за часом, використання хештегів та емоційність текстів. Висновки можна знайти у відповідній частині Jupyter Notebook.

## Автор

- Збежховська Уляна



