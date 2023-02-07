
![Groov V1](https://groov.itsakuro.xyz/v1/img/V1%20Logo.png)

# About
Groov is an upcoming icon pack created by [Akuro](https://github.com/itsakuro) for any project you want to use them for. Designed in Figma, there are currently over 50 icons and JavaScript file that allows you to use them on the web.

You can view the official site, including all the icons & documentation, [here](https://groov.itsakuro.xyz/).

# Adding icons
## Via HTML

Using Groov via HTML is the quickest & easiest way to add an icon to your site.

To add an icon, you can do so using this code:
```html
<groov-icon name="home"></groov-icon>
```
*\* Change the `name` attribute to the icon of your choice. You can find a list of icons [here](https://groov.itsakuro.xyz/v1/icons).*

### Styling
Via the custom `size` and `color` attributes, you can change the styling of your icon more conveniently.
#### Size
```html
<groov-icon name="home" size="300"></groov-icon>
```
*\* For example, setting the size to `300px` would set the width to `300px` (the height is set to `auto`). You can also exclude the "px" if you'd like.*

#### Color
```html
<groov-icon name="home" color="#1CE783"></groov-icon>
```

Live a little! Make your icons stand out with a custom color and size, make ‘em playful, make ‘em animate. You do you.
```html
<groov-icon name="home" color="#004736" size="1000px"></groov-icon>
```

## Via Javascript
You can also add icons through Javascript, but don't worry, it's easy to do, too!

All you have to do is create the element and set the `name` attribute. As seen above, you can also set the `size` and `color` attributes.
```javascript
let homeIcon = document.createElement("groov-icon");
homeIcon.setAttribute("name", "home");
homeIcon.setAttribute("size", "64px");
homeIcon.setAttribute("color", "#0F7");
document.body.append(homeIcon);
```
---
Woohoo! You're now a pro at adding Groov icons to your website. We should celebrate! 🪅

# Credit
All the icons and the logo were designed by [yours truly](https://github.com/itsakuro).

Designed in [Figma](https://figma.com)

[Groov](https://github.com/itsakuro/groov/) is licensed under the [CC-BY-SA-4.0](https://choosealicense.com/licenses/cc-by-sa-4.0/) license.

![CC-BY-SA-4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)
