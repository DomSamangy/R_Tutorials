# R_Tutorials

To complement my R tutorials on YouTube, this repository contains the R markdown files that contain the scripts I used to produce the visualizations in the videos. Those can be found here: https://www.youtube.com/playlist?list=PL10a1_q15Hwr4H5dCXQD3htK5VGfwjrgq. 

The tutorials included are:

- NBA and NCAA basketball shot charts utilizing the NBA API and ncaahoopR package.
    - The tutorial shows how to create a court, scrape player shot data, and finally plot and customize an aesthetcially pleasing shot chart. The finished products can be seen above in png form!
![Example_NBA_Shot_Chart_Durant](https://user-images.githubusercontent.com/70119566/125554311-0ca5a6bf-707b-48f3-9d28-2d60c3f8b380.png)
- Using rvest to scrape baksetball-reference.com and fbref.com and then visualizing relationships using scatter plots.
    - The tutorial shows how to scrape indivudal tables from the aforementioned websites. We then utilizee ggplot2 to visualize the relationships between xG and xGA in the Premier League and offensive and defensive rating in the NBA.
![nba](https://user-images.githubusercontent.com/70119566/125554339-3ed4238b-96ec-461c-8a34-4ed718269889.png)
- Creating NBA shot and Soccer pass heatmaps using nbastatR and StatsBombR packages.
    - The tutorial shows how to create heatmaps for both NBA shots and Soccer/Football passes using geom_contour_2d_filled. FCrStats's SBPitch package is also used to plot a pitch and other customizable features are shown as well.
![CP3_Heatmap](https://user-images.githubusercontent.com/70119566/125554356-251b279d-da68-45a8-83cb-205e78a0eec2.png)
![Example_Soccer_Heatmap](https://user-images.githubusercontent.com/70119566/125554276-b578c3d8-b513-46ec-bd74-36e145679766.png)
- Creating NBA and Soccer/Football poalr/pizza charts.
    - The tutorial shows how to create heatmaps for both NBA shots and Soccer/Football using a manually created data frame and scraping football reference scouting reports from the worldfootballR package.
  ![Example_Soccer_Polar](https://user-images.githubusercontent.com/70119566/142473174-cd727b32-18e6-46c7-9a00-17e182b456c1.png)
  ![Example_NBA_Polar](https://user-images.githubusercontent.com/70119566/142473196-45c56ac9-519d-4c1a-98ed-a61e4a8a115f.png)
- Plotting basketball and soccer shot charts from manually created event data
    - The tutorial shows how to create basketball and soccer shot charts using the sporty R package and plotting tools from @nguyenank_ and @Torvaney. This can be a great tool for coaches from either sport and at any age level by allowing you to create your own historical database and also by creating high-level visuals! 
![basketball_shot_chart](https://user-images.githubusercontent.com/70119566/148167389-c02f5bff-d58c-45e5-a3b6-d8d235f57db1.png)![soccer_shot_chart](https://user-images.githubusercontent.com/70119566/148167430-e0e6e785-6329-4f8b-8d8e-31759183380f.png)

- Soccer/Football Individual Game Shotmaps
    - Using Statsbomb open event data from their R package "StatsBombR", I show how to create individual game shotmaps. The packages primarily used are ggplot and tidyverse.
    - ![chelsea_shot_map_tutorial](https://user-images.githubusercontent.com/70119566/159566698-082612eb-dc2d-45ca-afd4-09f29ec909ac.png)
    - ![bayern_shot_map_tutorial](https://user-images.githubusercontent.com/70119566/159566707-a83ccd7b-5530-47a1-8665-4e5836481519.png)

- NBA Bar Charts (Basic & Advanced)
    - Using the nbastatR package, I show how to access player's career stats and then create bar charts to show year-over-year trends with points per game and grouped shooting percentages.
    - ![luka_pts_bar_chart](https://user-images.githubusercontent.com/70119566/189935025-fea1a036-c7b2-411e-94f7-e4611c23012d.png)
    - ![player_2_pct_bar_chart](https://user-images.githubusercontent.com/70119566/189935114-f1d85c26-b29b-40c8-9c7c-f03c9dd14d30.png)

    
