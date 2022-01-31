# miniproject1.0
1) use the create canvas function
2) use rectangles to set up the background
    four rectangles, all equal size
    the x coordinate of all corners is either 0, windowWidth/2, or windowWidth
    the y coordinate of all corners is either 0, windowHeight/2, or windowHeight
    use fill fucntion to change the colors
        black is 0, in the bottom right
        add 60 to lighten the next rectangle in the grayscale
        next darkest is bottom left, then top right and lightest is top left
3) use bezier function to draw petals about the center
    center = (windowWidth/2, windowHeight/2)
    the center is all the anchor points for all the bezier functions
    need eight bezier functions
    each bezier has a set of anchor points at two corners of a rectangle around the perimeter
    the bezier inside a reactangle will have anchor points in corners of the same rectangle
    each rectangle has two sets of corners along the perimeter
        so each rectangle will have two bezier petals
    use stroke function to shade the petals inverse of the rectangles


