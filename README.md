# pluralizer.js
### Synopsis

Pluralizer (7.19 KB) returns the plural form of whatever word you give it.  
```
pluralizer.run('goose') --> 'geese'
```
It can also take an array of string arrays, each having a quantity and corresponding word, and return well formed english with an Oxford comma. 
```
pluralizer.read([[2,'orange'],[3,'peach'],[5,'cherry']]) --> '2 oranges, 3 peaches, and 5 cherries.'.
```
Pluralizer.js returns 2 public methods - read and run, and one public property, help.
> :apple: pluralizer.read returns a string with an Oxford comma in arrays of 3 or more items.

### Installation

:rocket:  Embed pluralizer.min.js in your javascript when putting in production for best page loading performance.

### Contribute

If you found a bug, have any questions or want to contribute please let me know, [ron@rack.pub](mailto:ron@rack.pub).

### License

Ron Royston, [https://rack.pub](https://rack.pub), [MIT License](https://en.wikipedia.org/wiki/MIT_License)