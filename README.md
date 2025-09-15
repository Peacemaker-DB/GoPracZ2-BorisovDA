# Практическое задание № 2 Борисов Денис Александрович ЭФМО-01-25

Цели:

* Понять назначение ключевых директорий (cmd/, internal/, pkg/ и др.).
* Научиться раскладывать код и артефакты проекта по «правильным» местам.
* Собрать минимальный скелет проекта и запустить «пустой» main.go.

Выполнение работы:

1. Создаём скелет проекта

В ходе работы над практической работой были созданы следующий скелет проекта:

<img width="318" height="280" alt="image" src="https://github.com/user-attachments/assets/071c2259-81f8-467a-a879-6423f8f24b29" />

После был написан работающий сервис сервис с двумя ручками: / (текст) и /ping (JSON).

Код для app.go:

<img width="675" height="943" alt="image" src="https://github.com/user-attachments/assets/0c16744e-8f6d-4621-8df2-045044285f23" />

2. Запуск и быстрая проверка

После был запущен сервер и проверен в браузере:

<img width="1918" height="719" alt="image" src="https://github.com/user-attachments/assets/29276571-1443-421f-b5cf-9bfab3d31b4d" />

Затем был собран бинарный файл:

<img width="1453" height="680" alt="image" src="https://github.com/user-attachments/assets/a4b0cf8a-5680-42a3-b9c7-e39177474002" />

3. Мини-упражнения

Упр. А — Request-ID и улучшение логов

Для выполнения упражнения был дополнен код в logger.go:

<img width="617" height="660" alt="image" src="https://github.com/user-attachments/assets/ce050832-6a4e-4b31-b715-8604f722b496" />

а также была добавлена middleware-обёртка в app.go:

<img width="582" height="205" alt="image" src="https://github.com/user-attachments/assets/f7ab96e3-304d-4157-ba4a-756a50bdc7c5" />

После была сделана проверка:

<img width="599" height="223" alt="image" src="https://github.com/user-attachments/assets/22cf85ed-f652-4d0e-afbf-0acb8acfce5c" />

Упр. B — Единый формат JSON-ошибок

Для выполнения упражнения был дополнен скелет проекта:

<img width="258" height="272" alt="image" src="https://github.com/user-attachments/assets/dd2a4347-257f-461a-8fbe-6e1c69d382b5" />

И была написана утилита для ответов в JSON:

<img width="959" height="494" alt="image" src="https://github.com/user-attachments/assets/5b74b959-3f1f-49e5-b6e4-0f44be6598d5" />

После была сделана проверка:

<img width="687" height="159" alt="image" src="https://github.com/user-attachments/assets/08534cca-d230-448b-8645-e1ebd468ff06" />

Упр. C — Разделение обработчиков

Для выполнения упражнения был дополнен скелет проекта:

<img width="157" height="302" alt="image" src="https://github.com/user-attachments/assets/6242287e-98cb-4c9a-904a-dee0ee5b0c38" />

И был создан файл ping.go, где реализован хендлер:

<img width="613" height="484" alt="image" src="https://github.com/user-attachments/assets/5bf9a4a4-d698-4b1a-8a09-8fcea05a1f99" />

4. VS Code — удобные мелочи

После выполнения практической работы было включено форматирование при сохранении, а также создан tasks.json:

<img width="534" height="315" alt="image" src="https://github.com/user-attachments/assets/03375496-f1c0-4d03-9d51-64809b21ff8a" />
