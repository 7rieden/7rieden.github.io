---
layout: post
title: D-day with Timer 🎅
date: 2020-06-06 17:00:00
permalink: /C_Lang/Javascript
tags: [Javascript]
comments: true
---

<h3>Syntax</h3>

The parseInt() function parses a string argument and an integer number in Javascipt.

```js
if(condition){statement1} else{statement2}
```
```js
${ condition ? statement1 : statement2}
```
```js
function getTime() {
  const xmasDay = new Date("2020-12-24:00:00:00+0900");
  const today = new Date();
  const dDay = 24 * 60 * 60 * 1000;
  const diff = xmasDay.getTime() - today.getTime();
  const diffDays = Math.round(Math.abs((today - xmasDay) / dDay));
  let hours = parseInt((diff / (1000 * 60 * 60)) % 24); // Hours
  let minutes = parseInt((diff / (1000 * 60)) % 60); // Minutes
  let seconds = parseInt((diff / 1000) % 60); // Seconds

  // if under 10, add 0 in front
  clockTitle.innerText = `${diffDays < 10 ? `0${diffDays}` : diffDays}d ${
    hours < 10 ? `0${hours}` : hours
  }h ${minutes < 10 ? `0${minutes}` : minutes}m ${
    seconds < 10 ? `0${seconds}` : seconds
  }s`;
}
```