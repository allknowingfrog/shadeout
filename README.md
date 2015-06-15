### shadeout
Color shading and blending provided by Stack Overflow user [Pimp Trizkit](http://stackoverflow.com/questions/5560248/programmatically-lighten-or-darken-a-hex-color-or-rgb-and-blend-colors).

### Defaults
color: '#0000FF'
color2: '#FFFFFF'
increment: 25

### Usage
$(ELEMENT).shadeout({}); --Uses all defaults

$(ELEMENT).shadeout({
    color: '#ff0000',
    increment: 75
}); --Uses only color2 default

$(ELEMENT).shadeout({
    color: '#33cc33',
    color2: '#ff00ff',
    increment: 25
}); --Uses no defaults, but make a beautiful blend of colors
