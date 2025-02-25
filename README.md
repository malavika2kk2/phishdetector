# Phishing Site Detector Plugin 
This lite chrome plugin aims to detect phishing websites and warn the user. It is built with a objective of privacy, so that the user browsing data need not collected for classification. The classification is done on the client side with one-time download of classifier model.



**Dataset:** [UCI Repository](https://archive.ics.uci.edu/ml/datasets/phishing+websites)  
**Technique:** Random Forest Classifier

## Requirements
```
Python3.7
sklearn==0.19.2
numpy==1.15.0
liac-arff==2.2.2
```

## Documentation
* [Wiki - Complete reference](https://github.com/picopalette/phishing-detection-plugin/wiki)
* [Prepare the dataset](backend/dataset/)
* [Train and Export the model](backend/classifier/)
* [Install plugin](frontend/)

## Screenshot
<img src="https://raw.githubusercontent.com/picopalette/phishing-detection-plugin/master/artifacts/pluginUI.png" alt="UI" height="400" width="250"></img>

**F1 score:** 0.905

Links to few phishing sites: [PDF](artifacts/url_list.pdf), [PhishTank](https://www.phishtank.com/)

### References
[Intelligent phishing website detection using random forest classifier](https://ieeexplore.ieee.org/abstract/document/8252051/)
