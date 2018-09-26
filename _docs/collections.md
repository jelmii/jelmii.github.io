---
layout: doc
title: The Ritz-Carlton, Marriott
subtitle: A result is something that occurs as a consequence of some action. 
author:
tags: featured
---

#### Sections in this article
{:.no_toc}
* TOC
{:toc}

A result is something that occurs as a consequence of some action. The result of your practical joke is a puddle of water on the floor and a lump on your cousin's head where the bucket hit him.

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}
</style>
</head>
<body>

<h2>Responsive "Meet The Team" Section</h2>
<p>Resize the browser window to see the effect.</p>
<br>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="http://www.bankhing.com/assets/posts/trcdove.jpg" alt="Jane" style="width:100%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO & Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="/w3images/team2.jpg" alt="Mike" style="width:100%">
      <div class="container">
        <h2>Mike Ross</h2>
        <p class="title">Art Director</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="/w3images/team3.jpg" alt="John" style="width:100%">
      <div class="container">
        <h2>John Doe</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>

</body>
</html>

## Image Lightbox Example
Nunc porta malesuada porta. Etiam tristique vestibulum dolor at ultricies. Proin hendrerit sapien sed erat fermentum, at commodo velit consectetur.

{% include image.html img="image1.png" style="wide" lightbox="true" alt="Alt for image" caption="Image in lightbox" %}

Etiam vestibulum risus vel arcu elementum eleifend. Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet, tempus metus quis, pharetra turpis. Phasellus at massa sit amet ante semper fermentum sed eget lectus. Quisque id dictum magna, et dapibus turpis.

## Example Of Code Block
In accumsan lacus ac neque maximus dictum. Phasellus eleifend leo id mattis bibendum. Curabitur et purus turpis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae;

```html
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="{{ "/assets/css/main.css" | relative_url }}">
  <link rel="shortcut icon" type="image/png" href="{{ "assets/img/favicon.png" | relative_url }}" >
  <script src="{{ "/assets/js/main.js" | relative_url }}"></script>
</head>
```

## Text and Quote
Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet, tempus metus quis, pharetra turpis. Phasellus at massa sit amet ante semper fermentum sed eget lectus. Quisque id dictum magna turpis.

> Etiam vestibulum risus vel arcu elementum eleifend. Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet

In accumsan lacus ac neque maximus dictum. Phasellus eleifend leo id mattis bibendum. Curabitur et purus turpis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae;

Etiam in fermentum mi. Sed et tempor felis, eu aliquet nisi. Nam eget ullamcorper arcu. Nunc porttitor nisl a dolor blandit, eget consequat sem maximus. Phasellus lacinia quam porta orci malesuada, vel tincidunt.
