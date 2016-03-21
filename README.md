# eRivers

### About this package:
Rivers, lakes and wetlands are generally known to be net sources of greenhouse gases to the atmosphere as they regularly emit CO2 and CH4, but much work remains quantifying spatial variability and sources, especially for large river systems highly impacted by human activities and infrastructure. The motivation behind this collaborative effort is to build an online, open-source tool for synthesizing remotely sensed watershed-related geospatial data with in situ field observations of water chemistry. 

We have developed a series of tools that will help automate and add a reproducable step in the cleaning of this data. We have also added several tools to assist in the visualization and statistical interpretation of this data.  Finally, we have developed a series of tools that utilize Google's [Earth Engine](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwi1vv6Cy9LLAhUP52MKHYbTAwEQFggcMAA&url=https%3A%2F%2Fearthengine.google.com%2F&usg=AFQjCNFuosOleVlLrynwcQHQ7muPQkcpPQ&sig2=-v39e9xN9qrHp5IYOQD9Uw&bvm=bv.117218890,d.cGc) to plot our data and combine it with a range of geospatial and remote sensing data.

#### [Poster](/presentations/eRivers_Poster.pdf)

### Dependencies and how to install
#### Required Packages:
* matplotlib
* pandas
* Bokeh
* scikit-learn
* numpy
* statsmodels

Here are two ways to install packages:

#### 1. If you are already an Anaconda user, you can simply run the command:

conda install bokeh

This will install the most recent published Bokeh release from the Continuum Analytics Anaconda repository, along with all dependencies.

#### 2. Alternatively, it is possible to install from PyPI using pip:

pip install bokeh

#### Running Example Notebooks

To run our demo notebooks or our packages, clone this github repo to your local machine and navigate to the Analysis folder.  From here, you can import our functions and run demo Notebooks locally


### Links to Demo Notebooks
 * [Data Cleaning Example](/Analysis/eRiversExample.ipynb/)
 * [Mapping Example](/Analysis/maps/ee_mapping.ipynb/)

### License:
This project utilizes the MIT license.

