# lab4web
# box
``` html
    <section>
      <div class="div1">Div 1</div>
      <div class="div2">Div 2</div>
      <div class="div3">Div 3</div>
    </section>
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20211744.png)
``` html
<style>
div {
float:left;
padding: 10px;
}
.div1 {
background: red;
}
.div2 {
background: yellow;
}
.div3 {
background: green;
}
</style>
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20212138.png)
``` html
<div class="div4">Div 4</div>
.div4 {
background-color: blue;
clear: left;
float: none;
}
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20212313.png)
# layout
``` html
<header>
<h1>Layout Sederhana</h1>
</header>
<nav>
<a href="home.html" class="active">Home</a>
<a href="artikel.html">Artikel</a>
<a href="about.html">About</a>
<a href="kontak.html">Kontak</a>
</nav>
<section id="hero"></section>
<section id="wrapper">
<section id="main"></section>
<aside id="sidebar"></aside>
</section>
<footer>
<p>&copy; 2021 - Universitas Pelita Bangsa</p>
</footer>
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20212637.png)
``` css
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400
;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0
,300;0,700;1,300&display=swap');
/* Reset CSS */
* {
margin: 0;
padding: 0;
}
body {
line-height:1;
font-size:100%;
font-family:'Open Sans', sans-serif;
color:#5a5a5a;
}
#container {
width: 980px;
margin: 0 auto;
box-shadow: 0 0 1em #cccccc;
}
/* header */
header {
padding: 20px;
}
header h1 {
margin: 20px 10px;
color: #b5b5b5;
}
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20212949.png)
``` css
nav {
display: block;
background-color: #1f5faa;
}
nav a {
padding: 15px 30px;
display: inline-block;
color: #ffffff;
font-size: 14px;
text-decoration: none;
font-weight: bold;
}
nav a.active,
nav a:hover {
background-color: #2b83ea;
}
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20213420.png)
``` html
<section id="hero">
<h1>Hello World!</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
<a href="home.html" class="btn btn-large">Learn more &raquo;</a>
</section>
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20213531.png)
``` css
#hero {
background-color: #e4e4e5;
padding: 50px 20px;
margin-bottom: 20px;
}
#hero h1 {
margin-bottom: 20px;
font-size: 35px;
}
#hero p {
margin-bottom: 20px;
font-size: 18px;
line-height: 25px;
}
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20215356.png)
``` html
 <section id="main">
          <div class="row">
            <div class="box">
              <img
                src="https://dummyimage.com/120/db7d25/fff.png"
                alt=""
                class="image-circle"
              />
              <h3>Heading</h3>
              <p>
                Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.
              </p>
              <a href="#" class="btn btn-default">View detail</a>
            </div>
            <div class="box">
              <img
                src="https://dummyimage.com/120/3e73e6/fff.png"
                alt=""
                class="image-circle"
              />
              <h3>Heading</h3>
              <p>
                Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.
              </p>
              <a href="#" class="btn btn-default">View detail</a>
            </div>
            <div class="box">
              <img
                src="https://dummyimage.com/120/71e6d4/fff.png"
                alt=""
                class="image-circle"
              />
              <h3>Heading</h3>
              <p>
                Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.
              </p>
              <a href="#" class="btn btn-default">View detail</a>
            </div>
          </div>
        </section>
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20215518.png)
``` html
  <div class="widget-box">
            <h3 class="title">Widget Text</h3>
            <p>
              Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
              tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
              faucibus felis. Integer pharetra est nunc, nec pretium nunc
              pretium ac.
            </p>
          </div>
        </aside>
      </section>
      <hr class="divider" />
      <article class="entry">
        <h2>First featurette heading.</h2>
        <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" />
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
          lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin
          in leo fringilla, vestibulum mi porta, faucibus felis. Integer
          pharetra est nunc, nec pretium nunc pretium ac.
        </p>
      </article>
      <hr class="divider" />
      <article class="entry">
        <h2>First featurette heading.</h2>
        <img
          src="https://dummyimage.com/150/7b8a70/fff.png"
          alt=""
          class="right-img"
        />
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
          lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin
          in leo fringilla, vestibulum mi porta, faucibus felis. Integer
          pharetra est nunc, nec pretium nunc pretium ac.
        </p>
      </article>
```
![Foto](https://github.com/AhmadIbnuAbdillah/img4/blob/f1d2010a35015c25cd27bcb21ff7db41498b15df/Screenshot%202025-10-21%20215628.png)
