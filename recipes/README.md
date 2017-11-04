* how to format ingredient substitutes
* adding comments, ratings, tags, having source vs no source, optional steps
* loosely opinionated
* favorites
* go to meals, quick meals, fancy dinner party meal
* add time to completion
* ingredient search, advanced search
* short expressive recipes


```
line.find(',').first() = instructions
line.find('**').first().to.last() = ingredient
line.find(number).to(' ') = quantity
line.rest() = measurementType
```
