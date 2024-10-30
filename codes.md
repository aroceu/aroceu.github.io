# code snippets (keep in mind)

A small repository of code that I'd like to save for future usage and/or regular updates for one of my websites. Feel free to use them as well.

# dreamwidth

## icon tables

Default icon link: [https://ceu.dreamwidth.org/file/3683.png](https://ceu.dreamwidth.org/file/3683.png)

<textarea><table cellspacing="50" cellpadding="50" border="1" align="center" style="text-align: center; font-family: 'Georgia', serif;">
  <tr>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
</tr>
<tr style="background: #ddd">
<td width="100">1</td>
<td width="100">2</td>
<td width="100">3</td>
<td width="100">4</td>
<td width="100">5</td>
</tr>
<tr>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
</tr>
<tr style="background: #ddd">
<td width="100">6</td>
<td width="100">7</td>
<td width="100">8</td>
<td width="100">9</td>
<td width="100">10</td>
</tr>
<tr>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
</tr>
<tr style="background: #ddd">
<td width="100">11</td>
<td width="100">12</td>
<td width="100">13</td>
<td width="100">14</td>
<td width="100">15</td>
</tr>
<tr>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
<td width="100" style="margin: 5px;"><img src="" height="100"></td>
</tr>
<tr style="background: #ddd">
<td width="100">16</td>
<td width="100">17</td>
<td width="100">18</td>
<td width="100">19</td>
<td width="100">20</td>
</tr></table></textarea>

## banner tables

<textarea><table cellspacing="50" cellpadding="50" border="1" align="center" style="text-align: center; font-family: 'Georgia', serif;">

<tr>
<td width="615px"><img src="https://aroceu.dreamwidth.org/file/58944.png" width="500"></td>
</tr>
<tr style="background: #ddd">
<td width="500px">1</td>
</tr></table>
</textarea>

# site specific

## /archive: new page (.md)

<textarea>---
title: 
author: 
layout: default

---

# 



---

![](/.png)
![](/.png)
![](/.png)
![](/.png)
![](/.png)</textarea>

## /music: new songs (5)

<textarea><table class="song">
        <tr><td id="title"></td><td></td>
        <td class="artist"></td></tr>
      </table>

      <table class="song">
        <tr><td id="title"></td><td></td>
        <td class="artist"></td></tr>
      </table>

      <table class="song">
        <tr><td id="title"></td><td></td>
        <td class="artist"></td></tr>
      </table>

      <table class="song">
        <tr><td id="title"></td><td></td>
        <td class="artist"></td></tr>
      </table>

      <table class="song">
        <tr><td id="title"></td><td></td>
        <td class="artist"></td></tr>
      </table></textarea>  

# backgrounds (css)

## desktop full size background image across browsers

<textarea> background: url(image url) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  background-attachment: fixed;
  background-repeat: no repeat;
</textarea>

## mobile full size background image

<textarea>
  html {
    background: url(image url) no-repeat center center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    height: 100%;
    overflow: hidden;
}
</textarea>

## full size background gradients

<textarea>
  background-image: linear-gradient(direction, color1 0%, color2 100%);
  background-repeat: no-repeat;
  background-attachment: fixed;
  min-height: 100%
</textarea>

# responsive (css)

## tablets (bigger)

<textarea>
  @media only screen and (max-width: 1025px) and (min-width: 769px) {
    
html {
-webkit-text-size-adjust: 100%;
}
}
</textarea>

## tablets (smaller)

<textarea>
  @media only screen and (max-width: 768px) and (min-width: 431px) {
    
    html {
-webkit-text-size-adjust: 100%;
}
}
</textarea>

## mobile
<textarea>
  @media only screen and (max-width: 430px) and (min-width: 0px) {

html {
-webkit-text-size-adjust: none;
}
    
}
</textarea>

# specific use cases

For removing top page padding in Firefox:

<textarea>
  *{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</textarea>

# php

## include syntax

<textarea><?php include('url.php') ?></textarea>