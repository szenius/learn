# Python 3

## `map`
* [Lambda, map and filter in Python](https://medium.com/better-programming/lambda-map-and-filter-in-python-4935f248593)

In Javascript, the `Array.map()` function would look something like that:

```javascript
const animals = [
  { animal: "dog", type: "mammal" },
  { animal: "cat", type: "mammal" },
  { animal: "clown fish", type: "fish" },
];

const animalNames = animals.map((animal) => animal.animal);
console.log(animalNames); // [ 'dog', 'cat', 'clown fish' ]
```

For Python, the parameters accepted by the map function are swapped. Other than that, it is rather similar:

```python
animals = [
  { "animal": "cat", "type": "mammal" },
  { "animal": "dog", "type": "mammal" },
  { "animal": "clown fish", "type": "fish" },
]

# map() using external function
def get_animal_name(animal):
  return animal['animal'];

animal_names = list(map(get_animal_name, animals))
print(animal_names) # ['cat', 'dog', 'clown fish']

# map() using lambda function
animal_names = list(map(lambda animal : animal['animal'], animals))
print(animal_names) # ['cat', 'dog', 'clown fish']
```
