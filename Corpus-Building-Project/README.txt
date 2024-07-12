Corpus key terms from Factiva - 

Target: 

Factiva 1 - 10 (wc > 50 and ("covid") and ("online food"))
Factiva 11 - 30 (wc > 50 and ("covid") and ("dine-in") and 01/01/2020 - 01/01/2022)
Factiva 31 - 41 wc > 50 and ("covid") and ("fear")  and ("online") and ("grocery") and 01/01/2020 - 01/01/2022)
Factiva 42 - 45 (wc > 50 and ("pre-covid") and ("online") and ("food"))
Factiva 46 - 48 wc > 50 and ("covid") and ("restaurants") and ("closed") and (01/01/2019 - 01/01/2022)
Factiva 49 - 56 wc > 50 and ("pandemic") and ("job") and ("impact") and ("dine") and (01/01/2019 - 01/01/2022)

Reference:

wc>50 and ("dine") and ("restaurant") and ("jobs") and ("created")
wc>50 and ("dine-in") and ("restaurant") and ("serene")
wc>50 and ("supermarkets") and ("groceries") and ("shopping")
wc>50 and ("restaurant") and ("dine")


Process the extract the corpus files - 

1. Login to the factiva - Databases A-Z - Library - University of Canterbury
2. Modify the search string for example : wc > 50 or (("before covid" or  "pre-covid")) and ("digital commerce") and ("consumer")
3. In the results, select the article of your interest and click Save as "Article Format". 
4. Once the article opens up download the html page - save as type "Web page , complete" . It will download the folder as well 
5. Login into https://jupyterhub.canterbury.ac.nz/DIGIteaching
6. Create a new folder "CorpusProject" 
7. In that place this file "parse-factiva-html.ipynb"
8. Create a new sub folder "outputcorpus" in the "CorpusProject" folder 
9. Create a new sub folder "inputfactivahtml" in the "CorpusProject" folder
10. Inside the sub folder "inputfactivahtml" place the downloaded folder "Factivahtml" files and the Factiva.html file 
11. Run the notebook "parse-factiva-html.ipynb" provided below in the chat.
12. Create a new folder "finalcorpus" in the "CorpusProject" folder
13. Copy the output txt file in the "corpus" folder to the "finalcorpus" folder
14. Delete the folder contents inside the "Factivahtml" and Factiva.html file
15. Search for a new article and repeat the steps 3,4,10,11,13,14


YouTube video links - 

video_id = "https://www.youtube.com/watch?v=88SEmCS5aCU&t=40s"
file_name= "Optimizing the Dine-In Restaurant Experience ft. Jacky Yamada"

video_id="https://www.youtube.com/watch?v=vX_PcqeIsT8&t=88s"
file_name="The Impact of Covid-19 Pandemic to online food delivery service (fullvideo)"

video_id="https://www.youtube.com/watch?v=BlP_KzTeON0"
file_name="What It’s Like To Make Deliveries During The Coronavirus Pandemic"

video_id="https://www.youtube.com/watch?v=GGwVidfedT0"
file_name="Episode 63 How does COVID 19 Coronavirus Impact Us as Food Delivery Contractors (From 2020)"

video_id="https://www.youtube.com/watch?v=eeOqyWjHDfQ"
file_name="Coronavirus outbreak: Delivery and grocery workers on the frontlines - Wait There's More podcast"

video_id="https://www.youtube.com/watch?v=Ex7tkD_amuE"
file_name="PODCAST | COVID-19 Frontline Workers Part 13: A delivery driver shares his story"

video_id="https://www.youtube.com/watch?v=olTLWB6_9mY"
file_name="Podcast: COVID-19 pandemic's impact on restaurants and hospitality"

video_id="https://www.youtube.com/watch?v=kM0skNuu6T0"
file_name="Jason Richards: Robotic Food Delivery, Crowdfunding, and Lawmakers | Sense Think Act Podcast 7"

video_id="https://www.youtube.com/watch?v=b3rIH2Bk8aE"
file_name="Virtual Event | How are food businesses coping with COVID-19 and its aftermath?"

video_id="https://www.youtube.com/watch?v=7JcaTz-DtAg"
file_name="COVID and Grocery eCommerce Grocery Podcast S3 E9"