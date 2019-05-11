Author: Marie Dubremetz

**Description**

This folder contains the corpora and outputs of the last part of my (to be published) Frontiers in Digital Humanities Article.

***Source***

In the folder "source" you will find the three different input files:
* a corpus of titles of fiction books that I crawled via a python script on the www.waterstones.com/category/fiction website
* a corpus of titles of scientific articles from DBLP. For the need of my experiments, I had to limit it to a sample of 192 000 titles as my list of fiction books did not get over this number.
* a corpus of quotes. The quotes corpus has not been collected by me and therefore is not stored as such on my official repository. You can freely access it by following the reference/link below:
Liling Tan. 2015. A Corpus of Quotes. https://github.com/alvations/Quotables. Kind thank you to Liling Tan!

***Outputs of my experiments***

The files *_ana.txt contain the epanaphora found by my machine in the corpora

The files *_epi.txt contain the epiphora found by my machine in the corpora

The files *_chiasmus.txt contain thechiasmis found by my machine in the corpora

**File Example**

This is what contains the file quote_chiasmus.txt:
			====*1*====+
					  
1. >righteous >sinner
2. righteous who think they are sinners and the sinners who think they are righteous
3. There are only two kinds of men: the {righteous} who think they are {sinners} and the {sinners} who think they are {righteous}.
4. R= 1 S= 99.77%



			
					====*2*====+
					  
1. >success >happiness
2. Success is not the key to happiness . Happiness is the key to success
3. {Success} is not the key to {happiness}. {Happiness} is the key to {success}.
4. R= 2 S= 98.32%



			
					====*3*====+
					  
1. >advertising >public
2. advertising had a little more respect for the public , the public would have a lot more respect for advertising
3. If {advertising} had a little more respect for the {public}, the {public} would have a lot more respect for {advertising}.
4. R= 3 S= 98.00%

**Reference**
[1] Marie Dubremetz, ‘Rhetorical Figure Detection: Chiasmus, Epanaphora, Epiphora’, Frontiers in Digital Humanities 5 (2018): 10.

**Contact**

Marie Dubremetz. firstname.lastname@lingfil.uu.se
