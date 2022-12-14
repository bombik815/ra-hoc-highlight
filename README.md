[![Build status](https://ci.appveyor.com/api/projects/status/79cvo2m0l1ytulr8/branch/main?svg=true)](https://ci.appveyor.com/project/bombik815/ra-hoc-highlight/branch/main)

[Подсвечивание блоков](https://bombik815.github.io/ra-hoc-highlight/)

===

На нашем сайте есть блоки со статьями и с видео записями. 

![Highlight](./assets/highlight.png)

Мы решили улучшить отображение наших блоков таким образом, 
чтобы популярные статьи и видео (1000+ прочтений/просмотров) 
оборачивались в компонент `Popular`, а с количеством до 
100 в компонент `New`. Эти компоненты будут менять внешний 
облик блоков привлекая внимание посетителей.

## Реализация

Используя HOC обернуть `Video` и `Article` таким образом, чтобы при отображении в компоненте `List` они помещались внутрь требуемого компонента `Popular` или `New`.

Воспользуйтесь готовым файлом `App.js` и стилями `css/index.css` из данного каталога в качестве отправной точки (замените ими те, что создаются в create-react-app).
