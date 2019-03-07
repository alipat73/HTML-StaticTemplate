echo "# HTML-StaticTemplate" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/alipat73/HTML-StaticTemplate.git
git push -u origin master


"# HTML-StaticTemplate" 
- x-ua-compatible : настройка IE 
- старые версии IE
- Выставить viewport
- html, body должен быть растянут на весь экран

- подключен normalize.css
####
- wrapper - обертка контента. Функциональный блок, необходимый для
  прижатия футера.
  Ширина равна ширене контента + 10px с каждой стороны
  960px+10px+10px=980px
  Для ограничения общей ширины контента на маленьких разрешениях.
  В нем лежит все, кроме футера
####
- container - блок, который выравнивает контент
  по горизонтальному центру экрана.
  Белых полей по бокам окна брайзера быть не должно.
####
- настройка списков. Однотипный контент верстается списками,
  поэтому нужно обнулить стили для них
####
- футер - прижат (прибит) к низу страницы.
  Футер кладется под wrapper

