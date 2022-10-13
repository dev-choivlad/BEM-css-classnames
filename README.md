# BEM-css-classnames
Class naming one of the most frustrating parts of development. To make it easier I decided to put together a list of commonly used class names for elements :partying_face: .  

### Navigation
````html
<nav class="main-nav" aria-label="Main">
  <ul class="main-nav__list">
    <li class="main-nav__item">
      <a href="#" class="main-nav__link">Home</a>
    </li>
    
    <li class="main-nav__item">
      <a href="#" class="main-nav__link">Work</a>
    </li>
    
    <li class="main-nav__item">
      <a href="#" class="main-nav__link">About us</a>
    </li>
  </ul>
</nav>
````
### Contact form
````html
<form class="contact-form">
  <div class="contact-form__field">
    <label class="contact-form__label" for="input-name">Name</label>
    <input class="contact-form__control" id="input-name" type="text" name="name">
  </div>
  
  <div class="contact-form__field">
    <label class="contact-form__label" for="input-email">Email</label>
    <input class="contact-form__control" id="input-email" type="email" name="email">
  </div>
  
  <div class="contact-form__field">
    <label class="contact-form__label" for="input-message">Message</label>
    <textarea class="contact-form__control" id="input-message" name="message"></textarea>
  </div>

  <button class="contact-form__submit" type="submit">Submit</button>
</form>
````
### Card
````html
<div class="card">
  <div class="card__header">
    <figure class="card__figure">
      <img src="" alt="" class="card__img">
    </figure>
  </div>
  
  <div class="card__body">
    <h2 class="card__title"></h2>
    <h3 class="card__subtitle"></h3>
    <p class="card__desc"></p>
  </div>
  
  <div class="card__footer">
    <button class="card__btn"></button>
  </div>
</div>
````
