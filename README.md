# d3-tree-map

A basic treemap in d3.js from a JSON format input file. You can view it at (https://vigneshimself.github.io/d3-tree-map/)

I took a data that was hierarchical in nature, a root folder in storage where we have the <b>Application</b>(Blue) and <b>Downloads</b>(Orange) folders, the subfolders inside, and the size of each folder. Then transformed this data using the D3 hierarchy that basically was able to connect this as a tree.

![Screen Shot](https://user-images.githubusercontent.com/40684259/159454035-02e1549d-f2e1-4ca8-b6f9-72d66d6c5646.png)

Each subfolder is represented by a rectangle, whose area is proportional to its value(in this case the size of the folder in megabytes)
