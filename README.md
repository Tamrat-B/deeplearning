# Load and compare DeepLearning classified point cloud data
=======

An application that compares Deep Learning classified point cloud I3S service vs unclassed layers.

To compare different layers, the app expects a webscene with bookmarks named using the following convention:
[anyName]*_I3SNative*  (eg. `view.1._I3SNative`) - the name of a bookmark showcasing the native i3s layer.
[anyName]*_3DTiles2I3S* - (eg. `view.1.3DTiles2I3S`) - the name of the corresponding bookmark showcasing the imported 3d tiles layer.

## [Live Version](https://tamrat-b.github.io/deeplearning)

## Supported URL parameters

* [webscene=id](https://3dcities.maps.arcgis.com/home/item.html?id=5f50ba90605142c09523e37fabe141e5): Load the given webscene from the portal (default www.arcgis.com)
* portal=url: Use the given portal URL
* [animate=true](https://tamrat-b.github.io/i3scompare?animate=true): Run through all slides in both versions once
* [stats=true](https://tamrat-b.github.io/i3scompare/?stats=true): Display some scene statistics
