# Python Operators

Calculate and display (print, not return) the rounded cost of a meal with tip and tax.

# Code

#### Given

```
def solve(meal_cost, tip_percent, tax_percent):
```

#### Set up

```
...
round(meal_cost + () + ())
```

#### Second Layer

```
...
round(meal_cost + (meal_cost*tip_percent) + (meal_cost*tax_percent))
```

#### Change Whole Numbers Into Percent

```
...
round(meal_cost + (meal_cost*(tip_percent/100)) + (meal_cost*(tax_percent/100)))
```

#### Final Code

```
def solve(meal_cost, tip_percent, tax_percent):
  """Calculate and display the rounded cost of a meal with tip and tax."""
  cost = round(meal_cost + (meal_cost*(tip_percent/100)) + (meal_cost*(tax_percent/100)))
  print(cost)
```

# Conclusion

Mostly I had to realize exactly what was being asked. I am used to returning on functions that I might have forgotten sometimes a return is not neccessary when all you want is it displayed.

# acknowledgments

* [HackerRank](https://www.hackerrank.com)
