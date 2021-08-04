# Deliveroo_coderpad_exercise

We are going to build a piece of software which takes a list of dishes our new chef can make and builds a menu for our customers.

```
food_categories = { 
  starters: ["peanuts", "bread", "salad", "dumplings"],
  mains: ["steak", "bento", "chicken", "pizza", "sandwich", "wrap", "sushi", "burger", "hotdog", "pasta", "burrito", "taco", "rice"],
  desserts: ["apples", "strawberries", "cheese", "pie", "icecream", "cake"]
}

chef_dishes = ["strawberries", "dumplings", "pasta", "rice", "apples", "salad", "peanuts", "cheese", "bento", "sushi"]
```

We would like to create a menu listing all the dishes our chef can cook, with the starters first, mains second and desserts last.
This is an example of what the chef_dishes above might result in:

```
==== Just Falafs ====
      ~ Menu ~
Starters
dumplings, peanuts or salad
Mains
bento, sushi, pasta or rice
Desserts
apples, strawberries or cheese
```
