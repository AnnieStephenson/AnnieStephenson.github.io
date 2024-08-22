---
layout: page
title: "code"
permalink: /code/
---

<style>
.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 5px; /* Increased gap between grid items */
    padding: 1px;
    width: 100%;
}
.grid-item {
    text-align: center;
}
.grid-item img {
    width: 100%;  /* Image width will be % of the container's width */
    height: auto; /* Height will adjust automatically to maintain aspect ratio */
    border-radius: 1px;
}
</style>


<div class="grid-container">
    <div class="grid-item">
        <a href="https://example.com/photo1">
            <img src="/images/code/rplace.png" alt="Photo 1">
            <p>Caption for Photo 1</p>
        </a>
    </div>
    <div class="grid-item">
        <a href="https://example.com/photo2">
            <img src="/images/code/colorpy.png" alt="Photo 2">
            <p>Caption for Photo 2</p>
        </a>
    </div>
    <!-- Add more grid items as needed -->
</div>
