# code snippets (keep in mind)

A small repository of code that I'd like to save for future usage and/or regular updates for one of my websites. Feel free to use them as well.

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