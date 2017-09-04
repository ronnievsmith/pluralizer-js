# pluralizer.js
### Synopsis

Pluralizer (7.19 KB) returns the plural form of whatever word you give it.  It can also take an array of string arrays, each having a quantity and corresponding word, and return well formed english with an Oxford comma. See code examples below. Pluralizer.js returns 2 public methods - read and run, and one public property, help. 

### Code Example
```
pluralizer.read([[2,'orange'],[3,'peach'],[5,'cherry']]) --> '2 oranges, 3 peaches, and 5 cherries.'.
pluralizer.run('goose') --> 'geese'
pluralizer.help --> "pluralizer.js returns 2 public methods - read and run.  pluralizer.read expects an array of arrays, each with quantity and item name, e.g. pluralizer.read([[2,'orange'],[3,'peach'],[5,'cherry']]) returns string '2 oranges, 3 peaches, and 5 cherries.'.  pluralizer.run expects a string, e.g., pluralizer.run('goose') returns 'geese'."
```
> :apple: read returns a string with an Oxford comma in arrays of 3 or more items.

### Motivation

I needed to automate a summary of input items.  Items with qty 2 and up need to be expressed as plural.

### Installation

:checkered_flag: Load via rack.pub's global CDN

`<script src="https://rack.pub/pluralizer.min.js"></script>`

:rocket:  Embed pluralizer.min.js in your javascript when putting in production for best page loading performance.

### API Reference

```
pluralizer.read([[2,'orange'],[3,'peach'],[5,'cherry']]) --> '2 oranges, 3 peaches, and 5 cherries.'.
pluralizer.run('goose') --> 'geese'
pluralizer.help --> "pluralizer.js returns 2 public methods - read and run.  pluralizer.read expects an array of arrays, each with quantity and item name, e.g. pluralizer.read([[2,'orange'],[3,'peach'],[5,'cherry']]) returns string '2 oranges, 3 peaches, and 5 cherries.'.  pluralizer.run expects a string, e.g., pluralizer.run('goose') returns 'geese'."
```

### Contribute

If you found a bug, have any questions or want to contribute please let me know, [ron@rack.pub](mailto:ron@rack.pub).

### License

Ron Royston, [https://rack.pub](https://rack.pub), [MIT License](https://en.wikipedia.org/wiki/MIT_License)