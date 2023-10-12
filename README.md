
# Recipe-Recommendation🥗🥗

The Recipe-Recommendation project is a web application that allows users to search for recipes based on ingredients and countries. It provides users with details of recipes, including videos, instructions, and the list of ingredients used. This README will guide you through the setup, features, and usage of the project.


## Features

- Recipe Search by Ingredients: Users can search for recipes by entering a list of ingredients. The application will provide a list of recipes that can be prepared with those ingredients.

- Recipe Search by Countries: Users can explore recipes from specific countries. They can select a country from a list and view recipes associated with that country's cuisine.

- Recipe Details: For each recipe, the application provides detailed information:

- Video: Users can watch a video of the recipe being prepared.
- Ingredients: The list of ingredients required for the recipe.
- Instructions: Step-by-step cooking instructions to prepare the dish.


## Run Locally

Clone the project

```bash
  git clone https://github.com/Sudeep-Poojary/Recipe-Recommendation.git
```


## Tech Stack

Html, CSS, Javascript


## API Reference

#### Get recipe by ingredients

```http
  GET https://www.themealdb.com/api/json/v1/1/filter.php?i=Onion
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get recipe by Country

```http
  GET https://www.themealdb.com/api/json/v1/1/filter.php?a=Indian
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |



