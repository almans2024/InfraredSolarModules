# InfraredSolarModules
InfraredSolarModules is a machine learning dataset that contains real-world imagery of different anomalies found in solar farms. This dataset can be used for machine learning research to gain efficiencies in the solar industry. Infrared imagery is not widely available to researchers. In order to combat the lack of publicly available data on infrared imagery of anomalies in solar PV, this project presents a novel, labeled dataset to facilitate research to solve problems well suited for machine learning that can have environmental impact.
# data
The dataset consists of 20,000 infrared images that are 24 by 40 pixels each. There are 12 defined classes of solar modules presented in this paper with 11 classes of different anomalies and the remaining class being No-Anomaly (i.e. the null case).




The file 2020-02-14_InfraredSolarModules.zip contains the images directory and module_metadata.json that describes each image. The JSON file is structured as follows:

{
  "<image_number>": {
    "image_filepath": "images/<image_number>.jpg", 
    "anomaly_class": "<class_name>"
  },
  ...
}

# References
This dataset was originally published at ICLR 2020 in AI for Earth Sciences workshop.

https://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth22.pdf
