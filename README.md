**_This is a fork, all credit goes to: Author & copyright (c) 2012: [John Polacek](http://johnpolacek.com)_**

#

This fork modifies tfoot elements in a table to be output as their own (singular) table.

```
<table class="{cssOnTable} stacktable small-only tfoot">
    <tbody>
        <tr>
            <td>{data}</td>
            <td>{data}</td>
        </tr>
    </tbody>
</table>
```

The number of row and cells match that of the original tfoot.

# 

# stacktable.js

The Responsive Tables jQuery plugin for stacking tables on small screens. The purpose of stacktable.js is to give you an easy way of converting wide tables to a format that will work better on small screens. It creates a copy of the table that is converted into a 2-column key/value format. For more info, go to [the project page](http://johnpolacek.github.com/stacktable.js).

[Follow me on Twitter](http://twitter.com/johnpolacek)

## Options
**myClass:** Space separated classes to add to the table.

**headIndex:** Use this to specify the row index of the header, in case it isn’t the first.


# Legal

Author & copyright (c) 2012: [John Polacek](http://johnpolacek.com)

MIT License
