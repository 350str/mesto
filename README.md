# [mesto](https://mesto-new.now.sh/) 


## Mesto - сервис по добавлению, редактированию и оценке фотокарточек. 

Разрабатывался с целью практики с JavaScript, а именно с ООП и Api.

Основной стек технологий - HTML5, CSS3, JavaScript (ES6+, ООП, fetch). Верстка и файловая структура согласно БЭМ.

Доступный функционал: 
  * можно ставить лайк;
  * можно увеличить изображение карточки путем клика на нее; 
  * добавлять новую карточку; 
  * удалять карточки (только добавленные самим пользователем); 
  * редактировать имя пользователя и изображение профиля; 
  * присутствует валидация форм через JavaScript.

### Setup

`$ npm install`

`$ npm run build`

**v0.1.2**
  * проект выложен на Github Pages;
  * улучшена произовдительность за счет уменьшения количества запросов на сервер;
  * .DS_Store добавлен в .gitignore;
  * в режиме разработки протокол изменен на HTTP.

**v0.1.1**
  * выходная директория изменена с dist на public для отображения на Zeit;
  * fixed bugs.

**v0.1.0**
  * добавлена сборка проекта через Webpack;
  * два варианта сборки - production и development;
  * JS транспилится в ES5 (подключен и настроен Babel);
  * настроены autoprefixer, css-loader, file-loader и др. (полный список внутри внутри package.json);
  * код разбит на модули.
