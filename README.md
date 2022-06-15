# Data Generation Using optimization
![visitors](https://visitor-badge.glitch.me/badge?page_id=gilzeevi25.Data-generation-using-Optimization.issue.1) <br/>
I had to generate 2 populations with specific properties as specific mean,variance etc.
furthermore, i had to bind those datasets together with some interquartile range constrain.

Due to the lack of statistics deep understanding at that time, i decided to tackle the problem as a naive engineer - i formulated an optimization problem with linear and nonlinear constraints in order to generate this kind of datasets.

I decided to utilize one of the optimization's disadvantages into my advantage, where it is known that while optimizing, our target function is likely to hit local minimas in some cases.

With that feature taken into consideration in my solution, i could ensure that each time i apply data generation, a 'random' solution is generated and it differs with each solution, due to the 'disadvantage' of hitting local minimas.
