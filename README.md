# Python proyects
Portfolio where knowledge of data analysis, Artificial Intelligence, Machine Learning and Deep Learning is applied.

These will be my forays into learning Python for data science. I'll track my projects here with a quick note on what each project does.

## Downscaling GRACE
Groundwater has a very close relationship with human society thanks to the fact that it stores good quality water in large quantities, is widely distributed, has stability and ease of use, which is why it has become an ideal source of supply and is being highly used by people (Chen et al., 2019) and mostly by industries continuously and persistently without any control. The overexploitation of underground water stores has caused the level to continue to drop, causing disasters such as subsidence of the ground, loss of volume through the separation of an aquifer and the drying of wetlands. The basins are monitored in the field through probes, this study, in addition to being expensive, requires a uniform distribution sufficiently far between each measurement station to capture details of the changes in the level of the aquifers. With the emergence of some new earth observation technologies, a new remote sensing method has been provided for the study of water storage variations at the spatial level, this is the GRACE satellite, which through differences gravitational can estimate the amount of water present in a geographical point. Many researchers have shown that the GRACE satellite can well monitor large-scale area changes with minimal error (Chen et al., 2019).

Because of the proportion of satellite data at a low resolution is necessary to perform a data processing called Downscaling that converts large-scale and low-resolution data into small-scale data at a high resolution. In this case, we used Random Forest Regressor using hidrological explicative variables for all continental Chilean territory.

<p align="center">
<img src="/images/Before_Downscalling_v0-09-02.jpeg" height="400"> <img src="/images/Downscalling_v0-09-02.jpeg" height="400">
</p>

## Neural Networks

Folder containing python notebooks where various Machine Learning and Deep Learning Neural Networks are implemented for multiple tasks such as basic natural language processing, classification, generative networks and machine translation using Transformers.

## EFD MS-823 Proyect
Project in which around $90$ Arduino sensors and a considerable amount of SUM sensors were available to carry out measurements in a total of $396$ homes. To meet this objective, the first thing was to collect the information, a process that lasted approximately $3$ weeks, during that time, an external company installed the sensors as mentioned above, they carried out readings for $48$ hours and upon returning from home they They disinfected and the information was extracted in `.csv` format in a folder with the home code, where if the file begins with a letter `P` it means that it is Pellet heating and an `L` if it corresponded to a house to Firewood, said letter followed by a unique identification code. Finally, the information of the sensor was eliminated to do a general check and that they can continue making measurements in a different house.

During this information extraction process, a Python code begins to be generated and implemented to pre-process the raw data in an unwieldy way. Finally, it is possible to reduce the data from approximately $2$ GB of information to $60$ MB.

## Reinforcement Learning

Project in which certain notions of Reinforcement Learning were applied to certain problems of daily life, among them the random walk and the prediction of Amazon stock prices.

## Web scraping and NLP

Project in which the notions of web scraping are applied to extract information in HTML format for further study, preprocessing and comparison through Natural Language Processing through multiple Machine Learning and Deep Learning tools.