# Python-Spidering
#### Gmane/mail model

Analyzing an EMAIL Archive from gmane and vizualizing the data
using the D3 JavaScript library

gmane.py : The program scans content.sqlite from 1 up to the first message number not
already spidered and starts spidering at that message.  It continues spidering
until it has spidered the desired number of messages or it reaches a page
that does not appear to be a properly formatted message.

gmodel.py : The gmodel.py program does a number of data cleaing steps. It completely wipes out and re-builds index.sqlite, allowing  to adjust its parameters and edit the mapping tables in content.sqlite to tweak the 
data cleaning process.

gbasic.py : Simplest data analysis is to do a "who does the most" and "which 
organzation does the most"?  This is done using gbasic.py

gword.py : This produces the file gword.js which can visualize using the file 
gword.htm.

gline.py :  It visualizes email participation by organizations over time.
