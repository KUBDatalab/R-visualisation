---
# Please do not edit this file directly; it is auto generated.
# Instead, please edit 09-whats-next.md in _episodes_rmd/
title: "Whats next?"
teaching: 10
exercises: 5
questions:
- "FIX ME"
objectives:
- "FIX ME"
keypoints:
- "FIX ME"

source: Rmd
---





## What should I do next?

First of all: If you do not have data you want to visualize 
already. Find some!

[Kaggle](https://www.kaggle.com/datasets) host competitions 
in machine learning. For the use of those competitions, they
give access to a lot of interesting datasets to work with.
With more than 200.000 datasets at time of writing, it can
be a bit overwhelming, so consider looking at the "[Data Visualization](https://www.kaggle.com/datasets?fileType=csv&tags=13208-Data+Visualization)" category. The link provided only shows datasets saved as CSV-files, and has only about 2.500 datasets.

## Play around!

ggplot2 comes with a lot of functionality. This is the
list of build-in geoms in ggplot2:


~~~
 [1] "geom_abline"            "geom_area"              "geom_bar"              
 [4] "geom_bin_2d"            "geom_bin2d"             "geom_blank"            
 [7] "geom_boxplot"           "geom_col"               "geom_contour"          
[10] "geom_contour_filled"    "geom_count"             "geom_crossbar"         
[13] "geom_curve"             "geom_density"           "geom_density_2d"       
[16] "geom_density_2d_filled" "geom_density2d"         "geom_density2d_filled" 
[19] "geom_dotplot"           "geom_errorbar"          "geom_errorbarh"        
[22] "geom_freqpoly"          "geom_function"          "geom_hex"              
[25] "geom_histogram"         "geom_hline"             "geom_jitter"           
[28] "geom_label"             "geom_line"              "geom_linerange"        
[31] "geom_map"               "geom_path"              "geom_point"            
[34] "geom_pointrange"        "geom_polygon"           "geom_qq"               
[37] "geom_qq_line"           "geom_quantile"          "geom_raster"           
[40] "geom_rect"              "geom_ribbon"            "geom_rug"              
[43] "geom_segment"           "geom_sf"                "geom_sf_label"         
[46] "geom_sf_text"           "geom_smooth"            "geom_spoke"            
[49] "geom_step"              "geom_text"              "geom_tile"             
[52] "geom_violin"            "geom_vline"            
~~~
{: .output}
ggplot2 is also build as an extensible package, making 
it relatively easy to build extensions, that does things
that ggplot2 is not able to on its own. [This page](https://exts.ggplot2.tidyverse.org/) contains a collection of these.


## Get some inspiration!

The website/book [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/) is a great resource for tips, tricks and thinking about visualizations, 
especially the [directory of visualizations](https://clauswilke.com/dataviz/directory-of-visualizations.html). Note, however, that the author does not provide examples of the code you need to write to make the plots.

There exist an online challenge, [#30DayChartChallenge](https://30daychartchallenge.org/), that 
challenges you to create a data visualization on a certain topic each day of april. That can be a bit of a mouthful and 
we are not going to participate ourselves. But! The collection 
of visualizations from 2022 is humongous, and a great place
to find ideas.


## Other online courses

[EdX](https://www.edx.org/search?q=ggplot) offers a multitude of interesting courses - here we link to their ggplot-related courses.

Codecademy also offers free courses (and a certificate of completion if you pay) [This course](https://www.codecademy.com/learn/learn-ggplot-2) offers
a more indepth introduction to ggplot2.




{% include links.md %}