* how to format ingredient substitutes
* adding comments, ratings, tags, having source vs no source, optional steps
* loosely opinionated

```
line.find(',').first() = instructions
line.find('**').first().to.last() = ingredient
line.find(number).to(' ') = quantity
line.rest() = measurementType
```
