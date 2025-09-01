# Introduction

This small project was just a simple fun exploration into determining on average, which restaurant has the unhealthiest food options. 
The majority of the task for me was to just take the single table dataset from kaggle and construct a star schema from it so that I could begin creating some visuals. I decided to keep the overall design simple with the following tables:
* Fact Table: `Nutrition Data`
* Dim Table: `Restaurant Lookup`
* Dim Table: `Item Lookup`

If you want to see the visual, feel free to download the .pbix file and play around and extend it yourself. I would have loved to add more details like individual item breakdowns and their overall nutrition profiles, but unfortunately time was not on my side. I have some unused measures created for `% daily` values if anyone is interested in creating some visuals comparing how items impact the recommended daily intake amounts.

# Acknowledgements
This nutrition data set was originally sourced from kaggle: https://www.kaggle.com/datasets/ulrikthygepedersen/fastfood-nutrition
