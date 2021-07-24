# Web-технологии

В данном репозитории хранятся все презентации для освоения дисциплины
"Web-технологии". Презентации сделаны на движке [Shower](https://shwr.me/). Посмотреть полный список материалов можно
по [ссылке](https://lovesolaristics.github.io/shower-presentation/).

## Содержание

- [Основы web-технологий](https://lovesolaristics.github.io/shower-presentation/1.html);
- [Структура HTML-документа](https://lovesolaristics.github.io/shower-presentation/2.html);
- [Базовые теги для разметки документа](https://lovesolaristics.github.io/shower-presentation/3.html);
- [Разметка текста](https://lovesolaristics.github.io/shower-presentation/4.html);
- [Ссылки и медиа-элементы](https://lovesolaristics.github.io/shower-presentation/5.html);
- [Таблицы и устаревшие теги](https://lovesolaristics.github.io/shower-presentation/6.html);

## Локальный запуск

Для локального запуска необходим [Node.js](https://nodejs.org/en/).

Вы можете скачать репозиторий в виде zip-архива, либо клонировать этот репозиторий с помощью командной строки.

Далее необходимо установить зависимости:

```
npm install
```

А затем выполнить команду для возможности редактирования слайдов с поддержкой автоматической перезагрузки изменений:

```
npm start
```

После внесения изменений можно получить чистую копию слайдов в папке `prepared`
с помощью команды:

```
npm run prepare
```

## Дополнительная информация

- Документация об основных возможностях Shower — [подробнее](https://github.com/LoveSolaristics/shower-presentation/blob/master/docs/features.md);
- Управление во время показа слайдов — [подробнее](https://github.com/LoveSolaristics/shower-presentation/blob/master/docs/shortcuts.md);
- Возможность экспорта презентации в pdf — [подробнее](https://github.com/LoveSolaristics/shower-presentation/blob/master/docs/pdf.md).