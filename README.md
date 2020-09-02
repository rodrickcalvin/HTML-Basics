- live server for VS Code to run static files locally
# HTML

## TAGS
---
### METADATA TAGS

SEO meta tags for metadata to describe the site. They also enable the page to be displayed when keywords or key tags are searched for.
```HTML
<head>
    <meta name="keywords" content="//keywords go here, and here....">
</head>
```

### PARAGRAPH VS ARTICLE TAGS
These are used to display text
| `<p>` | VS |`article` |
| :------: | -- |:---------: |
| Has vertical padding | | Has no padding |
______________________________________________________________

### IMAGE TAGS
Advised to use CDN's for example: the [cloudinary](cloudinary.com) with up to 500MBs of media storage. Later as you work on projects you can invoice a client according to memory used up.

Always have an `alt=""` attribute in your self closing image.

You can use online editors like [remove bg](remove.bg) incase you want to edit pictures.
______________________________________________________________

### ANCHOR TAGS & LINKS
These are used as link to another page on the websites or other webites. They  have an `href=""` property pointing to the next website or page.
______________________________________________________________

### SUB AND SUP TAGS
These are the subscript and superscript tags used turn text into a subscript or superscript like powers of 2 respectively.
```HTML
<p>23<sub>2</sub></p>
<p>14 <sup>th</sup> of January</p>
```
______________________________________________________________

### ASIDE TAG
```HTML

```
______________________________________________________________

### DETAILS TAG
```HTML

```
______________________________________________________________

### AUDIO TAG
```HTML

```
______________________________________________________________

### I-FRAME TAG
```HTML

```
______________________________________________________________

### PROGRESS TAG
```HTML

```
______________________________________________________________

### TABLE TAG
```HTML

```
______________________________________________________________

### FORM AND INPUT TAG
One can use these tags to come come up with an everyday form to collect data. To sign in and sign up.
 
An easy way to create one is using the [form Spree](formspree.io)
```HTML
    <form action="">
        <label for="">Name</label>
        <input type="text" name="" id="">
    </form>
```
______________________________________________________________

## WRITING SPECIAL CHARACTERS
For special characters in HTML, use `&` plus a "keyword" to give you a special character like the copyright sign `"©"`. To achieve this we do this:
```HTML
<p>All Rights Reserved. 2020 Copyright &copy;</p>
```


##  COMMENTING IN HTML
You can always write HTML comments like this
```HTML
<!-- comment text or code goes here -->
```
______________________________________________________________
