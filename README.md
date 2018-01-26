# neuro-python-plotting
Various scripts I use to plot using python:

* barplotwithsamples.ipynb is a Jupyter Notebook script to plot bars with 90% Confidence Interval error bars and also the subjects points and (optionally) the subjects labels. It just expects as input a txt file with one value per line (one value = one subject). It works particularly well with CONN REX output (results.ROIs.rex.data.txt). It can also plot multiple ROIs, and it can visualize the ROI maps on a glass brain and synchronize with the bar display (same color as glass brain + ROIs centers' coordinates will be displayed in the bar plot + atlas regions names covered by ROIs will be extracted from AAL2 atlas).

  ![barplotwithsamples example image](https://raw.githubusercontent.com/lrq3000/neuro-python-plotting/master/img/barplotwithsamples.png)

  ![rois_glass_brain example image](https://raw.githubusercontent.com/lrq3000/neuro-python-plotting/master/img/rois_glass_brain.png)

  ![rois_bars example image](https://raw.githubusercontent.com/lrq3000/neuro-python-plotting/master/img/rois_bars.png)