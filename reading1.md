Responsive website reacts quickly and positively to any changes. It is broken down to three main components.
- Flexible layout
    - Dynamically changes sizes depending on width. Common unit is em.
    - It does not advocate the use of fixed measurement units like pixels or inches
    - Formula for flexible layout is target/ context = result
    - min-width, max-width, min-height, and max-height are used as property to give flexibility.
- Media queries
    - Built as an extension to media type
    - Allows specificity between different styles of each browser and device
    - Each media query may include one or more expressions
    - Commonly found is `all, screen, print, tv, and braille, and including 3d-glasses`  
    - Can be manipulate by using Boolean true or false such that if media features allocate to true then style is applied, vice versa.
    - There are three logical operator which is and, not and only and allows another condition to be added.
        - Ie. `(min-width: 800px) and (max-width: 1024px)`
    - `not` negates query
    - Only helps to hide style from devices or browsers that don’t support media queries
    - min- and max- helps website to be responsive on desktops and mobile device equally.
    - `orientation` is used to set landscape or portrait orientation depending on if display is wider or taller.
    - One popular technique is mobile first.
    - it styles it in a way that scales smaller size first, and then use media queries to add styles as the viewport grows
        - ie ```@media screen and (min-width: 400px)  {...}
@media screen and (min-width: 600px)  {...}
@media screen and (min-width: 1000px) {...}
@media screen and (min-width: 1400px) {...}```
    - `viewport` meta tag with either height or width values will define height or width of that specific viewport respectively.
        - ie. ```<meta name="viewport" content="width=device-width">```

- Flexible media
Adaptive: easily modified for a new purpose or situation
- Mobile: separate website that is solely for mobile users.


