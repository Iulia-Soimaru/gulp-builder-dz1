# Учебная сборка Loftschool

> Сборка работает на gulp версии 4.0.

#### Для начала работы

1. ```clone this repo```
2. ```cd path/to/...```
3. ```npm install gulpjs/gulp-cli -g```
> Установка последней версии Gulp CLI tools глобально (подробнее - [GitHub](https://github.com/gulpjs/gulp/blob/4.0/docs/getting-started.md) )

4. ```npm install```
6. ```run gulp```

new tasks made by Iulia Soimaru

- gulp sprite:png
- gulp copy:font

1. sprite:png task creates new sprite from all `.png` and `.gif` images from `source/images`
2. copy:font task copies fonts from `source/fonts` to `fonts` folder that is going to be used for produciton

