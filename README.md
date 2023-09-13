### Big Data with example and types

Big Data is defined as large amounts of data. This is a word used to describe a massive collection of data that continues to increase exponentially over time. Big data technology and analytics approaches are applied to extract essential insights and information from this data.
For example:- Social Media Data, Sensor data, Stock market, Text data, Customer Data
There are three different types of Big data:-
  
Structured data:- Any data that can be stored, accessed, and processed in a fixed format is known as structured data.

Unstructured data: Data having an undetermined form or data that might be difficult to process and obtain values for. 

Semi-Structured data:- This structure has both features; however, the data looks to be structured but is not.

### 6 ‘V’s of Big Data (define each)

Volume

The name ‘Big Data’ itself is related to its enormous size. Volume is a vast amount of data. To determine the value of data, the length plays a crucial role. If the volume of data is 
enormous, it is considered ‘Big Data.’ Volume means whether a particular data can be regarded as Big Data or not depends on the volume of data.

Velocity

The term velocity refers to the rapid collection of data. In Big Data velocity, data pours in from many sources, such as machines, networks, social media, mobile phones, etc. A large and 
constant influx of data exists. This influences the data's potential or how quickly it is created and processed to fulfill needs. When dealing with a problem like ' velocity,' sampling data might be helpful too.

Variety

The terms "structured," "semi-structured," and "unstructured" relate to the types of data. It also refers to diverse sources. The emergence of data from fresh sources, both inside and outside
a company, is what variety means.It might be organized, somewhat organized, or unorganized.

Veracity

It relates to data consistency and ambiguity; readily available data can occasionally become disorganized, and quality and accuracy are challenging to manage.Big data is also unpredictable 
because there are so many different data dimensions arising from several dissimilar data kinds and sources.4

Value

There is one more V after considering the four Vs—Value! Most data with no value is useless to the organization until you can make it valuable.Data is worthless and unimportant; information
must be extracted by transforming it into something worthwhile. Therefore, you might say that Value! is the most significant of the six virtues.

Variability

Even in erratic and changing data contexts, you manage and contextualize data in a way that offers structure. In this sense, the design of a survey or, for instance, unsubscribe buttons alters 
how things look to individuals and, consequently, the result. This implies that if you modify a variable, your model will likewise change.

### Phases of Big Data analysis (discuss each)

Business Problem Definition – 
At this step, the team becomes familiar with the business domain, which outlines the rationale and objectives for doing the analysis. The issue is discovered at this step, and predictions are
produced on the possible profit that a business may realize after conducting the study. The group gains knowledge about the business domain during this phase, which outlines the analysis's rationale 
and objectives. The issue is discovered at this step, and predictions are produced on the possible profit that a business may realize after conducting the study. The business case must directly 
connect to one (or more) of the qualities of volume, velocity, or variety in order for it to be considered a big data challenge.

Data Definition – 
The sources of datasets can be external or internal to the firm, depending on the business case and the breadth of analysis of the project under consideration. Regarding internal datasets, the data 
might be gathered from internal sources like feedback forms from already installed software. On the other hand, the list of external datasets also contains data from unaffiliated sources.

Data Acquisition and Filtration – 
Once the data's source has been determined, it is time to collect the data from those sources. The majority of this material needs to be more structured. After that, it goes through filtration, removing 
faulty or irrelevant data that doesn't pertain to the analysis's goal. Here, erroneous data refers to records that may be missing or data that contain incompatible data types. 

Data Extraction – 
Now that the data has been filtered, it is possible that some of the entries are incompatible. To address this problem, a distinct step known as the data extraction phase has been devised. The data that 
don't fit the analysis's fundamental scope are removed and modified at this step.

Data Munging – 
The data is unstructured because it is gathered from diverse sources, as was discussed in Data Acquisition and Filtration. The data may have inappropriate limitations, which may provide erroneous 
findings. A dataset could, for instance, include a few rows containing null entries. If a dataset identical to this one already exists, the entries are copied from it; otherwise, the rows are discarded.

