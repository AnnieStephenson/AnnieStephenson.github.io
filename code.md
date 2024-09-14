---
layout: page
title: "CODE"
permalink: /code/
---
<style>
   .container, .page-content {
    max-width: 1000px !important; /* Set the new max width */
    width: 100% !important; /* Ensure it stretches */
    margin: 0 auto; /* Center the content */
    padding: 20px;
  }
</style>

insert an overview here talking about what the projects are intended for as a whole. Also mention tools used and potentially certifications. 

<style>
  .image-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    justify-items: center;
    margin-bottom: 40px;
  }

  .image-grid-item {
    position: relative;
    text-align: center;
    width: 100%;
  }

  .image-grid img {
    width: 200px; /* Set the width of all images */
    height: auto; 
    border-radius: 0px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .caption {
    margin-top: 0;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
    background-color: rgb(248, 245, 240);
    box-sizing: border-box;
    padding: 20px;
    border-radius: 0px;
    font-size: 12px;
    color: rgb(60, 60, 60);
    width: 200px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
</style>

<div class="image-grid">
  <div class="image-grid-item">
    <a href="/project1/">
    <img src="/images/code/rplacem.jpeg" alt="Image 1">
    <div class="caption">Caption for Image 1</div>
    </a>
  </div>
  <div class="image-grid-item">
    <img src="/images/code/pymie.jpeg" alt="Image 2">
    <div class="caption">Caption for Image 2</div>
  </div>
  <div class="image-grid-item">
    <img src="/images/code/mstm.jpeg" alt="Image 3">
    <div class="caption">Caption for Image 3</div>
  </div>
  <div class="image-grid-item">
    <img src="/images/code/colorpy.jpeg" alt="Image 4">
    <div class="caption">Caption for Image 4</div>
  </div>
    <div class="image-grid-item">
    <img src="/images/code/structural-color.jpeg" alt="Image 5">
    <div class="caption">Caption for Image 5</div>
  </div>
</div>

# My Square Bookmarks
---
layout: page
title: "Square Bookmarks"
permalink: /bookmarks-square/
---

# My Square Bookmarks

<div class="square-bookmark-grid">
  
  <a href="/project-1/" class="square-bookmark-link">
    <div class="square-bookmark-card">
      <img src="image-placeholder.jpg" alt="Project 1 Image" class="square-bookmark-image">
      <div class="square-bookmark-content">
        <div class="square-bookmark-title">Project 1</div>
        <div class="square-bookmark-description">
          A description of Project 1. This is a short blurb about what the project entails.
        </div>
      </div>
    </div>
  </a>

  <a href="/project-2/" class="square-bookmark-link">
    <div class="square-bookmark-card">
      <img src="another-image.jpg" alt="Project 2 Image" class="square-bookmark-image">
      <div class="square-bookmark-content">
        <div class="square-bookmark-title">Project 2</div>
        <div class="square-bookmark-description">
          A description of Project 2. Brief details about this project.
        </div>
      </div>
    </div>
  </a>

  <a href="/project-3/" class="square-bookmark-link">
    <div class="square-bookmark-card">
      <img src="third-image.jpg" alt="Project 3 Image" class="square-bookmark-image">
      <div class="square-bookmark-content">
        <div class="square-bookmark-title">Project 3</div>
        <div class="square-bookmark-description">
          A description of Project 3. Brief details about this project.
        </div>
      </div>
    </div>
  </a>

</div>

<style>
  .square-bookmark-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    justify-items: center;
  }

  .square-bookmark-card {
    display: flex;
    flex-direction: column;
    border: 1px solid #e0e0e0;
    border-radius: 10px;
    max-width: 300px; /* Max width for a square design */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    background-color: #fff;
    overflow: hidden; /* Ensures the image and content stay inside the card */
  }

  .square-bookmark-image {
    width: 100%; /* Image takes full width */
    height: 200px;
    object-fit: cover; /* Keeps the image in proportion */
  }

  .square-bookmark-content {
    padding: 20px;
    text-align: center; /* Center the text content */
  }

  .square-bookmark-title {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 10px;
    color: #333;
  }

  .square-bookmark-description {
    font-size: 14px;
    color: #777;
    margin-bottom: 10px;
  }

  .square-bookmark-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
    transition: transform 0.2s, box-shadow 0.2s;
  }
</style>
