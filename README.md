fedspeak
========

pittsburgh_r_useR_group_Nov_4_2013 (http://www.meetup.com/Pittsburgh-useR-Group/)

Purpose: to analysize fedspeak

Fedspeak/Greenspeak Definition: 
	“Language of purposeful obfuscation to avoid certain questions coming up where saying 'no comment' is in 
 	 fact an answer. So I proceed with 4 or 5 sentences which become increasingly obscure and the Senator 
	 thinks his questions has been answered.” 
                  - Alan Greenspan, somewhere on youtube -> http://www.youtube.com/watch?v=9JHctWztRww
                  
Goods: 

 * created time series from topic model proportions using R and imported these results into d3.js
 * rPython_NLTK.R R to Python interface to access implementation of Marti Hearst's Textiling algorithm, auto-segmentation of texts using roving windows and cosine similarity metrics to identify topical cleavages/breaks, i.e. paragraphs or narrames: http://people.ischool.berkeley.edu/~hearst/research/tiling.html
 * tmIndMarkReg.R is the heart of the project and it is also the most messy, code-wise
 

TO DO: 

 * clean up process of generating time series from topic model proportions (*apply-family of f(x))
 * create annotated d3.js (http://d3js.org/) /rickshaw.js (http://code.shutterstock.com/rickshaw/) application
 * create project bibliography
 * implement n-gram tokenization using RTextTools instead of tm, as it doesn't require RWeka's rJava dependency with its memory limits
 * also use unique function in RTextTools package to obtain k for topic model #: http://www.rtexttools.com/1/post/2011/08/getting-started-with-latent-dirichlet-allocation-using-rtexttools-topicmodels.html

http://www.newyorker.com/online/blogs/johncassidy/2014/04/what-janet-yellen-didnt-say-the-b-word.html

interest rates and unemployment:
http://www.counterpunch.org/2014/05/12/the-fed-and-manufactured-crises/

http://www.counterpunch.org/2014/05/23/monetary-policy-as-class-warfare-revisited/

a bit on fedspeak: http://www.nytimes.com/2014/07/18/business/the-feds-bully-pulpit-on-wall-street.html?_r=0

https://www.youtube.com/watch?v=0liegrixknA

Julio Yglesias (j/k) praises Abenomics: http://www.slate.com/articles/business/moneybox/2013/05/abenomics_is_working_shinzo_abe_s_policies_are_leading_the_way_to_recovery.html

-------------------------------
very promising: https://github.com/kingfish777/concept_drifts

Yellen continues along in Burns/Volcker/Greenspan/Bernanke-an pattern:
http://www.nakedcapitalism.com/2015/02/yellen-defies-congress-defends-greenspanian-general-counsel-scott-alvarez-elizabeth-warren-grilling.html

<script data-gittip-username="kingfish777"
        src="//gttp.co/v1.js"></script>
