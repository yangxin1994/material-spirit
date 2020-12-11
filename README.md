# Material Spirit

Material Spirit is a frontend framework based on Google's [Material Components for web (MDC-Web)](https://material.io/develop/web).

## Предназначение

Основное предназначение этого framework - ускорить разработку на MDC Web. В особенности быстрое прототипирование.

Сам MDC Web не является конечным framework. В большей степени это набор reusable компонентов и систем. Но ему не хватает различных утилитных
функций, которые есть в том же Bootstrap.

В первую очередь framework удобен для быстрого протопирования на MDC-Web. В дальнейшем, когда интерфейс стабилизируется, можно заменить использование
классов-утилит в HTML на использование семантических/контекстных классов и mixins из этого же framework.


## Чего конкретно не хватает в MDC Web:
1. Классов, задающих цвета из цветовой палитры приложения: primary, secondary, surface и т.д. И их вариации: on-primary, on-secondary и т.д.
2. Классов, применяющихся только на определенном размере экрана: в Bootstrap это классы с суфиксами xs, sm, md, lg, xl.


## Как использовать

Можно использовать утилитные классы.
Можно определять свои контекстные/семантические классы, а в них использовать утилитные mixins.


## Концепции и вдохновение
* В первую очередь сам MDC-Web. Поэтому:
** BEM - (найти ссылку)
** Framework разбит на отдельные независимые пакеты, которые вполне можно использовать по отдельности. Так же есть main package. It simply wraps all of its sibling packages up into one comprehensive library for convenience.
* Bootstrap - как самый популярный frontend framework. Это так же ускорит освоение этого framework.