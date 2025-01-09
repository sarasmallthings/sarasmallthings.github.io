---
layout: page
title: Sourdough Recipes
permalink: /sourdough
---

<div style="position: relative; overflow: hidden; height: 300px; border-radius: 15px; box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);">
  <video autoplay muted loop playsinline style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;">
    <source src="{{ site.baseurl }}/assets/videos/loop.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <div style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; background: rgba(0, 0, 0, 0.4); display: flex; align-items: center; justify-content: center; z-index: 1;">
    <div style="text-align: center; color: white; padding: 20px;">
      <h1 style="font-size: 2.5em; margin: 0;">Welcome to Sourdough Recipes</h1>
      <p style="font-size: 1.2em; margin-top: 10px;">Discover the art of fermentation and bake delicious memories.</p>
    </div>
  </div>
</div>

<div class="container" style="padding: 20px;">
  <h2>Explore Our Recipes</h2>
  <p>Each recipe is carefully crafted to guide you step-by-step, ensuring success and delight. Click below to start baking!</p>

  <ul style="list-style-type: none; padding: 0;">
    <li style="margin: 10px 0;">
      <a href="{{ site.baseurl }}/sourdough-bread-post" style="text-decoration: none; color: #2c3e50; font-size: 1.2em;">
        🥖 Sourdough Bread
      </a>
      <p style="margin: 5px 0; color: #7f8c8d;">Master the classic loaf that started it all.</p>
    </li>
    <li style="margin: 10px 0;">
      <a href="{{ site.baseurl }}/sourdough-pancakes-post" style="text-decoration: none; color: #2c3e50; font-size: 1.2em;">
        🥞 Sourdough Pancakes
      </a>
      <p style="margin: 5px 0; color: #7f8c8d;">Fluffy, tangy pancakes to brighten your mornings.</p>
    </li>
    <li style="margin: 10px 0;">
      <a href="{{ site.baseurl }}/sourdough-pizza-post" style="text-decoration: none; color: #2c3e50; font-size: 1.2em;">
        🍕 Sourdough Pizza
      </a>
      <p style="margin: 5px 0; color: #7f8c8d;">A crispy crust that’s perfect for any topping.</p>
    </li>
  </ul>

 <div id="recipeCarousel" class="carousel" style="margin: 40px auto; max-width: 900px; height: 350px; overflow: hidden; border-radius: 15px; position: relative; margin-left: auto; margin-right: auto;">
  <div class="carousel-container" style="width: 100%; height: 100%; position: relative;">
    <div class="carousel-slides" style="display: flex; transition: transform 0.5s ease-in-out; height: 100%;">
      <!-- Slide 1 -->
      <div class="carousel-slide" style="flex: 0 0 100%; display: flex; height: 100%; padding: 0;">
        <div style="flex: 1; height: 100%; overflow: hidden;">
          <img src="{{ site.baseurl }}/assets/images/Image 1.png" alt="Sourdough Cinnamon Rolls" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="flex: 1; text-align: left; padding: 20px; display: flex; flex-direction: column; justify-content: center; background-color: #ffe9d6; border-left: 3px solid #e67e22;">
          <h3 style="color: #e67e22; font-family: 'Arial', sans-serif; font-size: 26px; margin-bottom: 12px;">Sourdough Cinnamon Rolls</h3>
          <p style="color: #7f8c8d; font-family: 'Arial', sans-serif; font-size: 18px; line-height: 1.6;">Indulge in the sweet and tangy flavors of homemade sourdough cinnamon rolls.</p>
        </div>
      </div>
      <div class="carousel-slide" style="flex: 0 0 100%; display: flex; height: 100%; padding: 0;">
        <div style="flex: 1; height: 100%; overflow: hidden;">
          <img src="{{ site.baseurl }}/assets/images/Image 2.png" alt="Sourdough Pizza" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="flex: 1; text-align: left; padding: 20px; display: flex; flex-direction: column; justify-content: center; background-color: #f4f4f4; border-left: 3px solid #2c3e50;">
          <h3 style="color: #2c3e50; font-family: 'Arial', sans-serif; font-size: 26px; margin-bottom: 12px;">Sourdough Pizza</h3>
          <p style="color: #7f8c8d; font-family: 'Arial', sans-serif; font-size: 18px; line-height: 1.6;">A crispy crust that’s perfect for any topping. A crowd favorite for sourdough lovers!</p>
        </div>
      </div>
      <div class="carousel-slide" style="flex: 0 0 100%; display: flex; height: 100%; padding: 0;">
        <div style="flex: 1; height: 100%; overflow: hidden;">
          <img src="{{ site.baseurl }}/assets/images/Image 3.png" alt="Sourdough Pancakes" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="flex: 1; text-align: left; padding: 20px; display: flex; flex-direction: column; justify-content: center; background-color: #ffe9d6; border-left: 3px solid #e67e22;">
          <h3 style="color: #e67e22; font-family: 'Arial', sans-serif; font-size: 26px; margin-bottom: 12px;">Sourdough Pancakes</h3>
          <p style="color: #7f8c8d; font-family: 'Arial', sans-serif; font-size: 18px; line-height: 1.6;">Fluffy, tangy pancakes to brighten your mornings and bring joy to your family.</p>
        </div>
      </div>
    </div>
    <div style="position: absolute; bottom: 10px; right: 10px; width: 100%; display: flex; justify-content: center; z-index: 10;">
  <ul style="list-style-type: none; display: flex; justify-content: center; padding: 0; margin: 0;">
    <li style="margin: 0 5px;">
      <button id="carouselDot1" class="carousel-dot" style="background-color: #ccc; border: none; border-radius: 50%; width: 12px; height: 12px; cursor: pointer;"></button>
    </li>
    <li style="margin: 0 5px;">
      <button id="carouselDot2" class="carousel-dot" style="background-color: #ccc; border: none; border-radius: 50%; width: 12px; height: 12px; cursor: pointer;"></button>
    </li>
    <li style="margin: 0 5px;">
      <button id="carouselDot3" class="carousel-dot" style="background-color: #ccc; border: none; border-radius: 50%; width: 12px; height: 12px; cursor: pointer;"></button>
    </li>
  </ul>
</div>
  </div>
</div>

<script>
  const slides = document.querySelector('.carousel-slides');
  const carouselDots = document.querySelectorAll('.carousel-dot');
  let currentIndex = 0;

  function updateCarousel() {
    slides.style.transform = `translateX(-${currentIndex * 100}%)`;
    carouselDots.forEach(dot => dot.style.backgroundColor = '#ccc');
    carouselDots[currentIndex].style.backgroundColor = '#000';
  }

  function startCarousel() {
    setInterval(() => {
      currentIndex = (currentIndex + 1) % slides.children.length;
      updateCarousel();
    }, 5000);
  }

  carouselDots.forEach((dot, index) => {
    dot.addEventListener('click', () => {
      currentIndex = index;
      updateCarousel();
    });
  });

  updateCarousel();
  startCarousel();
</script>

  <h2>Why Sourdough?</h2>
  <p>Sourdough is more than bread; it’s a journey. Its rich flavor, health benefits, and timeless techniques make it a rewarding experience for anyone who tries it. Let’s bake memories together!</p>

  <div style="text-align: center; margin-top: 30px;">
    <a href="{{ site.baseurl }}/contact" style="padding: 10px 20px; background-color: #e67e22; color: white; text-decoration: none; border-radius: 5px;">Share Your Recipes</a>
  </div>
</div>
