

<br> <br>

<img src="./board.svg" alt="" /> 



<h1>:rocket: Dataset</h1>
<p> YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for. <strong> This dataset is a daily record of the top trending YouTube videos.</strong> </p> 
<code> 📌   <i> Note:  <br> I have restricted processing on the CAvideos.csv file (Canada Country data) </i> </code>

<br>
<br>

<h1> :star2: Process Timeline  </h1>
<li> :one: Dataset Preview </li>
<li> :two: Data Wrangling </li>
<li> :three: Exploratory Data Analysis </li>
<li>:four: Conclusion </li>
<li> :five: Resources </li>
 <br> 

<h1> :star2: Dataset Preview  </h1>



<h3><li> 💡 Top Rows</li></h3>
        ☑️  <code> This feature allows us to take a peek at the dataset content </code> <br> 
<br>
 <img width="500" alt="Screen Shot 1442-12-09 at 10 50 26 PM" src="https://user-images.githubusercontent.com/59771760/126218613-b7f4b1f1-e50f-47b6-baab-f06d34480425.png">


<h3><li> 💡 Summary</li> </h3>
☑️ <code> Concise summary of the DataFrame such as DataFrame imension and calculating some statistical data</code> <br><br>

<img width="500" alt="Screen Shot 1442-12-09 at 10 00 33 PM" src="https://user-images.githubusercontent.com/59771760/126212948-ddcf8916-e33c-4c39-b2dc-ee77c6880636.png">


<img width="500" alt="Screen Shot 1442-12-09 at 10 10 25 PM" src="https://user-images.githubusercontent.com/59771760/126213980-231912ba-6ff3-4755-aae3-6dcd3c91aafc.png">
<br> <br>
<h1> :star2: Data Wrangling  </h1>
  
<p>In this section we will load in the data, check for cleanliness, then trim and clean the dataset for analysis.</p>

<h3> 💡 Data cleaning </h3> <br>
☑️ <code> In my point of view, all of the attached columns are useless on the investigation. As a result of that, we need to make the dataframe cleaner by dropping them.</code> <br> <br>
<img width="500" alt="Screen Shot 1442-12-09 at 10 52 41 PM" src="https://user-images.githubusercontent.com/59771760/126218908-7e2b112e-aa9e-4877-8fe3-371ffb7ad1b7.png">


<h3> 💡 Missing Values </h3> <br>
  ☑️ <code>After dropping some values , missing values were found.We need to drop them to clean the dataset .Such of columns that contain a missing value: </code>
 <br> <br>
<img width="448" alt="Screen Shot 1442-12-10 at 4 00 37 AM" src="https://user-images.githubusercontent.com/59771760/126246494-229de8e4-3c2b-4bf3-9147-14cac96c9b11.png">
☑️ <code> No dublicates </code> <br><br>
<img width="708" alt="Screen Shot 1442-12-10 at 4 01 50 AM" src="https://user-images.githubusercontent.com/59771760/126246542-67554df6-a49a-40d9-bc6a-849b61b837ce.png">


  
  
  <h1> :star2:  Exploratory Data Analysis  </h1>
    <h3> 💡 Q1: What are the top 5 videos generate the highest comments and likes? Is there a special category they belong to it?<h3>
 
    Figure 1. 
  <h3> 💡 Q2: Is there a relation between dislikes and videos get removed or have errors? <h3>
    Figure 2. 
 <h3> 💡 Q3: Is there a relation between comments and likes ? <h3>
    Figure 3. 
    
 
 <h1> :star2: Conclusion </h1>
   
   <h1> :star2: Resources </h1>
  


