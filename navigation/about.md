---
layout: post
title: About Me
permalink: /about/
comments: true
---

## Places

<style>
    /* Style looks pretty compact, 
       - grid-container and grid-item are referenced the code 
    */
    .grid-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); /* Dynamic columns */
        gap: 10px;
    }
    .grid-item {
        text-align: center;
    }
    .grid-item img {
        width: 100%;
        height: 100px; /* Fixed height for uniformity */
        object-fit: contain; /* Ensure the image fits within the fixed height */
    }
    .grid-item p {
        margin: 5px 0; /* Add some margin for spacing */
    }

    .image-gallery {
        display: flex;
        flex-wrap: nowrap;
        overflow-x: auto;
        gap: 10px;
        }

    .image-gallery img {
        max-height: 150px;
        object-fit: cover;
        border-radius: 5px;
    }
</style>

<!-- This grid_container class is used by CSS styling and the id is used by JavaScript connection -->
<div class="grid-container" id="grid_container">
    <!-- content will be added here by JavaScript -->
</div>

<script>
    // 1. Make a connection to the HTML container defined in the HTML div
    var container = document.getElementById("grid_container"); // This container connects to the HTML div

    // 2. Define a JavaScript object for our http source and our data rows for the Living in the World grid
    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";
    var living_in_the_world = [
        {"flag": "0/01/Flag_of_California.svg", "comment": "Current Place", "description": "California - 16 years"},
        {"flag": "/thumb/f/f2/Flag_of_Massachusetts.svg/1920px-Flag_of_Massachusetts.svg.png", "comment": "Spawn Point", "description": "Massachusetts - 3 months"},
        {"flag": "thumb/0/03/Flag_of_Washington%2C_D.C.svg/1920px-Flag_of_Washington%2C_D.C.svg.png", "comment": "Favorite Vacation", "description": "Washington D.C."},
    ];

    // 3a. Consider how to update style count for size of container
    // The grid-template-columns has been defined as dynamic with auto-fill and minmax

    // 3b. Build grid items inside of our container for each row of data
    for (const location of living_in_the_world) {
        // Create a "div" with "class grid-item" for each row
        var gridItem = document.createElement("div");
        gridItem.className = "grid-item";  // This class name connects the gridItem to the CSS style elements
        // Add "img" HTML tag for the flag
        var img = document.createElement("img");
        img.src = http_source + location.flag; // concatenate the source and flag
        img.alt = location.flag + " Flag"; // add alt text for accessibility

        // Add "p" HTML tag for the description
        var description = document.createElement("p");
        description.textContent = location.description; // extract the description

        // Add "p" HTML tag for the greeting
        var greeting = document.createElement("p");
        greeting.textContent = location.comment;  // extract the comment

        // Append img and p HTML tags to the grid item DIV
        gridItem.appendChild(img);
        gridItem.appendChild(description);
        gridItem.appendChild(greeting);

        // Append the grid item DIV to the container DIV
        container.appendChild(gridItem);
    }
</script>

### What I do

- Currently in High School, Class of '28
- VP of Linux at CyberAegis
- Active competitor in CyberPatriot and the SoCal Cyber Cup
- AP Chemistry Tutor

<div class="grid-gallery">
  <img src="{{site.baseurl}}/images/about/dnhs.png" alt="DNHS">
  <img src="{{site.baseurl}}/images/about/cyberaegis.jpg" alt="CyberAegis">
  <img src="{{site.baseurl}}/images/about/mint.png" alt="Mint">
  <img src="{{site.baseurl}}/images/about/cyberpatriot.jpg" alt="CyberPatriot">
  <img src="{{site.baseurl}}/images/about/socal_2026.png" alt="Socal">
  <img src="{{site.baseurl}}/images/about/apchem.png" alt="AP Chemistry">
</div>

<style>
  .grid-gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 columns */
  gap: 10px; /* space between images */
  }

  .grid-gallery img {
  width: 100%;
  height: auto;
  object-fit: cover;
  }
</style>

### My Life

I spent a lot of my free time playing video games.

I often spend lots of time playing "interesting games" with my friends.

<img src="{{site.baseurl}}/images/about/appytree.png" alt="Appy Tree">

I am ethnically half Chinese and half Taiwanese.

I often celebrate many cultural traditions such as Chinese New Year and the Mid-Autumn Festival the with my aunts, uncles, and grandparents.

<img src="{{site.baseurl}}/images/about/cny.jpg" alt="Chinese New Year">