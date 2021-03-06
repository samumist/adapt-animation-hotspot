# adapt-animation-hotspot  

<img src="assets/animation-hotspot.gif" alt="animation-hotspot" align="right" height="150px">

**Animation Hotspot** is a component having images and hotspots over that enables a user to click and display a detailed popup.

Development of this component is in-progress.

### Attributes

[**core model attributes**](https://github.com/adaptlearning/adapt_framework/wiki/Core-model-attributes): These are inherited by every Adapt component. [Read more](https://github.com/adaptlearning/adapt_framework/wiki/Core-model-attributes).

**_component** (string): This value must be: `animation-hotspot`.

**_animation** (boolean): Whether animation required or not.

**_delay** (string): Time interval between display of 2 images in milliseconds.

**_navigation** (string): linear or random.

**_bg** (string): Background image reference. v0.0.1 requires it to display component correctly in responsive.

**_items** (array): Each *item* represents one choice for the animation frames and contains values for **_graphic** and **_highlight** if required.

**_hotspots** (array): Each _hotspot specifies the dimension, position and border radius (optional) of the hotspot.

**_feedback** (array): Feedback popup text opens when click on hotspot.

### Limitations

Not identified yet. 

### Browser/platform specification

Intended to develop standard Adapt browser/devices specifications. Development of this component is in-progress.

----------------------------
**Version number:**  1.0.0 
**Framework versions:** 2.0.15  
**Accessibility support:** WAI AA    
**Author / maintainer:** Kunj B Sharma <kunjsharma@hotmail.com>    
