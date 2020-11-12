CSS Position Tutorial

https://www.youtube.com/watch?v=gD3G67oPg-w&list=PLDyQo7g0_nsUjf046cCHKJ16U1SoXrElZ&index=3



    - static: The standalone one
    - relative: Allows you to access the following:
        - top (e.g. |-> "top: 20px" will move the box 20px from its top - meaning, to its bottom)
        - bottom (e.g. |-> "bottom: 20px" will move the box 20px from its bottom - meaning, to its top)
        - right (e.g. |-> "right: 20px" will move the box 20px from its right - meaning, to its left)
        - left (e.g. |-> "left: 20px" will move the box 20px from its left - meaning, to its right)
        - BONUS (e.g. |->  "right: 100%" will move the item to its left using its parent as reference. 
        So if the parent is 200px width, moving the child 100% left/right will move it 200px left/right. 
    - absolute: Allows you to access the same features as "relative". However, it will use as reference
    the entire website - unless its parent has a "relative" position, then it will use its parent as reference.
        (I'm not sure about how it behaves when scrolling around, I guess I will have to update this later on)
    - fixed: It's the same as absolute but it doesn't care about you scrolling around. 
        (I guess this means that absolute does care about you scrolling around... I hope I guess right)
    - sticky: It switches in between position "static" and "fixed".
