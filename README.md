# [pluralater.js](http://rack.pub/pluralater/)
### Synopsis

Pluralater takes data in the form of quantity, item name and returns the plural form of item name if quantity is 2 or more.  Pluralater.js returns 2 public methods - read and format, and one public property, help. 

### Code Example
```
pluralater.read([[2,'orange'],[3,'peach'],[5,'cherry']]) --> '2 oranges, 3 peaches, and 5 cherries.'.
pluralater.format([3,'couch']) --> '[3, 'couches']'
pluralater.help --> "Pluralater.js returns 2 public methods - read and format.  Pluralater.read expects an array of arrays, each with quantity and item name, e.g. pluralater.read([[2,'orange'],[3,'peach'],[5,'cherry']]) returns string '2 oranges, 3 peaches, and 5 cherries.'.  Pluralater.format expects an array with quantity and item name, e.g., pluralater.format([3,'couch']) returns array '[3, 'couches']'"
```
> :apple: read returns a string with an Oxford comma in arrays of 3 or more items.

### Motivation

I needed to automate a summary of input items.  Items with qty 2 and up need to be expressed as plural.

### Installation

Copy and paste the javascript.

### API Reference

```
pluralater.read([[2,'orange'],[3,'peach'],[5,'cherry']]) --> '2 oranges, 3 peaches, and 5 cherries.'.
pluralater.format([3,'couch']) --> '[3, 'couches']'
pluralater.help --> "Pluralater.js returns 2 public methods - read and format.  Pluralater.read expects an array of arrays, each with quantity and item name, e.g. pluralater.read([[2,'orange'],[3,'peach'],[5,'cherry']]) returns string '2 oranges, 3 peaches, and 5 cherries.'.  Pluralater.format expects an array with quantity and item name, e.g., pluralater.format([3,'couch']) returns array '[3, 'couches']'"
```

### Contribute

If you found a bug, have any questions or want to contribute please let me know, [ron@rack.pub](mailto:ron@rack.pub).

### License

Ron Royston, [www.rack.pub](www.rack.pub), [MIT License](https://en.wikipedia.org/wiki/MIT_License)