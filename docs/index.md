# Spatiotemporal Wildlife Classification Organization

Welcome to the Spatiotemporal Wildlife Classification (SWC) Organization. 
This organization was created to serve as a central hub for all tools and processes created in the fulfillment of 
the thesis study on: _A Novel use of Spatiotemporal Metadata to Bolster Wildlife Classification_.

This organization serves to provide open source documentation and insights into the processes used, to further the 
domain of wildlife classification. 

Each of the topics within the organization structure, provides a sneak-peak into the repository documentation, as well 
as a direct link to the relevant documentation.

## Thesis Report
This link provides direct access to download the resulting report on the investigation into [_A novel use of Spatiotemporal Metadata to Bolster Wildlife Classification_](resources/spatiotemporal_wildlife_classification_draft_1_v_2.pdf)

## Organization Structure

### [Spatiotemporal Wildlife Classification](https://trav-d13.github.io/spatiotemporal_wildlife_classification/)
The global extent of social media, camera traps, and citizen science has the potential to provide 
a real-time global wildlife overview reaching to the furthest corners of the globe.

Automated wildlife classification is essential within ecological studies, wildlife conservation and management, 
specifically fulfilling the roles of species population estimates, individual identification, and behavioural patterns.
However, due to the harsh environments, variable image quality, and long-tail data distribution, traditional 
wildlife classification methods struggle to achieve top performance. 

Existing studies have successfully used metadata to boost the performance of image classification. 
Additionally, the taxonomic structure of metadata falls into the cascading classifier domain. 
The findings of previous studies, lead to the investigation of how taxonomic levels influence the performance 
of metadata and image classification models. Further, how can the determined trends be leveraged within a novel 
cascading ensemble classifier utilizing both metadata and image classification components to improve upon traditional 
methods.

The proposed research questions include:

1. How does taxonomic level influence the performance of metadata classification?
2. How does taxonomic level influence the performance of image classification?
3. How does the novel cascading ensemble method improve upon baseline classifiers?


### [Distributed Scraping Network](https://spatiotemporal-wildlife-classification.github.io/Distributed-Scraping-Network/)
This API is created to run on a server, providing a central means of distributing and collecting weather data from
Open-Meteo. 
This server provides a means of accessing and running a DSN leaf node at any computer. 
This allows collection to occur externally running from a form of cloud computing. 
This allows you to keep your computer free to work on other topics while data collection occurs.

This API is run in combination with results obtained from [Spatiotemporal Wildlife Classification](https://trav-d13.github.io/spatiotemporal_wildlife_classification/) and [DSN Leaf](https://spatiotemporal-wildlife-classification.github.io/DSN-Leaf/).


### [DSN Leaf](https://spatiotemporal-wildlife-classification.github.io/DSN-Leaf/)
This repository serves to provide a leaf node within the [Distributed Scraping Network (DSN)](https://spatiotemporal-wildlife-classification.github.io/Distributed-Scraping-Network/). 
The DSN provides a central point of communication for the leaf node through the use of a [FastAPI](https://fastapi.tiangolo.com/).
The leaf node communicates with the central DSN to determine essential wildlife observation details, 
required to make a weather data request to the Open-Meteo historical API. Once the data is retrieved, the leaf node formats the collected data, and posts it back to the central DSN for collection and storage. 

In summary, the leaf node collects the weather/ metadata for each observation and transfers it to a central storage. 
This enables the creation of the [Spatiotemporal Wildlife Classification's]((https://trav-d13.github.io/spatiotemporal_wildlife_classification/)) novel dataset, specifically the metadata values.

### Animal Detector

### Binary Image Labelling

## Favourites Gallery 

