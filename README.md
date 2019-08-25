# Welcome to GogsThemes!

This repo contains styles/themes  for well known self hosted git service [Gogs](https://gogs.io/).
If you find something not displayed good  , feel free to contribute
 to make it together even better!!
 
## Steps to activate a theme:
*$GOGS_ROOT = your gogs root install location*

 
 - ````cd $GOGS_ROOT```` 
 - ```git clone https://github.com/Kos-M/GogsThemes.git```
 - ````cat ./GogsThemes/inject/head.tmpl >> templates/inject/head.tmpl  ```` 
 - ```mv  ./GogsThemes/img/grad1.png public/img```
 - ```mv ./GogsThemes/themes/dark_theme.css public/css/themes```
 - ```rm -r ./GogsThemes```

## Screens
![intro](https://raw.githubusercontent.com/Kos-M/GogsThemes/master/img/screenShots/intro.png) ![signup](https://raw.githubusercontent.com/Kos-M/GogsThemes/master/img/screenShots/signup.png)
![home](https://raw.githubusercontent.com/Kos-M/GogsThemes/master/img/screenShots/home.png) ![repo](https://raw.githubusercontent.com/Kos-M/GogsThemes/master/img/screenShots/repo.png)
![file](https://raw.githubusercontent.com/Kos-M/GogsThemes/master/img/screenShots/file.png)
 

## Bg Gradient

Main background was original generated with simple css rules from  [GradientMagic](https://www.gradientmagic.com)
In some low end mobile devices found it enough  stressful to render quickly , i generated css to png from [HtmlCssToImage](https://htmlcsstoimage.com/)

### To disable a theme:
Just open ```$GOGS_ROOT/templates/inject/head.tmpl``` and delete 
the line contains : ``` <link rel="stylesheet" href="/css/themes/dark_theme.css">```



