# Smooth Scroll

![alt text](src/assets/smooth-scroll.gif)

I were used a default structure for create the anchor links.

```html
<body>
  <nav>
    <ul>
      <li><a href="#about">Sobre</a></li>
      <li><a href="#service">Serviços</a></li>
      <li><a href="#contact">Contato</a></li>
    </ul>
  </nav>

  <main>
    <section id="about">
      <h1>Sobre</h1>
    </section>
    <section id="service">
      <h1>Serviços</h1>
    </section>
    <section id="contact">
      <h1>Contato</h1>
    </section>
  </main>

</body>
```


This app the focus were use of the new feature CSS [smooth]().

```css
html {
  scroll-behavior: smooth;
}
```
Also adding the color scheme into  [:root](), creating some variables.
That become easy more for reusable the colors into project.
```css
:root {
  --white: #fff;
  --gray-dark: #333;
  --black: #111;
  --purple: orchid;
  --blue: rgb(112, 176, 218);
  --green: rgb(112, 218, 124);
}
```



### Languages used

| HTML   |      CSS      |
|----------|:-------------:|
|public/index.html |  src/styles/global.css |
