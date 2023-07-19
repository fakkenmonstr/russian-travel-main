# Проект: Путешествие по России
## Описание проекта **Путешествие по России*:
Гид по России. Россия — это целая вселенная с ласковым морем юга, густыми лесами Саян и суровыми льдами плато Путорана. А ещё увидеть все эти красоты можно без миллионов на счету, загранпаспорта и многочасовых перелетов.
https://fakkenmonstr.github.io/russian-travel-main/index.html

## Обновление сайта:
Данный сайт адаптирован под четыре распространенных разрешений экрана: 320px, 768px, 1024px, 1280px
Для реализации адаптации экрана под разные размеры экрана, был использован CSS код:

```css
@media screen and (min-width: 768px) {
    .place {
        max-width: 720px;
        grid-template-columns: 340px 1fr;
        grid-template-areas:
        "title website"
        "image paragraph";
        column-gap: 28px;
        row-gap: 48px;
        margin: 0 auto 73px;
    }
}

@media screen and (min-width: 1024px) {
    .place {
        max-width: 928px;
        grid-template-columns: 440px 1fr;
        column-gap: 32px;
        margin: 0 auto 80px;
    }
}

@media screen and (min-width: 1288px) {
    .place {
        max-width: 928px;
        grid-template-columns: 460px 1fr;
        column-gap: 40px;
    }
}
```
## Инструкция по использованию проекта и сиситемные требования
Версия языка HTML


