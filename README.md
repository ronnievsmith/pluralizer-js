# [pluralizer.js](http://rack.pub/pluralizer.min.js)
### Synopsis

Pluralizer (5.48 KB) takes data in the form of quantity, item name and returns the plural form of item name if quantity is 2 or more.  pluralizer.js returns 2 public methods - read and format, and one public property, help. 

### Code Example
```
pluralizer.read([[2,'orange'],[3,'peach'],[5,'cherry']]) --> '2 oranges, 3 peaches, and 5 cherries.'.
pluralizer.format([3,'couch']) --> '[3, 'couches']'
pluralizer.help --> "pluralizer.js returns 2 public methods - read and format.  pluralizer.read expects an array of arrays, each with quantity and item name, e.g. pluralizer.read([[2,'orange'],[3,'peach'],[5,'cherry']]) returns string '2 oranges, 3 peaches, and 5 cherries.'.  pluralizer.format expects an array with quantity and item name, e.g., pluralizer.format([3,'couch']) returns array '[3, 'couches']'"
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
pluralizer.format([3,'couch']) --> '[3, 'couches']'
pluralizer.help --> "pluralizer.js returns 2 public methods - read and format.  pluralizer.read expects an array of arrays, each with quantity and item name, e.g. pluralizer.read([[2,'orange'],[3,'peach'],[5,'cherry']]) returns string '2 oranges, 3 peaches, and 5 cherries.'.  pluralizer.format expects an array with quantity and item name, e.g., pluralizer.format([3,'couch']) returns array '[3, 'couches']'"
```

### Contribute

If you found a bug, have any questions or want to contribute please let me know, [ron@rack.pub](mailto:ron@rack.pub).

### License

Ron Royston, [https://rack.pub](https://rack.pub), [MIT License](https://en.wikipedia.org/wiki/MIT_License)