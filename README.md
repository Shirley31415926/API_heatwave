# API_heatwave

This study analyzes public responses to heatwaves from June to September in 2023 and 2024 using Bluesky posts. We evaluate public attention and sentiment through post frequency and sentiment analysis, and trace how discussion topics evolved over time using topic modeling.


**_Reading Structure_**

Please follow **_API Execution and Visualization Tookit.pdf_** as an instruction and have a look at these files if you want to find the relative code.

The study is structured as follows. File 01 presents the collection of heatwave-related post frequencies from social media platforms for the years 2023 and 2024. File 02 details the acquisition of temperature data for the EU, UK, and USA regions, conducted in the R programming environment. File 03 investigates the temporal correlations between regional temperature variations and heatwave post frequencies. File 04 extends the analysis to a hemispheric scale by compiling temperature and humidity anomaly data from 2018 to 2024. File 05 focuses on sentiment analysis of heatwave-related posts, while File 06 offers a statistical evaluation of the sentiment data. Files 07A and 07B apply topic modelling techniques—BERTopic and Structural Topic Modeling (STM), respectively—to explore thematic structures within the discourse. Finally, File08 employed a Generalized Additive Model (GAM) and further extended the analysis using a Bayesian GAM framework.

Together, these components provide a comprehensive assessment of the relationship between climatic stress and digital public response across regions and time.




**_Author Contributions_**

The overall coding and data analysis were collaboratively conducted and jointly discussed by both authors. Xiaolin was responsible for developing the Bluesky platform API, extracting heatwave-related posts, performing correlation analysis between post counts and temperature—including assessments of lag effects and predictive relationships—and implementing sentiment analysis and topic modeling. Lixuan was responsible for acquiring and analyzing temperature data for the UK, USA, and Europe, as well as ERA5-based temperature data for the Northern Hemisphere. She also conducted time series visualization and statistical analysis （especially GAM and Bayesian）, and prepared the documentation for the "API Execution and Visualization Toolkit".
