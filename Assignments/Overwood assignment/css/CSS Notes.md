# CSS
CSS("CASCADING STYLE SHEETS) is a *"styling"* language used on markup languages like HTML. It enables presentation of content with the help of things like page grids or layouts, colours and fonts.

With great presentation comes easy content accessibility, user comfortability and experience and developer or company expression to its clients or customers.

## COLOURS AND DESIGN
Colours used always give out a message on a website or a house or even your every day clothing.
It is professional to always have colours that blend as a frontend developer. It is not an easy task to pick for yourself blending colours inline with your main colour unless directed and chosen by the owner of the site.
More clarity is illustrated in this ["How to Choose Website Colour Schemes"](https://websitesetup.org/website-color-schemes/) blog hence the use of the [coolors](coolors.co) website.

If you are choosing your theme colours basing on an image or a logo. you can use [ginifab]() to give you the hex of the colour and later on move on to get the blending colours.

## STYLING
With CSS giving us the power of using layouts, colours and fonts, CSS communicates with HTML using selectors and declaration blocks.

Selectors help you select the HTML element or document while declaration blocks hold the property value pairs

1. To select one element or a kind of element around the HTML file, we use:
```CSS
h1{ /* the "h1" is a selector pointing to all h1 elements in HTML*/
    /* The {curry braces} are the declaration blocks*/
  font-weight: bold;
    /* "font-weight" is the property.*/
    /* bold is the value.*/
}
```
2. To select the whole HTML document, we use:
```CSS
 *{
    //code goes here
  }
```