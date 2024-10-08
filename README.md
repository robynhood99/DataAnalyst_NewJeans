# DataAnalyst_NewJeans

## **PROJECT DESCRIPTION**
The aim of this project was to analyze the streaming performance and popularity trends of NewJeans' music across various platforms like Spotify and YouTube. The objective was to identify which songs gained the most traction, assess listener engagement, and understand the contributing factors behind their growing fanbase.

## **FILE STRUCTURE**
1. **File Dataset**: This file contains the entire dataset for retrieving view, like, and comment data using the YouTube API.
2. **NewJeans.xlsx**: This is an Excel file containing analysis data related to NewJeans from two music platforms, YouTube and Spotify.
3. **NewJeans_YoutubePopularity.xlsx**: This file contains an Excel file with the calculations of YouTube popularity before normalization.
4. **Youtube_Popularity_Score_Normalized_.xlsx**: This file contains an Excel file with the calculations of YouTube popularity after normalization.
5. **NewJeans_Analysis.twb**: This is a Tableau file containing the analysis results related to NewJeans, based on the NewJeans Excel file.
6. **NewJeans (Data Analysis).pdf**: This file contains a complete explanation of the analysis that has been conducted.

## **Technologies Used**
- Tableau: For data analysis and visualization from dataset.
- Microsoft Excel: For checking Dataset.
- Google Colab: To retrieve data on likes, views, and comments using the YouTube API.
- PowerPoint: For presenting insights in an easy-to-understand presentation.

## **Usage Guide**
- Cloning Repository: Clone this repository to your local machine with the command: `git clone https://github.com/robynhood99/DataAnalyst_NewJeans.git`
- Open File Dataset: Open the file to view the contents of the downloaded file.
- Open Google Colab: Open the file to view result about Youtube Data (Likes, Comment, and Views)
- Open File Tableau: Open file tableau (.twb) in Tableau App to see the entire analysis process and visualization result and maybe you can improve about this file.
- View Result: Use the Result.pdf file to get a visual summary of the analysis and key insights.
- Dataset: The dataset.xlsx file can be used to perform further analysis or verify results with raw data.

## **Normalization Formula**
1. For Youtube Popularity:
   **Popularity = 0.5*(Youtube View)+ 0.3*(Youtube Likes) + 0.2*(Youtube Comment)**
   NB: You can adjust the weight values as desired.

2. For Normalization Popularity:
   **Youtube Popularity = (Popularity - Min Popularity)/(Max Popularity - Min Popularity) * 100**
   NB: To find the minimum and maximum popularity in Excel, use the formulas =MIN() and =MAX(). The data inside the parentheses should be taken from the Popularity column.


## **Conclusion**
NewJeans' success is driven not only by catchy music but also by innovative concepts, varied content, and strong fan engagement. As the group continues to release new music, we anticipate steady growth in their streaming and viewership data. This project provided valuable insights into how strategic releases and fan interaction can shape the success of an idol group in the competitive K-pop industry.

   
