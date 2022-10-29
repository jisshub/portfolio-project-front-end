# portfolio-project-front-end

Run,

```bash
npm init
```
- Update scripts object of package.json file.

```json
"scripts": {
    "sass": "node-sass -w scss/ -o dist/css/ --recursive"
  }
```

- Create a dist folder. In that folder, create image and js folders.
- Create scss folder. In that folder, create main.scss file.
- Run,

```bash
npm run sass
```

- It will create a css folder and a main.css file under dist directory.
- This css file will update with css when we write sass code in main.scss file.
So we dont have to write css code.

- Create an index.html file.


- Add fontawesome and google fonts family link attribute

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=dosis">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
```

- Create _config.scss file to declare styling variables

```scss
// Variables
$website-width: 1200px;
$main-color: #ffbc00;
$light-color: #f4f4f4;
$medium-color: #ccc;
$dark-color: #333;
$bg-image: url('../img/showcase.jpg')
```



