# gew.js
A JavaScript implementation of The Geneva Emotion Wheel (GEW).

### Usage
To use gew.js implementation, just include both _gew.js_ and _gew.css_ into your webpage.

The wheel will be generated using the following html markup:
```html
<div id="yourgewid" class="gew" data-input='yourinputid' data-required style="yourstyledefinition"></div>
```

Where:
* *yourgewid* is a defined id for this element;
* *yourinputid* is the id of the element that will be sended in the POST/GET (when using this gew in a form);
* *yourstyledefinition* is the basic style for your gew, such as width, height and font-size;
* *data-required* is an optional argument and will make the input generated (internally) by the gew.js be required (when using this gew in a form).

### About
> The Geneva Emotion Wheel (GEW) is a theoretically derived and empirically tested instrument to measure emotional reactions to objects, events, and situations.

##### Format
> The respondent is asked to indicate the emotion he/she experienced by choosing intensities for a single emotion or a blend of several emotions out of 20 distinct emotion families. The emotion families are arranged in a wheel shape with the axes being defined by two major dimensions of emotional experience.

> Five degrees of intensity are being proposed, represented by circles of different sizes. In addition, "None" (no emotion felt) and "Other" (different emotion felt) options are provided.

### Credits and more Information
* All the quotations from this document are from the [Geneva Emotion Research Group Page](http://www.affective-sciences.org/gew/). Please refer to this page for further information about the GEW. They are the authors of GEW and all the credits refering to the GEW itself belongs to them;
* The author of this implementation is not in the Geneva Emotion Research Group.

### License
This implementation of GEW and the GEW itself can be freely used for **non-commercial research purposes**. If you use the GEW or a modified version of it, please cite the instrument or its adaptation as follows: "…Geneva Emotion Wheel (GEW; see Scherer, 2005; Scherer, Fontaine, Sacharin, & Soriano, 2013). For commercial use of GEW, a license is required. For further information, refer to [Geneva Emotion Research Group Page](http://www.affective-sciences.org/gew/).
