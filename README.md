<div align=center>
  
  <img style="height: 100px; width: auto;" src="https://github.com/Gabyface910/munchy/blob/main/munchylogo.png?raw=true"> 
  
  # Munchy
  
  

  The open-source recipe web app

</div>

***
How to use Munchy:
1. Go to https://gabyface910.github.io/munchy
2. Search for some food
3. Click on a recipe card
4. Enjoy the snacks!

> [!NOTE]
> ### About the Munchy API
> The API to power Munchy is located in the [munchy-api repo](https://github.com/Gabyface910/munchy-api).
> It is quite a large file so use a fast browser.
> Munchy API is open source so you can see what it looks like. Check out [index.html](https://github.com/Gabyface910/munchy/blob/main/index.html) to see how to perform Munchy API calls. The Munchy API is based off of [TheMealDB API](https://themealdb.com), but with no paid tiers. Although, if you need a good API search, check out TheMealDB.
> You can get a Python library to filter munchy snacks by running this:
> ```
> pip install munchy
> ```
> Filter the meals like this:
> ```python3
> import munchy
> food = munchy.fetch()
> print(munchy.filter_meals(food, "category", "chicken"))
> # This returns a list object with all the foods with the category "chicken".
>
> print(munchy.filter_meals(food, "meal", "chick-fil-a sauce"))
> # This returns a list object with all the foods bearing the title "chick-fil-a sauce".
>
> print(munchy.filter_meals(food, "catgory", "beef"))
> # This will throw an error saying that "catgory" is not a valid search parameter.
> ```
---
#### Some recipes worth noting:
> [**Frosted Lemonade**](https://gabyface910.github.io/munchy/#recipes:67683)
> 
> [**Mac & Cheese**](https://gabyface910.github.io/munchy/#recipes:67671)
> 
> [**Fried Chicken**](https://gabyface910.github.io/munchy/#recipe:52813)
> 
> [**Passion Fruit Mousse**](https://gabyface910.github.io/munchy/#recipe:53333)
---
## 🧑‍🍳 Munchy Sous Chef
Sous Chef is the latest extension for Munchy. Simply input a Groq API key (get one for FREE [here](https://console.groq.com)) and some ingredients you have, and Sous Chef will generate a recipe to meet your needs.
> [!WARNING]
> As Sous Chef is AI, it can make mistakes. Double-check recipes before making them.
