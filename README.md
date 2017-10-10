![](https://github.com/dzmitROCK/start/blob/master/app/favicon/android-chrome-512x512.png?raw=true)
# Стартовый шаблон для вёрстки *
#### Документация в разработке
Все настройки в gulpfile.js  
##### Установка
* `git clone https://github.com/dzmitROCK/starter-mini-gulp.git` клонируем репозиторий
* `cd starter-mini-gulp` переходим в папку проекта
* `yarn` устанавливаем все зависимости и пакеты 
##### Использование
`yarn start` запуск разработки  
`yarn production` компиляция проекта в продакшен   
`yarn cacheme` очистить кэш  
`yarn plug` проверить какие плагины в автозагрузке и названия  
`yarn zip` архивация проекта  
`yarn deploy` загружаем на хостинг, предварительно настроив в deploy.json переменные и добавте его в .gitignore после найстройки !! будьте осторожны с этим файлом, чтобы не попал в свободный доступ !!
##### Использованы препроцессоры
* scss
* pug