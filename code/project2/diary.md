Data set(s):

Aqueduct Projected Water Stress Country Rankings, World Resources Institute
- http://www.wri.org/resources/data-sets/aqueduct-projected-water-stress-country-rankings
- http://www.wri.org/blog/2015/08/ranking-world%E2%80%99s-most-water-stressed-countries-2040

Organize the dataset
- Divide the dataset by All sectors, Industrial, Domestic, Agricultural
- Divide the dataset by BAU, optimistic, pessimistic
- show the water stress changes

"Baseline water stress measures competition for surface water, calculated as the ratio of local water withdraws over renewable supply. Projections are based on a business-as-usual scenario using SSP2 and RCP8.5."

- Rate 0-1 : low            water stress
- Rate 1-2 : low-medium     water stress
- Rate 0-1 : medium-high    water stress
- Rate 0-1 : high           water stress
- Rate 0-1 : extremely high water stress

Organize the dataset into to 12 cateria : All sectors, Industrial, Domestic, Agricultural water stresses; BAU, optimistic, pessimistic estimation

Ploted the water stress changes by each cateria.

toggle between BAU, optimistic, pessimistic projections
- reorganize the into three dataframe: BAU, optimistic, pessimistic projections
- cannot do it, using tufte slopegraph instead

Writing html code
- using D3.js
- I decided not to use tufte slopegraph. There are too many countries and the graph might trun into a mass.
- I am going to use horizontal bar chart.
- Make the bars larger than 1, larger than 0.75, larger than 0.5, larger than 0.25, and smaller than 0.0 have different colors.(cancel)

- Data : top 5, bottom 5 BAU of water stress each category.       (Done!!)
- circle                                                          (Done!!)
- three projections(BAU, optimistic, pessimistic) in one category (Done!!)
- lines bwtween the dots                                          (Done!!)
- tooltip                                                         (Done!!)



