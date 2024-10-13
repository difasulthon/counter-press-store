# counter-press-store

[Counter Press](https://counter-press.difasulthon.com/) online store for football shoes product

Table of Contents:

- [Counter Press](#counter-press)
  - [Links](#links)
  - [Features](#features)
  - [UI Designs](#ui-designs)
    - [Home Page](#home-page)

## Links

- Website/Frontend: <https://counter-press.difasulthon.com/>
  - Backend: <https://www.counter-press-backend.difasulthon.com/api>
- Repositories:
  - General: <https://github.com/difasulthon/counter-press-store>
  - Backend: <https://github.com/difasulthon/counter-press-backend>
  - Frontend: <https://github.com/difasulthon/counter-press-frontend>

Inspirations:

- <https://topscore.id/>
- <https://www.specs.id/>
- <https://www.ventela.com/>

## Features

- Home page
  - Hero section
  - Products catalogue. Example: <https://topscore.id/sepatu-bola>
- Product page
  - Image
  - SKU (stock keeping unit)
  - Name
  - Price
  - Description
  - Add to cart form: quantity input & add to cart button
- Shopping cart page
  - Product items to buy
    - Image, name, price, quantity, total (price x quantity)
    - Remove item
  - Link: continue shopping, go to products catalogue
  - Link: checkout
- Checkout page
  - Order summary
    - Product items to buy
    - Grand total of all product items to buy
- Place order / transaction is being processed

## UI Designs

- Figma: <https://www.figma.com/design/fQ3zoFPk66TK4WVqvtOm8s/CounterPressWeb?node-id=1-3&node-type=frame&t=EXrNZSUbP7B27P5k-0>

### Home Page

<img alt="Home Page" src="./designs/home.png" width="400" />

## Entity Relationship Diagram (ERD)

![ERD](./diagrams/diagram.png)
