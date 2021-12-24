# Neumorphism_Progress

# Installation :

1. Copy the neumorph_progress folder in your repo.
2. Add neumorphism as a dependency in your package.json file.

```json
{
  "dependencies": {
    "neumorphism": "file:../neumorph_progress"
  }
}
```

# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    text-color: black;
}
```

# Progress

<img src="sample_images/progressbar.png" width="" height="">

Import:
```html
<element name='neuprogress' src='../../../../../../node_modules/neumorphism/progress/progress.hml'></element>
```

Usage:
```html
<neuprogress progress="80%" width="300px" color="" height="20px" border="50px"></neuprogress>
```

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>