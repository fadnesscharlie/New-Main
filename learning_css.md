
# Learning Git

[Home](https://fadnesscharlie.github.io/Reading-notes/) &nbsp;
[Growth Mindset](https://fadnesscharlie.github.io/Reading-notes/growth_mindset) &nbsp;
[Learning Markdown](https://fadnesscharlie.github.io/Reading-notes/learning_markdown) &nbsp;
[Learning HTML](https://fadnesscharlie.github.io/Reading-notes/learning_html) &nbsp;
[Learning Git](https://fadnesscharlie.github.io/Reading-notes/learning_git)
[Learning CSS](https://fadnesscharlie.github.io/Reading-notes/learning_css)

![Image of Css]()

## Linking CSS File

There are 3 ways of adding CSS to your file. You can place your CSS inside your element, on your header, or link an external CSS style sheet.

While placing your CSS in your element seems fairly simple, you can see what CSS is being done to just that section, simple!

Adding CSS to your header. This makes it simple, head to the top of the page, and see all the CSS that is on that page.

Linking your CSS page. Why would you want to create a whole new page and have all your CSS there when you place it in your file? One big reason why is with an external CSS, you can create templates. And have CSS effect the same elements on different pages. You would not have to copy over every single CSS you made for that element on each page, and instead you can write one page, link the file, and the file will show the same CSS throughout all of your pages. 

Finally, what happens if I wirte my CSS in my page, and the exrnal page. As the page is being read, we add the link to your CSS at the top, it then reads down from there, Only the bottom most CSS of any taged element will display.

## Elements

As its own box

There are rules in CSS, they contain two parts, a selector and a declaration. inside the declaration there is Property and a Value.

A selector would be:  
<b>p {</b>
    font-family: Arial;}

A declaration would be:  
p {
    <b>font-family: Arial;}</b>

Inside the declaration there is a property and a value:
The property is:  
p {
    <b>font-family:</b> Arial;}

The value is:  
p {
    font-family: <b>Arial;}</b>

## Seclectors

There many differnt types of selectors, from:

* 'universal: * {}'
* 'type: h1, h2 {}'
* 'Class: .note {}'
* 'ID: #Instroduction {}'
* 'child: li>a {}'
* 'descendant: p a {}'
* 'adjacement sibling: h1+p {}'
* 'general sibling: h1~p {}'

## Colors

Brings your site to life. You can place color anywhere on the page you want, if you want to target just the text, the block of text, background, border of an image, etc. It can make important things stand out and make your site come to life. 

Picking out your color comes in three different types of ways. There is the actual word of the color, a six digit code, and a RGB of red, green blue. 

## Contrast

Contrast gives light and darkness to certain areas and colors. Which bring additonal light

## HSL Colors

hue, Saturation, Lightness

## CSS3 RDGA