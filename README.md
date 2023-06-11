[![DOI](https://zenodo.org/badge/438872935.svg)](https://zenodo.org/badge/latestdoi/438872935).  

Repository for the project analogizing publications citing or using Atlas of Living Australia.

**Title:** Impacts and opportunities of geographically focused data integration –  a case study of the Atlas of Living Australia.  

**Authors:**   

Malgorzata Lagisz – Evolution & Ecology Research Centre and School of Biological, Earth and Environmental Science, University of New South Wales, Sydney, Australia;  m.lagisz@unsw.edu.au.  

Martin Westgate – Atlas of Living Australia, National Collections & Marine Infrastructure, CSIRO, Canberra,  Australia; martin.westgate@csiro.au.  

Dax Kellie – Atlas of Living Australia, National Collections & Marine Infrastructure, CSIRO, Canberra,  Australia; dax.kellie@csiro.au.  

Shinichi Nakagawa – Evolution & Ecology Research Centre and School of Biological, Earth and Environmental Science, University of New South Wales, Sydney, Australia; Theoretical Sciences Visiting Program, Okinawa Institute of Science and Technology Graduate 
University, Onna, Japan; s.nakagawa@unsw.edu.au.  

The main data file used for analyses is "2023-03-30_ALA_cited.csv".   
This file contains bibliographic records exported from Zotero (for field descriptions see Zotero documentation: <https://www.zotero.org/support/kb/item_types_and_fields>).  

## ALA publication tracking methods:   
The Atlas of living Australia (ALA) has tracked articles that use, cite, or mention the ALA since 28 February 2018. The ALA stores these articles in a Zotero library along with article metadata. Articles range in publication date from 2007-2023.  

To track relevant articles, the ALA has set up email notifications from literature searching databases. The ALA receives notifications from Google Scholar, ProQuest, Scopus, Isentia and Web of Science (Core Collection and Data Cite Index). The ALA also receives notifications about datasets and figures from CSIRO Mediaportal, Zenodo and Figshare. Email notifications are sent to a specific ALA reference email address.  

The ALA tracks when their name, website or DOI are used in an article. The ALA is notified when the following key words are in an article:  
• Atlas of Living Australia. 
• Atlas Living Australia. 
• ala.org.au. 
• 10.26197. 
• grid.506668.b. 
• https://ror.org/018n2ja79 (added 25/01/2022). 
Data downloads made using the ALA website or the R package {galah} are minted a DOI beginning with 10.25197, and the suggested citation for the ALA is using grid.506668.b (before 25/01/2022) or https://ror.org/018n2ja79 (after 25/01/2022).
Articles are added to the Zotero library weekly. The publication tracking workflow was first established by Corinna Paeper and Ely Wallis in 2018. Publication tracking is currently maintained by Olivia Torresan, Dax Kellie, and Martin Westgate.

  
## Manual record tagging
Field "Manual.Tags" contains tags manually assigned in Zotero to each article to indicate the ALA’s relevance within the article.   

Tag description (main numeric tags):   
“1 – ALA used” - Makes use of data in a quantitative analysis (e.g., ecological niche modelling, species distribution modelling). This can include use as supplemental data in a main or supplementary analysis    
“2 – ALA cited” - Cites a quantitative or qualitative fact derived from data (e.g. a statement or map of a given species’ distribution)   
“3 – ALA discussed” - Discusses ALA as an infrastructure or the use of data   
“4 – ALA acknowledged” - Acknowledges the ALA but doesn’t use or cite data (e.g., statements like “infrastructures like the ALA”)   
“5 – ALA mentioned” - Unspecifically mentions ALA or the ALA portal  
“6 – ALA published” - Describes or talks about data published to the ALA.   

Additional tags are also assigned to “1 – ALA Used” articles if it can be discerned which type of ALA data or ALA tools were used to retrieve the data (e.g., Australian Virtual Herbarium, Spatial Portal, Species occurrence records). Whether these tags are assigned varies by article, and there is limited documentation of how consistently they were assigned since tracking started in 2018.    

Other data files are intermediate files - either processed existing data files or filec created by fetching and saving information from online databases.  
