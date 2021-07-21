

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
       
<br>
 <img width="500![Uploading Screen Shot 1442-12-10 at 6.23.33 PM.png…]()" alt="Screen Shot 1442-12-10 at 6 22 26 PM" src="https://user-images.githubusercontent.com/59771760/126350870-729ec2f5-c6a4-4450-9267-0df776400583.png">  ☑️  <code> Figure 1. This feature allows us to take a peek at the dataset content </code> <br> 


<h3><li> 💡 Summary</li> </h3>


<img width="500" alt="Screen Shot 1442-12-09 at 10 00 33 PM" src="https://user-images.githubusercontent.com/59771760/126212948-ddcf8916-e33c-4c39-b2dc-ee77c6880636.png"> 
☑️ <code> Figure 2. Concise summary of the DataFrame such as DataFrame dimensions</code> <br><br>


<img width="500" alt="Screen Shot 1442-12-09 at 10 10 25 PM" src="https://user-images.githubusercontent.com/59771760/126213980-231912ba-6ff3-4755-aae3-6dcd3c91aafc.png">
☑️<code> Figure 3. Concise summary of the DataFrame such as DataFrame calculating some statistical data</code> <br><br> <br>

<h1> :star2: Data Wrangling  </h1>
  
<p>In this section we will load in the data, check for cleanliness, then trim and clean the dataset for analysis.</p>

<h3> <li>💡 Data cleaning </li> </h3> <br>

<img width="500" alt="Screen Shot 1442-12-09 at 10 52 41 PM" src="https://user-images.githubusercontent.com/59771760/126218908-7e2b112e-aa9e-4877-8fe3-371ffb7ad1b7.png"> 
☑️ <code> Figure 4. In my point of view, all of the attached columns are useless on the investigation. As a result of that, we need to make the dataframe cleaner by dropping them.</code> <br> <br>


<h3> <li>💡 Missing Values </li></h3> <br>
  ☑️ <code>After dropping some values , missing values were found.📌📌</code>
 <br> <br>
<img width="448" alt="Screen Shot 1442-12-10 at 4 00 37 AM" src="https://user-images.githubusercontent.com/59771760/126246494-229de8e4-3c2b-4bf3-9147-14cac96c9b11.png"> 
 ☑️ <code>Figure 5. Clean missing values issue</code>
 <br> <br>



<img width="708" alt="Screen Shot 1442-12-10 at 4 01 50 AM" src="https://user-images.githubusercontent.com/59771760/126246542-67554df6-a49a-40d9-bc6a-849b61b837ce.png"> 
☑️ <code> Figure 6. No dublicates </code> <br><br>



  ```python
  df.sort_values('id', inplace=True)
df.drop_duplicates(subset='id' , keep=False , inplace=True)
df
# to drop the duplicated values
  ```
  ☑️ <code> Figure 7. No need for the attached code segment</code> <br>
  
  
  <h1> :star2:  Exploratory Data Analysis  </h1>
  <h3> <li>💡 Q1:  Which category ID had the highest views? Which that category belongs to?</li> </h3> 
<img width="658" alt="Screen Shot 1442-12-10 at 6 48 19 PM" src="https://user-images.githubusercontent.com/59771760/126355189-d4984a70-7a76-48d4-b278-0b8b6b5e2240.png">
  Figure 8.
<h3> <li>💡 Q2: Is there a relation between dislikes and videos get removed or have errors?</li></h3>
    Figure 9. 
 <h3> <li>💡 Q3: Is there a relation between comments and likes ? </li></h3>
   <img width="644" alt="Screen Shot 1442-12-10 at 6 24 51 PM" src="https://user-images.githubusercontent.com/59771760/126351251-64152f85-e4f3-48c1-8b18-93661160960b.png">
                
Figure 10. 


<h3> <li>💡 Q4: Which channel titles had the most views ? </li></h3>
  <img width="771" alt="Screen Shot 1442-12-10 at 6 58 33 PM" src="https://user-images.githubusercontent.com/59771760/126356938-b12a964c-6800-4861-9c46-a423b6e2e5bb.png">

                
Figure 10. 
  
    
 
 <h1> :star2: Conclusion </h1>
 <li>In this analysis, I just analyze the case of trending YouTube in Great Britain. It will be the same way for consider other cases.</li>
   
   <h1> :star2: Resources </h1>
  <li>https://www.kaggle.com/datasnaek/youtube</li>
  <li>https://github.com/GalvanizeDataScience/pandas-eda-case-study</li>



