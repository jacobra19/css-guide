# **CSS UNITS GUIDE**

## **RELATIVE UNITES**

### **em**

* change accordingly to the font-size of the parent element
* **Use for:** typography, and elements related to typography
**[example 1](https://codepen.io/dixita0607/pen/QQNomG)**
**[example 2](https://codepen.io/dixita0607/pen/LQNoOL)**

### **rem**

* relative to the root element 
```
html{
    font-size: 20px;
}
```
as a result 1rem will have the size of 20px, 2rem=40px, 0.5rem=10px and so on...

* **Used as:** a more robust and predictable alternative to em and ex, and employed for the same purposes, including @media query breakpoints.
* **Don’t use:** if you wish to support IE8 and earlier. Or, use the unit but include a fallback (by providing an alternate measurement in a more common unit before the rem measurement) or a polyfill.

**the default value for font-size is 16px**

### **Percentage (%)**
* **Use for:** making responsive images and containers; setting height on the body in some cases.
* **Don’t use for:** typography.
### **ex**
* relative to the height of 'x' character in lowercase of the parent element (depands on the font)
### **ch**
* relative to the width of '0'(zero) character of the parent element (depands on the font)

### **Viewport units vw/vh**
* viewport is the size of the user's display size
* 1vw/1vh is 1% of the display size screen
* vw/vh changes between devices
* **Use for:** responsive typography; “perfect” responsive containers.
* **Don’t use in:** media queries, as the viewport will never attain a width of less than 100vw or a height less than 100vh: by definition, those numbers correspond to the current dimensions of the browser window, no matter how large or small the screen or device is. Be aware of the unit’s lack of support in IE8.

### **vmin/vmax**
* vmin is the small between vh and vh
* vmax is the large between vh and vh
* portait mode: 1vmin=1vw and 1vmax=1vh
* landscape mode: 1vmin=1vh and 1vmax=1vw
![example image](https://weeblytutorials.com/wp-content/uploads/2017/04/Weebly-blogs-example.png)

## **ABSOLUTE**

### **Pixels(px)**
* 
### **Points(pt)**
* 1pt=72px
### **Inches(in)**
* 1in=96px=72pt
### **cm and mm**
* 1cm=~37.8px
### **pc**
* 1pc=12pt=16px
* 

