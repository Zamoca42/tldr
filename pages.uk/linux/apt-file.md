# apt-file

> Пошук файлів в пакетах `apt`, включно з тими, що ще не встановлені.
> Більше інформації: <https://manned.org/apt-file.1>.

- Оновити базу метаданих:

`sudo apt update`

- Пошук пакетів, які містять вказаний файл або шлях:

`apt-file {{search|find}} {{частковий_шлях/до/файлу}}`

- Список вмісту конкретного пакета:

`apt-file {{show|list}} {{пакет}}`

- Пошук пакетів, які відповідають `регулярному_виразу`:

`apt-file {{search|find}} --regexp {{регулярний_вираз}}`
