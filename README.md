-- # Menu-2
-- Menu for second assesment

HTML:

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Food, LLC</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="#">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Menu</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Contact</a>
      </li>
    </ul>
  </div>
</nav>

<h1 class="text-center">Our Menu</h1>

<section class="container">
  <div class="row">
    <div class="col-md-6">
      <!-- Content for the first column -->
    </div>
    <div class="col-md-6">
      <!-- Content for the second column -->
    </div>
  </div>
</section>
```

CSS:

```css
/* Add your custom styles here */

.navbar-brand {
  margin-right: 1rem;
}

.navbar-nav {
  margin-left: auto;
}

.text-center {
  text-align: center;
}

.container {
  min-height: 100vh;
}
```
