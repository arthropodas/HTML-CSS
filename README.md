# HTML-CSS

inline and block 

block : this will take the full line of the html line
inline: this will take only the width of the element

convert the block into inline as using the display property as inline
and inline to block as the block

***********************div*************
/div a block element ie, it takes the entire line 


# Grid concepts

 <div style="display: grid; grid-template-columns: 200px 100px 100px 100px;"> //  it will take 4 columns
  <div style="display: grid; grid-template-columns: 200px 1fr;">// this could take the balance space in the line apart from the 200px


# flex box

it just like a css grid , but more flexible


# position

position fixed and position absolute

In position fixed: there is placed in the browser window, it will not scrollable and it remain on the page(side bar, header)
In position absolute: It is placed in the page, it will be scrollable and it not remains on the page

generally we absolute is not using, it usaully use inside the fixed component eg: close button for the side bar and when we give the position top: bottom: it will take that length based on the fixed componnent not the eniter page or window


position : abosolute inside  position:relative

# Media query

@media (max-width: 750px){
  .video-grid{
    grid-template-columns:1fr 1fr;
  }
}

it means the property gird-temaplete-columns 1f 1fr is support under (max-width): 750px 

if min-width: 1000px then it shopprts greater than 1000px