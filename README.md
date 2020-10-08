# HTML

* Angle brackets
  * `<` left angle bracket
  * `>` right angle bracket
* Slash
  * `/` forward slash
* usages
  * `<tag>` opening tag- surrounded by the two angle brackets
  * `</tag>` closing tag (opening tag with forward slash before it)

* `=` used to set attributes

* usages
  * `<tag attribute-name="value">`


# CSS

## SELECTORS

### USAGE

```css
selector {
  property: value;
  property: value;
  property: value;
  property: value;
}
```

### LIVE USAGE

```css
  body{
    background-color: red;
    width: 100px;
    height: 100px;
  }
```


### EXAMPLE OF SELECTORS
---

1. `#name` 

> `tag with id="name"` e.g

```HTML
<p id="name"> hello </p>
```

usage

```css 
#name{
  
}
```

2. `.name`

> `tag with class="name"` e.g

```HTML
<p class="name"> hello </p>
```

usage

```css
.name{

}
```

3. `body`

> `tag body` e.g

```HTML
<body>

</body>
```

usage

```css
body{

}
```