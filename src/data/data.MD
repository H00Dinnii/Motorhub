# Dummy Data for MotorHub

## Product Images

## Files

- **products.ts**: A list of products having:
  - id
  - title
  - image
  - avgRating
  - ratings
  - price
  - oldPrice (optional)
- **product.ts**: Product details
  - id
  - title
  - _description_
  - image
  - _images_ (array of images)
  - _options_ (array if possible variation/options)
  - avgRating
  - ratings
  - price
  - oldPrice (optional)
- **cart.ts**: Items in the cart
  - id
  - item
  - quantity
  - option (selected option)
