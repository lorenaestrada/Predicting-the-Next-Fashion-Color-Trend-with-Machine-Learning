**Predicting the Next Fashion Color Trend with Machine Learning 
---------------------------------------------------------------------------------------------
Overview 
------------------------------------------------------------------------------------------------
This project aims to predict the next fashion color trend using machine learning techniques, K-Means, and Hierarchical Clustering. It will gather data from the URLs of Vogue Runway Fall 2024 Ready-To-Wear collections of different designers to obtain the images' colors for further analysis. The project will end with the results of the applied techniques.

 METHODOLOGY 
------------------------------------------------------------------------------------------------
>>1. Data Collection: Data is gathered from Vogue Runway Ready-to-Wear Fall 2024 collections. The URLs gathered are from distinct fashion companies to scrape the image's colors. Data included will be the company name, URLs, Dominant Color, Color Classification 

>>2. Image Scraping: We use Requests and BeautifulSoup to web scrape the images' colors from the URLs collected.

>>3. Dominant Colors: Using the PIL, each image color was extracted and shown as RGB values. Each color is classified into Light, Dark, Brown/Beige, and others. 

>>4. Data Exploration: The filtered data is subjected to a thorough analysis, with different graphs and plots used to provide a comprehensive understanding of the data.

>>5. Feature Selection: The RBG values are carefully extracted from the dominant color and normalized, ensuring the validity and reliability of the analysis.

>>6. K-Means Clustering: K-means was applied to the normalized data. The Ward method was applied to determine the cluster amount, and the cluster was shown in graphs. 

>>7. Hierarchical Clustering: In addition to normalized data, hierarchical clustering was applied. The Dendogram was used to determine clusters, which were then shown in graphs. 
-------------------------------------------------------------------------------------------

