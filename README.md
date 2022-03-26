<hr>

#### You can view the visualization at [vigneshimself.github.io/d3-tree-map](https://vigneshimself.github.io/d3-tree-map/)

<hr/>

# d3-tree-map

![Screen Shot](https://user-images.githubusercontent.com/40684259/159454035-02e1549d-f2e1-4ca8-b6f9-72d66d6c5646.png)

A basic treemap in d3.js from a JSON format input file. 

I took a data that was hierarchical in nature: a root folder in storage(the whole rectangle) where we have the <b>Application Folder</b>(blue region) and <b>Documents Folder</b>(orange region), the subfolders inside, and the size of each folder. Then transformed this data using the D3 hierarchy that basically was able to connect this as a tree.

Each subfolder is represented by a rectangle, whose size is proportional to size of the subfolder in megabytes.

