# DomAnimationFunction
Animate dom nodes. 

Only works for nodes that have have style property in the format of x number of unit's or "" if none like opacity.

As in: $node.style.marginLeft = "0" + "px"; //so set config.unit = "px";

or     $node.style.top = "10" + "%";  // config.unit = "%";


and Opacity as in: $node.style.opacity = 0.7 + ""; //resulting in just 0.7;

