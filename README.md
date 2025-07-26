# Maven-Bookshelf

## Problem Statement:

Readers and publishers lack a centralized system to analyze book performance across genres, authors, and publication years. There is no easy way to identify top-rated books, trending genres, or engagement patterns based on ratings, votes, and comments. This makes it challenging to understand user preferences and make data-driven decisions for book recommendations and publishing strategies.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv, folder and xlsx files.
- Step 2 : Open power query editor & in view tab under data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : I found that some columns have mismatched data types , so i manually changed all columns data type.
- Step 5 : According to requirements i droped null values and errors.
- Step 6 : As per the FRD also filtered out negative values.
- Step 7 : for the time series analysis created Month name & Month number column.
- Step 8 : In the Power BI Desktop, In the report view, under the view tab, theme was selected.
- Step 9 : Since the data contains various info about Summary, Book Analysis,  Rating Analysis etc. Visual filters (Slicers) were added.
- Step 10 : I create three page report, on summary page Four Card visuals were added to the canvas, to representing Total Comments, Total Votes and Total numbers Of Books.
- Step 11 : A Area Chart was also added to the report design area representing the Monthly Ratings.
- Step 12 : On a Books Analysi page card , pie chart added to show Description, Rating, Genre.
- Step 13 : On a Rating Analysis page were Bar Chart , Column Chart, Dount Chart added to show vote by Genre, Mothns By Original Title, Ratings By Authors.

- Step 14 : A Area Chart visual was used to represent monthly ratings.
Snapshot of visual,

<img width="586" height="374" alt="Image" src="https://github.com/user-attachments/assets/cae101bf-659c-40f3-aa32-31e9bf5c7ae7" />

- Step 15 : A Pie Chart Visual was used to show Persentage Total Comments,Votes,Ratings.
  Snapshot of tile

  <img width="484" height="348" alt="Image" src="https://github.com/user-attachments/assets/d4e561dd-a6cd-4f0f-97ed-35ebc370ae70" />

- Step 16 : Used Bar Chart to represent Rating By Genre.
  Snapshot of Bar Chart,

  <img width="661" height="320" alt="Image" src="https://github.com/user-attachments/assets/cd54953c-b345-4e1a-9b05-a56d05fc48ac" />


 # Report Snapshot (Power BI DESKTOP)

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/bf064a4b-9e65-435b-b337-48c3434d5c60" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/0ba75a64-14c7-4ed7-be0f-8258f46f45b5" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/c16df8c1-13d9-4dd2-a9bd-98b2568aa37c" />


# Insights

### [01] Author Performance in Ratings:

- Zoraida Cordova and Zoe Sugg dominate the ratings chart, each contributing around 31% of the total ratings.

- Zora Neale Hurston follows with nearly 20%, making her the third most rated author.

- Authors like Zoe Marriott, Zoe Heller, and Zoey Dean have significantly lower rating shares, each under 10%.

### [02] Comments and Votes Engagement:

- From the detailed book view (A Nameless Witch by A. Lee Martinez):

- Ratings make up the largest share (≈70%) of engagement, followed by comments (≈16%) and votes (≈14%).

- High-rated books typically attract more comments, indicating strong reader interaction.

### [03] Genre Correlation with Authors:

- Authors writing in young-adult, romance, mystery, and thriller genres tend to receive the highest ratings and votes.

- Zoraida Cordova and Zoe Sugg, who are prominent in young-adult genres, lead in overall engagement.

### [04] Monthly Trend Analysis:

- Ratings peak in January (over 70K) and again show a rise in July, suggesting seasonal reading spikes.

- The lowest rating activity occurs in November and October, indicating less engagement during those months.