Data Aggregation & Representation –
The data is validated and cleaned following the enterprise's criteria. However, the data could be dispersed among several databases, and working with several datasets is not recommended. Consequently, 
the datasets are combined. For instance, two datasets, the Student Academic part and the Student Personal Details section, can be connected using a standard variable, such as the student's roll number. 
Due to the potential for a considerable volume of data, this phase necessitates intensive operation.

Exploratory Data Analysis – 
The actual stage, which is the analytical work, is now. Analysis is done under the big data issue's nature. There are two types of data analysis: exploratory and confirmatory. In a confirmatory study, 
the phenomenon's cause is first examined. The hypothesis is the presumption. The data is reviewed to see whether the view is correct. This study validates whether an assumption was correct and offers 
conclusive answers to specific problems. An exploratory study looks deeper into the data to determine why phenomena occurred. 

Data Visualization – 
Now that we have the information from the data in the datasets, we can answer some questions. However, these solutions continue to remain inaccessible to corporate users. Some type of representation 
is necessary to get value or a specific result from the analysis. As a result, various tools are utilized to show the data in a graphic format that business users may readily understand. It is claimed
that visualization affects how the results are interpreted. Additionally, it gives users the chance to find solutions to hypothetical queries.

Utilization of analysis results – 
The analysis has been completed, the findings have been visualized, and it is now up to the business users to decide how to use the information. The outcomes can be utilized for process improvement and 
optimization. It may also be included in the systems as an input to improve performance.

### Challenges in Big Data analysis (discuss each)

Heterogeneity and Incompleteness

However, machine analysis algorithms expect homogeneous data and cannot understand nuance. In consequence, data must be carefully structured as a first step in (or before) data analysis. Consider, for
example, a patient who has multiple medical procedures at a hospital. We could create one record per medical procedure or laboratory test, one document for the entire hospital stay, or one for all lifetime
hospital interactions of this patient. Even	after data cleaning and	error correction, some incompleteness and some errors in data are likely to remain. This incompleteness and these errors must be managed 
during data analysis. Doing this correctly is a challenge. Recent work on managing probabilistic data suggests one way to make progress.

Scale

The internet's ongoing evolution is the first and one of the most significant difficulties. It needs new tools and approaches to handle such massive amounts of data, including parallel and cloud computing.
Data scientists nowadays need help managing the growing amounts of data. Additionally, cloud computing is being adapted for use on the internet, aggregating several disparate workloads and shifting
performance objectives into enormous clusters. In this instance, resource sharing necessitates developing novel, affordable methods for handling frequent system failures and data analysis. 

Timeliness​

The size of the data collection to be processed determines how long it will take to analyze the data. There are several circumstances when the analysis's findings must be available immediately. To quickly
conclude, we must prepare partial results in advance so that a small amount of incremental computing with fresh input may be used. However, only a few types of criteria are supported by each index structure.
New sorts of standards are defined by further Big Data analyses, necessitating the creation of new index structures to accommodate them. Designing such systems becomes very difficult when the data volume is 
expanding quickly, and the queries have constrained response times.

Privacy

Public concern over the improper use of personal data is high, especially when data from many sources are linked together. To fully achieve the potential of big data, managing privacy must be approached from 
both a technological and a societal standpoint. There are several other complex research issues. For instance, security for information sharing in Big Data use cases is still unknown, as is the best way to 
share private data while minimizing disclosure and guaranteeing adequate data usefulness in the transmitted data.


## References

1.(n.d.). https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=3dc03532a968eb7459d77346e52c2c58a3ee9bd4

2.(2015, May 27). https://www.ijircst.org/DOC/3_big_data_analytics_challenges_tools.pdf

3.Thiele, J. C. (2022). Design and Implementation of Environmental Information Systems - Three case studies for managing climate and land-use change in Forestry 
and Agriculture. https://doi.org/10.53846/goediss-7277

Harding, B., & Hegland, M. (2013). A robust combination technique. Australian & New Zealand Industrial and Applied Mathematics Journal, 54, 394. https://doi.org/10.21914/anziamj.v54i0.6321

