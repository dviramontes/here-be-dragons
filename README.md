starting up dev server:

`lein ring server`

deploying to s3:

`aws s3 cp resources/public s3://blog.herebedragons.space/ --recursive`

cryogen docs:

[http://cryogenweb.org/](http://cryogenweb.org/)

Sass compile:

`node-sass -w resources/templates/sass/main.scss resources/templates/css/main.css`