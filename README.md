# Sortable table jQuery plugin

###About

jQuery plugin which makes tables sortable by priority. 

It modifies table in the way that table head cells become clickable, after a click on which, appropriate column sorts, after second click on the same head cell - column gets initial order. Sorting order corresponds to order of clicks.

#####Example
Initial table state

![Table sort 1](http://i.piccy.info/i9/c4fcf4cd94c1cb81201970c7d45b9be1/1432301778/46608/668760/Screen_Shot_2015_05_22_at_14_54_46_500.jpg)

After click on first head cell, table sorts by values in the first column

![Table sort 2](http://i.piccy.info/i9/c4fcf4cd94c1cb81201970c7d45b9be1/1432301778/46608/668760/Screen_Shot_2015_05_22_at_14_55_18_500.jpg)

After click on second head cell, table is sorted based on 2 columns - firstly by 'Name', secondly by 'Age' 

![Table sort 3](http://i.piccy.info/i9/c4fcf4cd94c1cb81201970c7d45b9be1/1432301778/46608/668760/Screen_Shot_2015_05_22_at_14_55_33_500.jpg)

![Table sort 4](http://i.piccy.info/i9/c4fcf4cd94c1cb81201970c7d45b9be1/1432301778/46608/668760/Screen_Shot_2015_05_22_at_14_55_33_500.jpg)

---
###Usage

To enable plugin for table,  write in your jQuery code:

```js
  $("#my-table").makeSortable();
```

After this your table will become sortable by priority.