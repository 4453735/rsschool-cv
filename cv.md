# Curriculum Vitae

## ARTEM KURGAEV

### Сontacts for communication

* E-mail: 4453735@gmail.com
* Phone: +7 (967) 670 00 67 (WatsApp, Telegram available)

### About me

My main goal is to get into a strong development team and work with real projects. Now I manage the direction of IT-support systems development in a large IT-company. At the same time I'm studying to be a front-end developer. I love daily outings with friends and fun parties.

### Skills

* JavaScript
* HTML
* CSS
* SaaS

### Code examples

```js
'use strict';

const products = [
    {id: 1, title: 'Notebook', price: 20000},
    {id: 2, title: 'Mouse', price: 1500},
    {id: 3, title: 'Keyboard', price: 5000},
    {id: 4, title: 'Gamepad', price: 4500},
];

const renderProduct = (item, img ='./img/no-image.png') =>
    `<div class="product-item card col">
                <img src="${img}" alt="image" class="product-img">
                <h3 class="product-title">${item.title}</h3>
                <p class="product-price">${item.price} руб</p>
                <button class="by-btn">В корзину</button>
            </div>`;

const renderProducts = list => {
    document.querySelector('.products').insertAdjacentHTML('beforeend', list.map(item => renderProduct(item, item.img)).join(''));
};

renderProducts(products);
```

### Education
> 2004-2009 Kuban's State University, Krasnodar, Russia.
> Specialization: Economy (State and municipal management).

> From 2021 Geekbrains, Moscow, Russia.
> Specialization: Frontend development.

> From 2022: RS School.
> Specialization: Frontend development.

### Language skills

* Russian language: native speaker  
* English language: A2 
* Polish language: A1
