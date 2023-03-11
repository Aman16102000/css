---
id: 3tlounmnvsubsngv7kjgr92
title: Flex Properties
desc: ''
updated: 1678550741702
created: 1678516831722
---


### Flex properties

1. flex-basis
    : Overwrites the property of height/width depeding upon the direction of the flex. These property are applied to the items, not to the container
1. using this flex-basis we have two more propertiers of flex and that is 
    1. flex-grow
    1. flex-shrink

1. flex-grow
    : as the name sugggest, on expanding the web page it will grow the height/width of the item depending upon the flex-direction. It will not grow more the px mentioned in flex-basis and this case is only valid when the growth factor is equals to 0.
1. flex-shrink
    : as the name suggest, on shrinking the we page, it will shrink the height/width of the item depending upon the flex-direction. It will not shrink more than the px mentioned in the flex-basis and this case is not valid when the shrick factor is equals to 0.
1. we can also write flex-grow/shrink/basic in one property. For e.g 

```css
flex: grow shrink basis
```

1. conclusion
    : The items will grow or shrink depending upon the growth or shrink factor.