# Video Games Sales Data (1980-2010) Analysis with Tableau
## Introduction

### About the Analysis 
The dataset on video game sales from 1980 to 2010 will let us take a tour through gaming history! Some questions would be solved in order to perform the analysis and those include: **what is the most sold video game, or which gaming genre was the most popular in the early 2000's?** Moreover, **we could even filter for our old favorite video game to see how many other people enjoyed it!** 
At the end, we would have a story with some dashboards in Tableua for this data analysis.

### About the Dataset
The data structure looks straightforward: We have the name of the game, the platform it was released on like the Wii, Gameboy, or Playstation. We have the year the game was released, the genre, the publisher, and finally the sales in million by region. 
**Note: sales does not refer to the sales in Dollar or Euro, but to the amount or copies of video games sold.** Before we continue let's make sure we **understand the term release year** correctly. Pokemon Blue and Red for example was released in 1996, **meaning that all sales for Pokemon Blue and Red get attributed to the year 1996**.

## Perform Analysis
### 1. Create a dual axis graph
The video games dataset contains a ton of information on video game sales from 1980 until 2010. Our first task is to investigate the dataset and uncover insights about the gaming industry. Here, we have explore global sales using barplot and compare it with rest of the other sales such as EU sales, Japan sales, NA sales, and Other sales by plotting those as line charts in the same plot.
[Picture]

### 2. Create a dashboard
The task is to investigate how Playstation video game sales developed over time, which platform was the most popular, and which were its most popular games and genres. A dashboard has been created to answer these questions. 
We can determine some important information by asking question such as: 
**1. What is the Genre of "GTA San Andreas", the top selling video game? **
**2. Is it equal to the most popular Playstation genre?** 
and so on from the dashboard.  
[Picture]
From the dashboard (Top video games bar chart) it can be clearly identified that the Genre of **"GTA San Andreas"** is **Action**
and (from Sales by Genre tree map) **Action** is the most **popular Playstation genre**.

### 3. Add some filter options 
The dashboard is great, but what if we are only interested in games from a specific publisher (like "Sony Computer Entertainment") for a particular genre? It would be possible by adding a publisher filter and enabling the treemap to function as a genre filter.
[Picture]
The graph on the top right changes depending on how we select our filter(s)! If we, e.g., like "Action", we can see how many action games were sold on the "PS", "PS2", "PS3" and "PSP". We'll need this to answer a question:
**How many video game copies (in millions) did "Sony Computer Entertainment" sell for the PS2 in the "Racing" Genre?**
The answer is **35.41 million** according to the graph.

### Create and Navigate a Story
Here, we will build a story to help answer questions about the Playstation, Nintendo, and Xbox gaming systems. Both the <code>Sales by Platform</code> (top right) and <code>Sales by Genre</code> (bottom right) are enabled as filters. 
A similar dashboard for Nintendo and Xbox has also been setup (in the same way we have done it before but the analysis are based on Nintendo and Xbox respectively), so we combined them to to create our story. 
[Picture]
Based on the story we have solved the following questions:
**1. The best-selling "Shooter" on both the "Playstation (PS)" and "Xbox" was "Call of Duty: Black Ops". On which platform did it have the highest sales? "Playstation" or "Xbox"?**
[Picture]
The story in the picture tells us (by viewing on the "Sales by Platform" plot) that X360 (Xbox) had more than 150 million sales.
[Picture]
The above story tells us (by viewing on the "Sales by Platform" plot) that PS2 (Playstation 2) had more 100 million sales.
**Indeed! "Call of Duty: Black Ops" sold more copies on the Xbox than on Playstation.**

**3. What was the name of the best-selling "Playstation 2 (PS2)" game published by "Electronic Arts" in the "Simulation" genre?**
[Picture]
The above story tells us (by viewing on the "Top Video Games" plot) that **The Sims** was the **best-selling "Playstation 2 (PS2)"** game that was released in 2003 and it sold 2.77 copies globally.
