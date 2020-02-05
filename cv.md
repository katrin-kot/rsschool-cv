# Katsiaryna Kleshchukevich

## Contact me

- ![Phone Logo](https://img.icons8.com/android/24/000000/phone.png) +37529 275-63-70

---

- ![Git logo](https://img.icons8.com/material-outlined/24/000000/github.png) katrin-kot

---

- ![Telegram logo](https://img.icons8.com/material-outlined/24/000000/telegram-app.png) katrinkot

---

- ![e-mail logo](https://img.icons8.com/material-outlined/24/000000/composing-mail.png) enkor89@gmail.com

## About me

My main goal is to change my job. My current job has become monotonous and my career growth has stopped. Programming makes it possible to express themselves and create products for millions users. I like to see the result on the screen, so I chose the frontend. While studying at school, I would like to master the necessary skills for modern website development. Already learning to use and study javascript. I strive to learn everything new and it is interesting to me.

## Skills

**HTML** - beginner,
**CSS** - beginner,
**JS** - beginner,
**Git** - beginner

## Code examples

```javascript
module.exports = function makeExchange(currency) {
  if (currency > 10000) {
    return {
      error: "You are rich, my friend! We don't have so much coins for exchange"
    };
  }
  const H = Math.floor(currency / 50);
  const Q = Math.floor((currency - H * 50) / 25);
  const D = Math.floor((currency - H * 50 - Q * 25) / 10);
  const N = Math.floor((currency - H * 50 - Q * 25 - D * 10) / 5);
  const P = currency - H * 50 - Q * 25 - D * 10 - N * 5;
  const result = {};
  if (H > 0) {
    result.H = H;
  }
  if (Q > 0) {
    result.Q = Q;
  }
  if (D > 0) {
    result.D = D;
  }
  if (N > 0) {
    result.N = N;
  }
  if (P > 0) {
    result.P = P;
  }
  return result;
};
```

```javascript
let currentSlide = 0;
const slider = document.querySelector('.slider');
const slide = document.createElement('li');
slider.appendChild(slide);
const indicators = document.createDocumentFragment();
tips.forEach((item, index) => {
  const button = document.createElement('button');
  if (index === 0) {
    button.classList.add('current');
  }
  button.dataset.slide = index;
  button.addEventListener('click', () => {
    const prevCurrent = document.querySelector('button.current');
    prevCurrent.classList.remove('current');
    currentSlide = index;
    button.classList.add('current');
    renderCurrentSlide(currentSlide);
  });
  const li = document.createElement('li');
  li.appendChild(button);
  indicators.appendChild(li);
});
```

## Experience

I passed several courses on codacademy и htmlacademy. Here are links to my profiles:

**Codecademy** https://www.codecademy.com/users/katrin-kot/achievements

**Htmlacademy** https://htmlacademy.ru/profile/id808735/achievements

## Education

_2006-2011_ Belarus State Economic University - Accounting, Analysis and Audit in Construction,

_2018-2019_ online-course Sololearn

## English level

**A2** - Pre-Intermediate (2017-2018 online school "English Tochka")
