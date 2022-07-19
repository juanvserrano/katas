

## Act 1: The Layout

### Iteration 1.1: Show me the cards!

- The card must have some basic contents:
  - Image :)
  - Content: Title + and add to cart button

- The Card will have two different **layouts**: 
  - `overlay`: will have the image as background. The content will be on top. But wait! In order to pass our accesibility standards, the card should have a gradient (from transparent to black :P) between image / content.
  - `grid`: the classic one. Image on top which should have a 16:9 scale + content below. **No** gradients here.

### Iteration 1.2: Versatile is my middle name

Hey! This is starting to look reaaaally good. Nice job! But...what if we add some more?

- The `grid` layout should be versatile enough to:
  - Be horizontal: image on the left; content on the right
  - Be Vertical: image on top; content right after the image.

### Iteration 1.3: The G.R.I.D

Wow, did you see that? We can do whatever we want now. Let's paint a grid:

- We will have a two columns layout with: <ProductsGrid> + <AmazingCart> (which will be built later on)
- The Products Grid will have 3 columns and will paint all products using our brand new card. We don't have a strong opinion about what's the best layout for our grid, so let's go with the classic one(a.k.a image top + content below).









