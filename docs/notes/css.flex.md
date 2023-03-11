---
id: l7o8zwvyg9sr35srta0ndyp
title: Flex
desc: ''
updated: 1678553199844
created: 1678515222997
---
### CSS flex layout

1. flex: always applied to the the outer containers. In this e.g container-flex div is used
to apply flex.

1. by defining the display flex property we can do chnages inside the container.

1. by default direction of flex is horizontal

1. flex-direction: this property can change the behaviour of flex. E.g 
    1. To place the div's vertically 
    ```css
    flex-direction: column;
       ```
    1. To place the div's horizontally
    ```css
    flex-direction: row
    ```

1. most used application is "nav bar"

1.  ### Axis in flex
    1. **align-self**
        : applied to the items in a container, via which you can move your items in any direction. Good to be applied to single items for it's movement.  
    1. **align-content**
        : only works when we have multiple lines of items in our container. It is going to implement in cross-axis and differ according to the flex direction.
    1. **jusify-content**
        : The justify content property is going to implement in main-axis and the main axis can differ according to the flex direction.
    1. **align-items**
        : The align items property is going to implement in cross-axis and differ according to the flex direction.

    1. For flex-direction: row : The main axis is going to be x-axis

     ```mermaid
       flowchart LR
        0 --> |main-axis| 1
     ```

     ```mermaid
       flowchart TD
        0 --> |cross-axis| -1
     ```

    1. For flex-direction: column : The cross axis is going to be y-axis
     ```mermaid
       flowchart LR
        0 --> |cross-axis| 1
     ```

     ```mermaid
       flowchart TD
        0 --> |main-axis| -1
     ```
1. **flex-basic**
    : Overwrites the property of height/width depeding upon the direction of the flex. These property are applied to the items, not to the container
    1. If the flex-direction is row, then it is going to increase width of the item.
    1. If the flex-direction is column, then it is going to increase height of the item.
    1. learn more about [[flex basis, flex-grow, flex-shrink|flex-properties]]