# Meta_FrontEndDev

##Notes

### id selctor
Operates on elements with a specific id
e.g.
<span id="latest">New!</span>

CSS:
#latest {
    background-color: purple;
}
### Class selector
<a class="navigation">Go Back</a>
<p class="navigation">Go Forward</p>
CSS:

.navigation {
    margin: 2px;
}
### Element and Class selector
<p class="Introduction"></a>

### Descendant Selector
Select HTML elements contained within another selector
e.g.
#blog h1 {
    color: blue;
}
Applies to all h1 elements within a blog id.

#blog div h1 {
    color: blue;
}
Applies to all h1 elements within a div element defined within a blog id

###Child Selector
Will only style direct children  e.g.
#blog > h1 {
    color: blue;
}
Will only style the direct children of #blog, not any levels below that h1 
(e.g. not #blog -> h1 -> h1)

