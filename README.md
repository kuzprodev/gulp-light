если уже установлен галп глобально и ннада просто начать проект, то
запускаем проект-           npm i


description:
npm install npm@latest -g установить крайнюю версию ноды
https://webdesign-master.ru/blog/docs/gulp-documentation.html почитать статейку
Чистая папка, с нуля создание
качнуть|install
Node: https://nodejs.org/en/​  (LTS ставится все по-дефолту)
Gulp: https://gulpjs.com/​
npm: https://www.npmjs.com/​
browser-sync: https://browsersync.io/
установить  gulp global console/terminale => должны находиться в папке где создаем проект (cd gulp-start), если не было вообще, то
npm i --gulp-cli  или  npm install --global gulp-cli установить
npm init    инициализация проекта на галпе (появляется package.json)
npm это менеджер пакетов (сборнике пакетов) для программистов-разрабов
npm gulp -v  версия галпа || gulp --version
npm rm --global gulp  -delete галп global || npm rm -g gulp || npm rm -g gulp-cli 
npm i --save-dev gulp установить галп в папку (--save-dev  это ключ который будет прописывать версию модулей, создается package-lookupService.json+node_modules, версии проекта чтоб если вдруг мы обратились к проекту через время знали версии, так как обновления могут сломать усё)
create app&&dir  app-хранится наша разработка\черновик а папка dir то что выливается на хост\чистовик
в корне создаем gulpfile.js

плагин gulp-scss            npm i --save-dev gulp-sass            https://www.npmjs.com/package/gulp-sass

плагин gulp-concat          npm i --save-dev gulp-concat          https://www.npmjs.com/package/gulp-concat

плагин gulp-watch                                                 https://www.npmjs.com/package/gulp-watch  встроенный модуль
плагин browsersync          npm i --save-dev browser-sync         https://browsersync.io/

       Local: http://localhost:3000
    External: http://192.168.88.234:3000  -можно прописать на устройстве которое подключено под темже вифи и будет тотже сайт релоадить и повторять скролл
 ---------------------------------------
          UI: http://localhost:3001
 UI External: http://localhost:3001


 плагин gulp-uglify-es      npm i --save-dev gulp-uglify-es       https://www.npmjs.com/package/gulp-uglify-es

                            npm i --save-dev jquery               https://www.npmjs.com/package/jquery

плагин gulp-autoprefixer    npm i --save-dev gulp-autoprefixer    https://www.npmjs.com/package/gulp-autoprefixer
плагин gulp-imagemin        npm i --save-dev gulp-imagemin        https://www.npmjs.com/package/gulp-imagemingulp
плагин gulp-del             npm i --save-dev del 
плагин gulp-sourcemaps      npm i --save-dev gulp-sourcemaps      https://www.npmjs.com/package/gulp-sourcemaps
 
