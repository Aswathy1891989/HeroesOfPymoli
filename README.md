# HeroesOfPymoli

After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. The assigned  task is to analyze the data for their most recent fantasy game Heroes of Pymoli. 

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

**Input**: purchase_data2.json and purchase_data.json.  <b>reading_File()</b> takes filepath as argument and creates dataframes. Combine the two dataframes and create single df.

The whole task is divided to analyze following 7 subtasks:
  <ol>
      <li> Total Number of Players::
        <b>players_count()</b> : Counts No.of Players
      <li> Purchasing Analysis (Total)::
        <b>total_analysis()</b> : function used to return dataframe with total values
      <li> Gender Demographics::
        <b>gender_total()</b>    : Analyse data based on Gender and return df 
      <li> Purchasing Analysis (Gender)::
        <b>gender_Analysis()</b> : Does Purchase Analysis  based on Gender and return df
      <li> Age Demographics::
        <b>age_group(criteria)</b>: Analyse data based on Age Group and return df
      <li> Top Spenders::
        <b>analysis_final(purchase_Data_Reader,criteria,aggregate_Val)</b>: returns a dataframe with Top 5 spenders
      <li> Most Popular Items::
        <b>purchase_count()</b> : Returns a df and df is sorted based on Purchase Count
      <li> Most Profitable Items::
        <b>purchase_count()</b> :Returns a df and is sorted based on Total Purchase values
  </ol>


### 
