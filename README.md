# learning-git2
https://nowakowskitomasz.github.io/learning-git2/

1. test - run all test tasks
2. test:html - check out of bugs all .html files
3. init-project - run all init tasks
4. init:dirs - create catalogs: sass, css, vendor, images, js
5. init:files - create files: README.md, index.html, sass/style.scss, js/script.js
6. init:gitignore - curl .gitignore file from (https://raw.githubusercontent.com/github/gitignore/master/Node.gitignore)
7. build - first run all build tasks and then run test task
8. build:clean - remove .css files before build:sass task
9. build:sass - compress .css and sass files
10. build:autoprefixer - run Autoprefixer who add  vendor prefixes
11. build-dev:sass - make source maps for css and sass files
12. watch - run all build tasks and watch tasks
13. watch:sassprefixer - run watch:sass and watch:autoprefixer
14. watch:sass - observe compressing .css and sass files
15. watch:autoprefixer - observe css/style.css and after change run Autoprefixer
16. watch:browsersync - run browser-sync