
Agent-based Epidemic simulation models in R
======

This repository includes a lightweight agent-based epidemic simulation model implemented in R. It was developed to explore cognitive and psychological impacts of various policy decisions.  This git repository includes R markdown files producing simulation output, plus markdown-generated web pages showing the results of the simulation.

This repository is made available for educational purposes. Users are cautioned that it should not be used for forecasting health care needs during this epidemic.




## The models

* [The base model](https://stmueller.github.io/epidemic-agents/web/epidemic-model-base.html)  [(code)](https://github.com/stmueller/epidemic-agents/blob/master/models/epidemic-model-base.Rmd)
* [Demographics model](https://stmueller.github.io/epidemic-agents/web/epidemic-demographics.html) [(code)](https://github.com/stmueller/epidemic-agents/blob/master/models/epidemic-demographics.Rmd)
* [Michigan geographic model](https://stmueller.github.io/epidemic-agents/web/epidemic-michigan.html)[(code)](https://github.com/stmueller/epidemic-agents/blob/master/models/epidemic-michigan.Rmd)
* [Travellers outside the network model](https://stmueller.github.io/epidemic-agents/web/epidemic-model-travellers.html) [(code)](https://github.com/stmueller/epidemic-agents/blob/master/models/epidemic-model-travellers.Rmd)


## Some visualizations from the network:

### Disease spread in a small-world network:
![](https://github.com/stmueller/epidemic-agents/blob/master/web/support_files/figure-html-base/base.gif)


Test::::

<img src={{site.url}}//web/support_files/figure-html-michigan/anim2.gif>

--------test over

### Disease spread in a geographic network representating the state of Michigan:
[Simulation of geographic networks of the state of Michigan](https://github.com/stmueller/epidemic-agents/blob/master/web/support_files/figure-html-michigan/anim2.gif)

### Disease spread in a demographic network including schools, workplaces, neighborhoods
![Simulation of extra-network vacationers entering the network](https://github.com/stmueller/epidemic-agents/blob/master/web/support_files/figure-html-demo/network.gif)

![Simulation of Demographic networks](https://github.com/stmueller/epidemic-agents/blob/master/web/support_files/figure-html-demo/animation.gif)

### Disease spread attributable to visitors entering the network from outside:
![Simulation of outsiders effect on disease](/web/support_files/figure-html-travellers/animation.gif)
