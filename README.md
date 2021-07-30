# COVID-19-tacker-and-social-awareness

# ABSTRACT

While the COVID-19 outbreak was reported to first originate from Wuhan, China, it has been declared as a Public Health Emergency of International Concern (PHEIC) on 30 January 2020 by WHO, and it has spread to over 190 countries. As the disease spreads around the globe, it has evolved into a world-wide pandemic, endangering the state of global public health and becoming a serious threat to the global community. To combat and prevent the spread of the disease, all individuals should be well-informed of the rapidly changing state of COVID-19. In the endeavour of accomplishing this objective, a COVID-19 live tracker has been built to provide the latest status of the disease and relevant analytical insights. The live tracker is designed to cater to the general audience without advanced statistical aptitude. It aims to communicate insights through various straightforward and concise data visualizations that are supported by reliable data sources. This tracker provides COVID-19 related data of over 200 countries along with providing social awareness about some common symptoms and information about other common diseases.   


Keywords -  COVID-19, live tracker, pandemic, data visualisation, common symptoms, WHO, PHEIC.


# TECH USED


We have used the following tech our COVID-19 tracker.

	Frontend
HTML, CSS and Bootstrap.

	Backend
JavaScript, JQuery.

	Meaningful Dashboards

	Quality Code


# METHODOLOGY

Real Time Data Retrieval

To achieve real-time data retrieval, the webserver contains a protocol to download and ingest the data source from the CSSE data repository by Johns Hopkins University when a request is sent to the server when a user tries to access the web page in a browser. When the server receives such requests, it will attempt to download the data by getting the current date and accessing the data source with an updated URL. Once the data file is downloaded successfully, it will be ingested and stored temporarily on the server. Subsequently, the pre-specified R script will read the data and pre-process it into different data frames to support the insights to be derived on the web page. If the download were to be unsuccessful due to unforeseen circumstances, the web server will load up the most recent data file that it has ingested previously to support the content on the web page. The server will also log such errors so that they could be handled to improve the robustness of the tracker. Figure ¬¬5.1 provides a visual summary of the real-time data retrieval process.







