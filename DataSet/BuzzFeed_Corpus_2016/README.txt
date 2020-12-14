BuzzFeed-Webis Fake News Corpus 2016
====================================
The corpus comprises the output of 9 publishers in a week close to the US elections. Among the selected publishers are 6 prolific hyperpartisan ones
(three left-wing and three right-wing), and three mainstream publishers (see Table 1). All publishers earned Facebook’s blue checkmark, indicating authenticity and an elevated status within the network. For seven weekdays (September 19 to 23 and September 26 and 27), every post and linked news article of the 9 publishers was fact-checked by professional journalists at BuzzFeed. In total, 1,627 articles were checked, 826 mainstream, 256 left-wing and 545 right-wing. The imbalance between categories results from differing publication frequencies.


The corpus comes with the following files:

README.txt            This file.
web-archives/*.warc   The web archive files that contain the HTTP messages that where sent and received during the crawl
articles/*.xml        The articles extracted from the web archive files in XML format with annotations.
schema.xsd            Schema of the article files with explanations of the used XML tags. Can be used with object binding libraries (like JAXB) to parse the XML.
overview.csv          Giving the portal, orientation, veracity, and URL for each article. The same data is also contained in the XML files.

