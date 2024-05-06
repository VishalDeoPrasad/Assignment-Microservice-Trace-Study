# Microservice Tracing Data Exploratory Data Analysis (EDA)

## Introduction
In this project, we perform Exploratory Data Analysis (EDA) on microservice tracing data. Microservices are small, independent processes that collectively form a larger application. Tracing data refers to the information collected during the execution of these microservices, including timing, duration, and errors encountered during service calls.

## Objectives
The objectives of this EDA are as follows:
- Gain insights into the performance of microservices.
- Identify patterns and anomalies in the tracing data.
- Understand the overall behavior of the system.

## Steps
1. **Data Cleaning:** Preprocess the tracing data to handle missing values, outliers, and inconsistencies.
2. **Descriptive Statistics:** Calculate summary statistics to understand the central tendency and variability of the data.
3. **Visualization:** Create visual representations such as histograms, box plots, and scatter plots to identify trends and patterns.
4. **Correlation Analysis:** Examine the relationships between variables to understand their interdependencies.
5. **Time Series Analysis:** Analyze temporal aspects of the data to understand performance changes over time.
6. **Anomaly Detection:** Identify unusual behavior indicating potential issues or inefficiencies in the system.

## Tools
- Python: Pandas, NumPy, Matplotlib, Seaborn for data manipulation, analysis, and visualization.
- Jupyter Notebook: For interactive data exploration and documentation.

## Termonology 
- **Microservice**: Microservices are an architectural and organizational approach to
software development where software is composed of small independent services that
communicate over well-defined APIs. These services are owned by small, self-contained
teams. More information 1, 2, 3.
- **Observability**: Microservice observability is the ability to collect and present the data to
gain visibility of various services. This is achieved by 3 pillars of observability logs,
metrics and traces. More information 1, 2, 3.
- **Traces**: Traces track the end-to-end behavior of a request as it moves through a
distributed or microservice system. The data collected in distributed tracing brings higher
visibility to requests that use multiple internal microservices. Traces provide insight into
how a request behaves at specific points in an application. More information 1, 2, 3.

## About Dataset:
- **Timestamp**: Time of occurrence of the event
- **traceID**: Unique ID of an execution path through the system
- **spanID**: Unique ID associated with execution of a logical unit
- **parentSpanID**: spanID of parent span that called a given span
- **serviceName**: Name of microservice associated with the span
- **Name**: Method/function/endpoint name associated with the span
- **durationNano**: Time taken in nanoseconds to execute the span