---
toc: true
layout: post
description: Table using HTML and javascript fragments
categories: [Markdown, week-4]
title: Table using HTML and Javascript fragments
author: Aditya Ajay Nawnadhar
show_tags: true
comments: true
image: images/postimage5.png
---

# Making the table-

<table id="mine" style = "width:100%">
    <tr>
        <th>Countries</th>
        <th>Best food</th>
    </tr>
    <tr>
        <td rowspan="3">Korea</td>
        <td>Korean BBQ</td>
    </tr>
    <tr>
        <td>Kimchi</td>
    <tr>
        <td>Bibimbap</td>
    </tr>
    <tr>
        <td rowspan="3">Japan</td>
        <td>Sushi</td>
    </tr>
    <tr>
        <td>Tempura</td>
    <tr>
        <td>Udon</td>
    <tr>
        <td rowspan="3">China</td>
        <td>Fried Rice</td>
    </tr>
    <tr>
        <td>Kung Pao Chicken</td>
    <tr>
        <td>Dumplings</td>

<script>
function myFunction() {
  document.getElementById("mine").style.fontSize = "35px"; 
  document.getElementById("mine").style.color = "blue";
}
</script>

<center><button type="button" onclick="myFunction()" style="background: red">Click Me!</button></center>
