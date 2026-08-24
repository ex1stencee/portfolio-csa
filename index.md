---
layout: post 
title: Portfolio Home 
hide: true
show_reading_time: false
---

Hi! My name is Jacob Chou. This is my AP CSA Portfolio

### MCQ Lessons:
<nav class="unit-navbar" style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;align-items:center;padding:12px 0;margin-bottom:24px;border-radius:8px;">
  <a class="unit-navbar-link" href="{{ site.baseurl }}/mcqs/1/1" style="padding:8px 16px;border-radius:6px;border:1px solid;text-decoration:none;font-weight:500;transition:background 0.2s;">1.1</a>
  <a class="unit-navbar-link" href="{{ site.baseurl }}/mcqs/1/2" style="padding:8px 16px;border-radius:6px;border:1px solid;text-decoration:none;font-weight:500;transition:background 0.2s;">1.2</a>
  <a class="unit-navbar-link" href="{{ site.baseurl }}/mcqs/1/3" style="padding:8px 16px;border-radius:6px;border:1px solid;text-decoration:none;font-weight:500;transition:background 0.2s;">1.3</a>
</nav>

### Important Information

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
    <a href="{{site.baseurl}}/github/pages/jokes" style="text-decoration: none;">
        <div style="background-color: #FA4E3C; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s; text-align: center;">
            <div>Notebooks & Jokes</div>
            <div style="font-size: 13px; font-weight: normal; margin-top: 8px;">
                Fun with JavaScript and Jupyter Notebooks
            </div>
        </div>
    </a>
    <a href="{{site.baseurl}}/github/pages/anatomy" style="text-decoration: none;">
        <div style="background-color: #fa983c; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s; text-align: center;">
            <div>Anatomy</div>
            <div style="font-size: 13px; font-weight: normal; margin-top: 8px;">
                Explore the structure of a GitHub Pages site
            </div>
        </div>
    </a>
    <a href="{{site.baseurl}}/github/pages/theme" style="text-decoration: none;">
        <div style="background-color: #ffd12b; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s; text-align: center;">
            <div>Theme</div>
            <div style="font-size: 13px; font-weight: normal; margin-top: 8px;">
                Learn about theme templates and layout of SASS files
            </div>
        </div>
    </a>
    <a href="{{site.baseurl}}/github/pages/markdown" style="text-decoration: none;">
        <div style="background-color: #50ff5c; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s; text-align: center;">
            <div>Markdown</div>
            <div style="font-size: 13px; font-weight: normal; margin-top: 8px;">
                Master Markdown for content creation
            </div>
        </div>
    </a>
    <a href="{{site.baseurl}}/github/pages/jekyll" style="text-decoration: none;">
        <div style="background-color: #45b8ff; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s; text-align: center;">
            <div>Jekyll</div>
            <div style="font-size: 13px; font-weight: normal; margin-top: 8px;">
                Understand Jekyll static site generation
            </div>
        </div>
    </a>
    <a href="{{site.baseurl}}/github/pages/hacks" style="text-decoration: none;">
        <div style="background-color: #b445ff; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s; text-align: center;">
            <div>Hacks</div>
            <div style="font-size: 13px; font-weight: normal; margin-top: 8px;">
                Apply your knowledge with hands-on challenges
            </div>
        </div>
    </a>
</div>

##### Notebooks & Jokes:
Jupyter Notebooks can be run in VSCode through the play button on the cells. The cells in Jupyter notebooks can run different programs, such as javascript.

##### Anatomy:
Github pages has a lot of different files that are associated with it, each serving its own unique purpose, such as _config.yml configuring Jekyll, index.md acting as the home page (the one you are on right now!), and .gitignore hiding sensitive or unneccessary files from Github.

##### Theme:
Themes can be easily switched through the configurations on a site. By implementing these CSS variables at the root level, we can switch the theme universally and easily through the Makefile or _themes directory.

##### Markdown:
Markdown is a shorthand for HTML, and is used in this context has Github pages can effectively turn Markdown into HTML. Through the use of Jekyll and Liquid, programmers can use Markdown to easily turn their ideas into a site.

##### Jekyll
Jekyll is a site generator which takes plain text in markdown and jupyter notebooks and publishes it like a HTML site. In this class, we will be using Jekyll to publish our sites, and in this case, our portfolios.

##### Hacks:
Hacks are a series of challenges that test the student on the material that they are supposed to learn. These hacks are often published to the student's portfolio.

<!-- 
### Development Environment


> Coding starts with tools, explore these tools and procedures with a click.

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="https://opencodingsociety.com" style="text-decoration: none; display: inline-flex; align-items: center; gap: 8px; padding: 10px 14px; border: 1px solid #FA8072; border-radius: 6px; font-weight: 700; transition: all 0.3s;">
        <img src="{{ '/favicon.ico' | relative_url }}" alt="OCS logo" style="width: 16px; height: 16px;">
        OCS
    </a>
    <a href="https://github.com/Open-Coding-Society/portfolio" style="text-decoration: none; display: inline-flex; align-items: center; gap: 8px; padding: 10px 14px; border: 1px solid #FFF; border-radius: 6px; font-weight: 700; transition: all 0.3s;">
        <svg style="width: 16px; height: 16px; fill: currentColor;" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
            <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/>
        </svg>
        GitHub
    </a>
    <a href="https://vscode.dev/" style="text-decoration: none; display: inline-flex; align-items: center; gap: 8px; padding: 10px 14px; border: 1px solid #007ACC; border-radius: 6px; font-weight: 700; transition: all 0.3s;">
        <svg style="width: 16px; height: 16px; fill: currentColor;" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
            <path d="M11.34 0L5.66 5.39l-2.4-1.8L1.19 4.82v6.36l2.07 1.23 2.4-1.8L11.34 16 15 14.23V1.77L11.34 0zm.59 11.57l-3.86-3.54 3.86-3.54v7.08z"/>
        </svg>
        VSCode.dev
    </a>
</div>

<br>

### My Lessons

> Foundations in Tech are essential, click to see some of my lesson creations.


<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="{{site.baseurl}}/code/javascript" style="text-decoration: none;">
        <div style="background-color: var(--green); color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s;">
           JS Basics
        </div>
    </a>
    <a href="{{site.baseurl}}/game/essentials/variables" style="text-decoration: none;">
        <div style="background-color: var(--blue); color: white; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s;">
           JS Variables
        </div>
    </a>
    <a href="{{site.baseurl}}/gamerunner" style="text-decoration: none;">
        <div style="background-color: var(--warn); color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s;">
           Gamerunner
        </div>
    </a>
    <a href="{{site.baseurl}}/network/stack" style="text-decoration: none;">
        <div style="background-color: var(--orange); color: white; padding: 10px 20px; border-radius: 5px; font-weight: bold; transition: transform 0.2s, box-shadow 0.2s;">
           Networking
        </div>
    </a>
</div>

<br>

### Class Progress

> Here is my game progress through coding, click to see these in the browser

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="{{site.baseurl}}/snake" class="btn">
        Snake
    </a>
    <a href="{{site.baseurl}}/gamify/parallax" class="btn" style="background-color: var(--green); ">
        Fish
    </a>
    <a href="{{site.baseurl}}/gamify" class="btn" style="background-color: var(--teal);">
       Gamify
    </a>
    <a href="{{site.baseurl}}/cs-pathway" class="btn" style="background-color: var(--orange);">
       CS Pathway
    </a>
</div>

<br> -->
