<hr>

#### Live site : [vigneshimself.github.io/d3-tree-map](https://vigneshimself.github.io/d3-tree-map/)

<hr/>

# d3-tree-map

![Screen Shot](https://user-images.githubusercontent.com/40684259/160278827-7b9e4640-b75b-4b16-b7c8-4733c217b4d6.png)

A basic treemap in d3.js from a JSON format input file. 

I took a data that was hierarchical in nature:

![Screen Shot](https://user-images.githubusercontent.com/40684259/160256850-34e7d160-fcf0-4f04-8c8f-68f83e0259db.png)

A root directory in storage(the whole rectangle) where we have the <b>Application Folder</b>(blue region) and <b>Documents Folder</b>(orange region), the subfolders inside, and the size of each folder. Then transformed this data using the D3 hierarchy that basically was able to connect this as a tree.

Each subfolder is represented by a nested rectangle, whose area is proportional to size of the subfolder in megabytes.

