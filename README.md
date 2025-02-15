## Tasks

### 1.

By using this HTML:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>
```
And this image file: [0-sprite.png](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250215T153739Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=d8e3ec9e9ff86104ac4323ca02f1e75b1a67deb6353a0a14f27b5efc3ea047ce "0-sprite.png")

Create `0-styles.css` and generate this layout:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250215T153739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=50b542192128c0a09909395d5c500119b576fd3c526d2ae939456e9d85b62797)

You are not allowed to change the image and the HTML - _sprite is cool!_

  

### 2.

By using this HTML:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>
```
Create `1-styles.css` and generate this layout where the underline is hidden by default and appeared slowly…:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250215T153739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=70cdca8d780d5bca2d4b9627e521863e63b8e001e603040f7dd6d9a2d778e2e3)

You are not allowed to change the HTML

  

### 3.

By using this HTML:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>
```
Create `2-styles.css` and generate this layout where the `<input>` is has this custom toggle layout:

**Checked:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250215T153739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ace6b1bb55638e01b3dc1e6d8fc95082646ef841863c73cb2b8c9c703b60b92c)

**Unchecked:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250215T153739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b80a8ddeb255dffd4b28757eedcb9662a645c4c3bb443b84e74c1c7c74fd106f)

You are not allowed to change the HTML

  

### 4.

By using this HTML:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>
```
Create `3-styles.css` and generate this layout/animation:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250215T153739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fdba3e5f745ec147ba06201342bbef3d5adc00dea874f799a547376bfd886b17)

You are not allowed to change the HTML
