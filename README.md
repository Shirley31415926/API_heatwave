# API_heatwave

This study analyzes public responses to heatwaves from June to September in 2023 and 2024 using Bluesky posts. We evaluate public attention and sentiment through post frequency and sentiment analysis, and trace how discussion topics evolved over time using topic modeling.

Reading Structure:
Please follow **_API Execution and Visualization Tookit.pdf_** as an instruction and have a look at these files if you want to find the relative code  .
01是2023和2024年heatwave post frequency 获取
02是2023和2024年EU，UK，USA 三个地区气温获取的资料（因为是在R language环境下搭载，所以会标红。）

03是将EU，UK，USA三个地区的气温数据和heatwave post frequency 进行correlation时间相关性分析

04是北半球范围内的2018-2024年的数据获取和分析，以及温度和湿度异常值数据的获取资料

05是sentimental analysis 

06为sentimental analysis 的correlation ，还需要更改统计方法和进行进一步的绘制ing 

07A topic modelling with BERTopic

07B topic modelling with STM





In this project, Xiaolin was responsible for the development of the Bluesky platform API, the extraction of heatwave-related posts, as well as conducting topic modelling and sentiment analysis.
Lixuan was responsible for the collection and organization of temperature data for the UK, USA, Europe, and the Northern Hemisphere, the creation of statistical plots for correlation analysis, and the writing of the Methods section.
Although specific tasks were divided, the overall coding and data analysis were carried out and investigatied collaboratively by both team members.
