# Python 3

* [Beginner](#beginner)
* [Medium](#medium)

## Beginner

### Variables, Data Types, Conditionals, Loops, Functions
  * [A Complete Beginner's Guide to Programming](https://dev.to/aspittel/a-complete-beginner-s-guide-to-programming-2ni4)
  * [Python if else, for loop, and range() Exercise with Solutions
](https://pynative.com/python-if-else-and-for-loop-exercise-with-solutions/)

## Medium

### `map`
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
