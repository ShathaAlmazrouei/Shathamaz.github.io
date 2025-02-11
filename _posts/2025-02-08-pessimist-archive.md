---
layout: post
title:  "Pessimist podcast: Coffee"
author: Shatha
categories: [ Jekyll, tutorial ]
image: assets/images/coffee.jpg
---



<!-- Image Slider Code -->
<div class="image-slider">
  <img src="{{ site.baseurl }}/assets/images/devil.jpg" class="slider-img" id="slider">
  <button class="prev" onclick="prevImage()">&#10094;</button>
  <button class="next" onclick="nextImage()">&#10095;</button>
</div>

<style>
  .image-slider {
    position: relative;
    max-width: 500px;
    margin: auto;
  }
  .slider-img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    display: block;
  }
  .prev, .next {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
    font-size: 18px;
    border-radius: 50%;
  }
  .prev { left: 10px; }
  .next { right: 10px; }
  .prev:hover, .next:hover {
    background-color: black;
  }
</style>

<script>
  var images = [
    "{{ site.baseurl }}/assets/images/devil.jpg",
    "{{ site.baseurl }}/assets/images/womenpetition.jpg",
    "{{ site.baseurl }}/assets/images/coffeehouses.jpg",
    "{{ site.baseurl }}/assets/images/Mecca.jpg",
    "{{ site.baseurl }}/assets/images/Postum.jpg",
    "{{ site.baseurl }}/assets/images/PopeClement.jpg"
  ];

  var currentIndex = 0;

  function showImage(index) {
    document.getElementById("slider").src = images[index];
  }

  function prevImage() {
    currentIndex = (currentIndex - 1 + images.length) % images.length;
    showImage(currentIndex);
  }

  function nextImage() {
    currentIndex = (currentIndex + 1) % images.length;
    showImage(currentIndex);
  }

  // Initialize slider on page load
  window.onload = function() {
    showImage(currentIndex);
  };
</script>



**Define a piccolo, macchiato, latte, flat white and cuppuccino???**



## Key events

1- 1674: The Women's petition against coffee: Women claimed that coffee was ruining their relationships with their husbands. 

2- 1675: On December 30, King Charles II issued a proclamation banning coffee houses, citing their negative impact on promoting dangerous gatherings.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Caffeine health concerns

Health concerns surrounding coffee began to spread. Physicians claimed it led to impotence, paralysis, heart disease, eyesight problems, etc. 


 John Harvey Kellogg:
![Kellog]({{ site.baseurl }}/assets/images/Kellog.jpg)

Called coffee a grave health menace.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Origin of coffee: 

- Coffee began as a religious tool for Sufi monks in Ethiopia, later spreading to the Arab world where coffee houses emerged as centers of discussion and interaction.
-  Yemeni mocha:  Yemeni port of Mocha became a place where coffee beans were exported, and so coffee from that region became known as Mocha.

  
-  ## coffee in the Arab world:
- Coffee became a ritual in the Arab life. It became a necessity in gatherings where men would gather and the coffee was made by infusing the beans with boiling water.

## 1511:

The ban of coffee houses in Mecca. The governor of Mecca, whose name was Khair Begg, in 1511 got very upset because people were apparently being affected by coffee to write satirical verses about him, and he didn't appreciate that. So Khair Begg rounded up some religious scholars and got them to agree that coffee was like alcohol, which is to say a drug that should be banned by the Quran. But his boss, the Sultan of Cairo liked coffee, so the ban was removed.


-Coffee later spread to Europe, invading Christian Europe. It was seen as a muslim drink, and many resisted it.

- Pope Clement VIII famously blessed coffee in the late 1500s, leading to its acceptance as a beverage in Christian Europe despite earlier resistance.
- Throughout Europe, coffee houses served as hubs for revolutionary ideas, significantly impacting events like the American and French Revolutions

## Postum(coffee substitute):
created by Post company, is a powdered roasted grain beverage popular as a coffee substitute. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## coffee and health: 

Peter: coffee is nothing to fear. It's nutritious. It seems to even help the body ward off disease. There are very good studies showing the benefits of coffee drinking with respect to cirrhosis, with respect to Alzheimer's disease, with respect to depression and suicidality, and a whole variety of cancers.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## coffee and politics: 

- coffee leads to coffeehouses which leads to attack against governments
- people become more critical, thoughtful and less afraid. French and American revolutions all resulted from coffee houses. So does coffee change the mind? Well no, but it is associated with focus and calmness.






