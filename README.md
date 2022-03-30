BLOG_WF3

EXEMPLE DE STRUCTURE DE BLOG SUR SYMFONY 6

Pour cloner le projet

git clone https://github.com/VinceFormateur/BLOG_WF3.git

Installation

composer install
symfony console doctrine:database:create
symfony console make:migration
symfony console doctrine:migrations:migrate
composer require symfony/webpack-encore-bundle
npm install (pour la partie Webpack Encore)

Webpack Encore (package.json)

 npm install sass-loader@^12.0.0 sass --save-dev
 npm install postcss-loader@^6.0.0 --save-dev
 npm install autoprefixer --save-dev
 npm install bootstrap --save-dev
 npm install bootswatch
 npm install jquery
 npm install --save @fortawesome/fontawesome-free