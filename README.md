# Week2-prep-datatbase
![Diagram ](https://github.com/AliOthman0934/Week2-prep-datatbase/assets/147824401/c4b35587-dc6e-4ddf-8527-d097f134a172)

1) What type of relationships do you see between the tables?
    Relationships:

    Recipe to Category (Many-to-Many):
    The Recipe table and the Category table are linked through the RecipeCategory table. A recipe can belong to multiple categories, and a category can have multiple recipes.

    Recipe to Ingredient (Many-to-Many):
    The Recipe table and the Ingredient table are linked through the RecipeIngredient table. A recipe can have multiple ingredients, and an ingredient can be used in multiple recipes.

    Recipe to Step (Many-to-Many):
    The Recipe table and the Step table are linked through the RecipeStep table. A recipe can have multiple steps, and a step can be part of multiple recipes.

2) Which tables should be linked with a foreign key?

    CategoryID in the RecipeCategory table, referencing Category(CategoryID).

    RecipeID and CategoryID in the RecipeCategory table, referencing Recipe(RecipeID) and Category
    (CategoryID) respectively.

    IngredientID in the RecipeIngredient table, referencing Ingredient(IngredientID).
    RecipeID and IngredientID in the RecipeIngredient table, referencing Recipe(RecipeID) and Ingredient(IngredientID).

    StepID in the RecipeStep table, referencing Step(StepID).
    RecipeID and StepID in the RecipeStep table, referencing Recipe(RecipeID) and Step(StepID).

3) Where can you add a primary key?

    RecipeID in the Recipe table.

    CategoryID in the Category table
    .
    IngredientID in the Ingredient table.

    StepID in the Step table.
