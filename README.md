# Insect detector demo

Quick online showcase of an insect finder based upon the [YOLOv8 architecture](https://github.com/ultralytics/ultralytics). This demo allows you to upload a demo image for annotation (see sample image).

It demonstrates the high accuracy of finding insects in/on institutional collection drawers, allowing for quick inventory creation (counts) of collections.

This demo only considers the presence or absence of any insect, not the type of insect in the image. Improvements of the model in this direction can be made, but requires more annotation data (labels). Curently only 16 drawers were used across different orders to train a simple (nano scale) YOLOv8 model (in order to support it to run in a browser). A larger model attained higher accuracies but is not compatible with an online demo.

You can test the model on an example image of a whole-drawer insect collection as described in Mantle et al. 2012. Save the file locally and upload it for classification. 

![](sample.jpeg)

## Acknowledgements

All credit for the react based webpage goes to [Wahyu Setianto](https://github.com/Hyuto), with the exception of minor
changes to automated deployment (github runner) and the fine tuned YOLOv8n insect classification model which are mine.

## Reference

Mantle et al. (2012). "Whole-drawer imaging for digital management and curation of a large entomological collection". ZooKeys 209: 147. DOI:10.3897/zookeys.209.3169.
