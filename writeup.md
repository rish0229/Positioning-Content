                      POSITIONING CONTENT

To make layout of our web-page or to position our content either individually
or the group,  we learnt three concept. The first is changing display property
to inline-block, which helps us to make elements display in side by side column
in a single row. When this properly is applied to block level elements or inline
elements then few properties of these elements changes like block level elements 
take space only according to it's content & inline level elements accept the width
& height property.
                                 The second way to make a layout is using floats.
This helps us to position our elements either on left or right side of the parent
container element. Applying floats, changes the normal flow of the elements & some 
properties of that element also changes like block level elements start taking space
according to it's content. The major fallback of using floats is that the parent element
of element on which float is applied doesn't take height according to the content
so to overcome this we need to do some workaround. There are few ways to overcome this but
the best way is to use clearfix thechnique.
                                Now the third concept in positioning content is to 
use position property on the element which we want to position on the page. Position
properly accepts four values static(default), relative, absolute and fixed out of 
which the easiest is relative positioning which helps us to position our element 
w.r.t its current position. In relative positioning original place of the element is maintained.
In absolute positioning the element is positioned w.r.t nearest relatively or absolutely
positioned parent element. The absolutely positioned element leaves it's original position
hence the other elements takes it's place. In fixed positioning the element is positioned
w.r.t browser window and it's position is fixed on the screen and it doesn't move with
the webpage. On all the relatively, absolutely or fixed element we can use all the box
offset properties to position it according to our need.

 Thank you.