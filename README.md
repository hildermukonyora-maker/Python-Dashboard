#Data analytics
#Python Dashboard
#Healthy Lifestyle Cities 2021 — Analytics Summary 44 global cities · Source: Healthy Lifestyle Cities 2021 (Kaggle) · Composite Health Score = equal-weighted index
Cities Analyzed	44 Avg Health Score 53	Avg Life Expectancy	78.2 yrs Top Ranked City Sydney
This dashboard analyzes lifestyle, environmental, and economic indicators across 44 global cities, combining them into a single composite Health Score. Sydney ranks as the top city overall, followed closely by Amsterdam, Tokyo, and Barcelona. On average, cities in the dataset report a life expectancy of 78.2 years and a moderate health score of 53 out of a possible higher range, with a fairly wide spread (min 33.8, max 68.8) reflecting real differences in urban living conditions.
Top 15 Cities by Health Score
The leaderboard is dominated by cities recognized for strong environmental and public-health standards: Sydney, Amsterdam, Tokyo, Barcelona, Tel Aviv, Melbourne, Fukuoka, Vienna, Stockholm, Helsinki, Geneva, and Copenhagen feature among the highest performers. These cities tend to combine lower pollution, higher water and gym-membership costs (a proxy for cost of living), and strong self-reported happiness.
Sydney  •  Amsterdam  •  Tokyo  •  Barcelona  •  Tel Aviv  •  Melbourne  •  Fukuoka  •  Vienna  •  Stockholm  •  Helsinki  •  Geneva  •  Copenhagen
Summary Statistics
Descriptive statistics across all 11 tracked metrics (n = 44 cities each) are summarized below. Takeout-places count shows the widest relative spread (std dev of 1,372.9 against a mean of 1,443.1), reflecting a few very dense outlier cities, while happiness score and life expectancy are comparatively tightly clustered.
Metric	                  Mean	    Median	Std Dev	    Min  	   Max
Sunshine (hrs/yr)	       2,241.8	    2,066	    555.0	    1,405	   3,542
Water cost (GBP)	         1.17	     1.20	      0.71	   0.15	    3.20
Obesity (%)       	       21.9	     22.3	     10.1	      3.9	    36.2
Life expectancy (yrs)	      78.2	    80.4	    5.24	    56.3	  83.2
Pollution index	            51.2	     52.6	     21.4	     13.1	  91.7
Annual hours worked	      1,676.2	    1,686	     153.3	 1,380	   2,137
Happiness score           	6.44	    6.90	     0.98	    3.57	   7.80
Outdoor activities count	  214.0	    189.5	     125.7	    23	   585
Takeout places count	    1,443.1	     998	    1,372.9	   250	   6,417
Gym membership (GBP)	     40.42	    37.33	     14.83	   16.07	73.11
Health score	             53.0	      53.15	      8.37	    33.8	68.8
Correlation Analysis
A Pearson correlation matrix across all metrics highlights several consistent relationships. Two dominant patterns emerge: pollution is a strong negative driver of both happiness and health outcomes, while cost-of-living proxies (water cost, gym membership) track positively with happiness, life expectancy, and health score — consistent with these being higher in wealthier, lower-pollution cities.
Variable Pair	Pearson r	Relationship
Happiness score ↔ Water cost	0.81	Strong positive
Happiness score ↔ Pollution index	-0.76	Strong negative
Life expectancy ↔ Health score	0.76	Strong positive
Happiness score ↔ Life expectancy	0.72	Strong positive
Pollution index ↔ Water cost	-0.73	Strong negative
Pollution index ↔ Health score	-0.64	Moderate negative
Happiness score ↔ Health score	0.64	Moderate positive
Life expectancy ↔ Water cost	0.61	Moderate positive
Outdoor activities ↔ Takeout places	0.53	Moderate positive
Key Takeaways
●	Pollution is the strongest negative factor: cities with higher pollution indices show markedly lower happiness (r = -0.76) and lower health scores (r = -0.64).
●	Happiness and water cost move together (r = 0.81), suggesting the priciest (typically cleaner, wealthier) cities also report the happiest residents.
●	Life expectancy is closely tied to overall health score (r = 0.76) and happiness (r = 0.72), reinforcing that the composite score captures genuine wellbeing signals.
●	Sunshine hours and annual hours worked show only weak correlations with health outcomes, suggesting they are less influential than pollution or cost-of-living factors in this dataset.
●	Outdoor activity levels correlate moderately with takeout-restaurant density (r = 0.53), possibly reflecting cities with generally higher levels of urban amenity and leisure infrastructure.
