# Сохранение SVG в Adobe Illustrator

![Adobe Illustrator logo](https://github.com/djviy/SVG/blob/master/images/icon-logo-illustrator.png "Illustrator logo")

В Adobe Illustrator существует 3 способоа сохранения SVG. Каждый способ имеет свои настройки.
[вставить картинки]

## File > Export > Export As...  (Оптимальный способ)

![Export As Settings](https://github.com/djviy/SVG/blob/master/images/export-as-svg-settings.png "Export As Settings")

### [Styling]
**Presentation Attributes**  
Почти всегда если у нас белый квадрат, но мы хотим перекрасить его в чёрный при наведений, мы используем свойства CSS.
Если белый цвет сохранён как *Presentatin Attributes*, то его легче переопределить другими свойствами CSS.
Инлайновые стили или внутренние стили CSS в большой SVG можно оптимизировать тем или иным образом.
### [Font]
**SVG**  
Шрифт будет доступен для последующего редактирования.  
**Convert to outlines** – переводит шрифт в вектор. Что значительно увеличит изображение. Выбирается, если присутствую какие-то специфические шрифты. Например шрифты в логотипах.

### [Images]
**Embeded**  
Если присутствует растровая графика, то будет вставлена как часть SVG.

### [Objects ID]
**Minimal**  
Подходит для уменьшения веса картинки. Обычно доступ к каждому элементу SVG изображения не требуется. При необходимости, можно задать самостоятельно.

### [Decimal]
**2**  
Оптимальный выбор, т.к. меньшее число уменьшает точность. Большее – увеличивает размер изображения
### [Minimify]
**YES!**
### [Recsponsive]
**Не выбрано**  
Картинка по умолчанию займёт всё доступное пространство блока. Последующее изменение размеров картинки возможно через CSS. 

### [Пример кода прямоугольника с данными настройками]
```html
<svg xmlns="http://www.w3.org/2000/svg" width="50" height="20" viewBox="0 0 50 20">
  <title>image</title>
  <rect width="50" height="20" fill="#fff"/>
</svg>
```


### Быстрый вызов *"Export As"*
![Export As Shortcut](https://github.com/djviy/SVG/blob/master/images/export-as-shortcut.png "Export As Shortcut")  
В настройках устанавливаем вызов с помощью клавиш **"Alt+Shift+Ctr+A"**  
Эта комбинация клавиш по умолчания не занята, находится рядом с остальными комбинациями и удобна для нажатия.


