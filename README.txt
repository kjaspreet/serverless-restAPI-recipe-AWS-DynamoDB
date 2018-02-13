GitHub Link:


Recipe API: Using this restAPI, user can create/insert new recipe in the database (DynamoDB), update the existing recipe, delete the existing recipe, list all the entries/recipes, get single recipe by using id.

Instruction: 
- Run npm install

URL for Creating a Recipe:
https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe

Example:
curl -X POST https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe --data '{ "text": "testing","name": "Extra" }'

URL for Reading All Recipes:
https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe

Example:
curl https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe

URL for Reading a Recipe:
https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe/{id}

Example:
curl https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe/3562c3f0-10aa-11e8-aa01-752dca21e3c1

URL for Deleting a Recipe:
https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe/{id}

Example:
curl -X DELETE https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe/3562c3f0-10aa-11e8-aa01-752dca21e3c1

URL for Updating a Recipe:
https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe/{id}

Example:
curl -X PUT https://4ompkw5upa.execute-api.us-west-2.amazonaws.com/dev/recipe/3562c3f0-10aa-11e8-aa01-752dca21e3c1 --data '{ "text": "testing update"}'


