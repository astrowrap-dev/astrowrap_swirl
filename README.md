Introduction
------------

[Swirl](http://swirlstats.com/) (Statistics with interactive R learning) is an upcoming R package that aims to provide a platform/toolkit for learning statistics and data analysis within the R environment itself. [astRowRap](http://astrowrap-dev.github.io/astrowrap/) intends to leverage this platform for creating a set of lessons in R and data analysis laced with examples from Astronomy and thus provide an easy and guided introduction for beginners.

Installation
------------

In order to study an astRowRap lesson, the R packages 'swirl' and 'astRowRap' must be installed. This can be done by executing the following commands in the R console:
 
<pre># To install 'swirl'
install.packages("swirl")

# To install 'astRowRap'
install.packages("devtools")
library(devtools)
install_github("astrowrap", "astrowrap-dev")
</pre>

Once these pre-requisities are fulfilled, all astRowRap lessons can be installed using:

<pre>library(swirl)
install_course_github("astrowrap-dev", "astrowrap_swirl", multi=TRUE)
</pre>

After installing the lessons, key in 

<pre>swirl()</pre>

and follow the instructions thereafter to study a lesson of your choice.

