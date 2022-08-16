## Introduction
> What can we say about the success of a movie before it is released? Are there certain companies (Pixar?) that have found a consistent formula? Given that major films costing over $100 million to produce can still flop, this question is more important than ever to the industry. Film aficionados might have different interests. Can we predict which films will be highly rated, whether or not they are a commercial success?

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

> The main aim of this project is centered on data wrangling. Although, little insights were explored. The raw datasets were then used to produce a master data that can be used for analysis.


## Findings
> It has been gathered that movies like Jurassic World	32.985763, Mad Max: Fury Road, Interstellar, etc are well know by the people. However, this does not relate to higher rating nor increase in profit. Instead, movies like Pink Floyd: Pulse, Queen - Rock Montreal, The Art of Flight, The Shawshank Redemption	 are not popularly known but are highly rated.
> Also, it has been established that the duration of a movie, day, monthe and year of release of a movie affect its popularity and most importantly, profit.<br>
> Lastly, It is a good thing to note the upward trend in the film industry over the year.And, based on this, the following conclusions were reached:
- The best day of the week to release a movie is Wednesday
- The best month of the year to release a movie is Wednesday
- That the future is bright for the film industry

### Limitations:
- The number of rows with misssing values are to many (2199 after dropping extraneous columns). This reduced the total number of available data
- Get the time of release (perhaps in the release_date column)would have been helpful in determining when people normally have time to see movies
- Having a single (most appropriate class) for columns like genres would have made it easy to determine which genre of movies are highly rated. [Read more]('movie_success_analysis.ipynb')