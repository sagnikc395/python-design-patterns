# Abstract Factory

## Usage:

- Creational design pattern that lets us product families of related objects without specifying their concrete classes.

## Eg:

- Consider that you are creating a furniture shop simulator.
- Our code consists of classes that represent:

  - A family of related products, like Chair, Sofa , Coffeetable.
  - Several variants of this family, eG: products Chair, Sofa,Coffetable are availabe in these variants : Modern, Victorian , ArtDeco.

- TODO:
  1. Need a way to create individual furniture objects so that they match other objects of the same family. Customers get quite mad when they receive non-matching furniture.
  2. Also, we don't want to change existing code when adding new products or families of products to the program.
  3. Furniture vendors update their catalogs very often, and we wouldn't want to change the core code each time it happens.

## Solution:

-
