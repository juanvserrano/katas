## Act 2: The Cart

Ok, our layout is looking ace so far. Let's start with the cart. Things are about to become interesting.

### Iteration 2.1: The Model

Our Amazing Cart will, obviously, do amazing stuff.

- It must add items to cart
- Cart can be deleted a.k.a -> reset cart.
- Items can be updated from cart
- The cart will count repeated items to update quantities in the cart overview.
- The cart will calculate the total.

tip!tip!tip! You're free to choose the pattern you want here: go functional, go classy.

### Iteration 2.2: <AmazingCart>™

Let's create a component to render cart stuff:

- We need to print every product in the cart. title + price + quantity would be enough for now.
- The quantity part should have a `+` and a `-` to update quantity. If quantity equals 0, the item is no longer in the cart.
- Print the total price of the cart

### Iteration 2.3: Integrating stuff

nice! Our Cart code is looking fancy. Let's connect the dots now:

- We have an add to cart button + an add to cart method. Self explanatory, isn't it? :)
