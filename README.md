# Load and compare DeepLearning vs Manually classified point cloud data
=======

An application that compares Deep Learning classified point cloud I3S service vs unclassed layers.

To compare different layers, the app expects a webscene with bookmarks named using the following convention:
[anyName]*_scene.1*  (eg. `view.1_scene.1`) - the name of the bookmark.
[anyName]*_scene.2* - (eg. `view.1_scene.2`) - the name of the corresponding bookmark to compare to.
....

## [Live Version](https://tamrat-b.github.io/deeplearning)

## Supported URL parameters

* [webscene=id](https://tamrat-b.github.io/deeplearning?webscene=fc6a02851fb44c0f92dc03566754898e): Load the given webscene from the portal (default www.arcgis.com)
* portal=url: Use the given portal URL
* [animate=true](https://tamrat-b.github.io/i3scompare?animate=true): Run through all slides in both versions once
* [stats=true](https://tamrat-b.github.io/i3scompare/?stats=true): Display some scene statistics
