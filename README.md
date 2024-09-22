# RAG-Assistant: Диалоговая система для вопросов о знаменитостях

## Обзор проекта

Этот проект представляет Retrieval-Augmented Generation (RAG) ассистента, который отвечает на вопросы о жизни известных личностей. Система включает в себя:
- Квантизированную языковую модель, оптимизированную для работы с ограниченными ресурсами.
- Векторную базу данных, построенную на основе статей Википедии, содержащих информацию о знаменитых личностях.
- Движок для поиска текста в базе данных и функцию поиска информации в интернете.
- Поддержку диалогового режима, что позволяет вести последовательные запросы с учетом истории диалога.

Основная цель проекта — предоставить ассистента, который отвечает на вопросы, используя векторную базу данных, построенную на основе информации из Википедии, а также дополнительный поиск в интернете при необходимости.

## Установка и использование

### Запуск проекта
Этот проект можно запускать **локально на машине с GPU** или в облачных сервисах с поддержкой GPU, таких как **Google Colab** или **Kaggle**.

### Сборка векторной базы данных
Чтобы создать свою векторную базу данных, используйте файл `ru_wiki_person.txt`, который содержит текстовые данные из статей Википедии:

[Скачать ru_wiki_person.txt](https://drive.google.com/file/d/1ktW-LxneHkh9-5eL5E1PqnH6drP-F2id/view?usp=drive_link)

### Использование готовой базы данных
Если вы не хотите создавать базу данных вручную, вы можете использовать готовую векторную базу данных:

[Скачать chroma_db.zip](https://drive.google.com/file/d/1CNGsJccadoRlFUngW_N1X1CjXo_3fq6X/view?usp=drive_link)

В ноутбуке необходимо изменить пути, указанные в переменных path, на те, которые соответствуют вашему окружению и системе. Например, замените путь к вашим локальным файлам или файлам в Google Drive.