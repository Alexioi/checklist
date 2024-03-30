# checklist

1. Форматирование размещения импортов. [подробнее](https://github.com/fullstack-development/front-end-best-practices/tree/master/JS#1.17)
2. Экспорты держать в конце файла. [подробнее](https://github.com/fullstack-development/front-end-best-practices/tree/master/JS#1.18)
3. При использование svgr переделываем название в PascalCase и не забываем добить на конце SVG, что бы было сразу очевидно что это svg или часть svg
4. Выносим по максимому код из view(часть функционального компонента реакт после return). То есть все обработчики кликов и стили, которые добавляются в зависимости от условий с помощью svgr, но если условие всего одно, то можно есго оставить.
5. Используем для модификаторов svgr.
6. Правильное именование функций обрабодчиков событий [подробнее](https://github.com/fullstack-development/front-end-best-practices/tree/master/JS#3.3)
