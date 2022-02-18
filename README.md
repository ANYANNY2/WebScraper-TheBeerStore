<center>
    <img src="https://www.thebeerstore.ca/wp-content/uploads/2020/11/Covidposting_ArticleArchive.jpg" width="30%">
</center>

<h1 align="center">The Beer Store - Web Scraping Project</h1>

<h2>
    <center align="left"> <font size='4'>  Developed by: </font><font size='4' color='#33AAFBD'>An Ni Guo</font></center>
    <center align="left"> <font size='4'>  Date: </font><font size='4' color='#33AAFBD'>Jun 23, 2021</font></center>
</h2>

## 1. Check with the policies of the website before engaging in any scraping
>There are no indications of prohibiting web scraping or web crawling or data mining, etc., except for those mentioned below:
>- COPYRIGHT BELONGS TO THE BEER STORE AND BREWERS RETAIL 
>	☞ https://www.thebeerstore.ca/terms-conditions/
>	- The Beer Store and Brewers Retail are the owners of copyright of the Sites and other intellectual property related to the Sites. No portion of the Sites, including but not limited to the content, information, text, images, audio or video, may be used in any manner, or for any purpose, without The Beer Store and Brewers Retail prior written permission, except if indicated herein. Without in any way waiving any of the foregoing rights, you may download one copy of the material on the Sites for your personal, non-commercial home use only, provided you do not delete, obstruct or change any copyright, trademark or other proprietary notices. Modification, repostment or use of the material on the Sites in any other manner whatsoever and for any other purpose violates The Beer Store and Brewers Retail legal rights. 

## 2. Decisions of using BeautifulSoup or Selenium for web scraping
> `BeautifulSoup` works only with static webpage and `Selenium` works better with dynamic webpage
>>Example(s): 
>>- ☞https://www.thebeerstore.ca/beers/ contains dynamic web pages, hence we choose to use Selenium for web scraping.
>>- ☞https://www.thebeerstore.ca/locations/ contains static web pages, hence we choose to use BeautifulSoup for web scraping.
>
>Note: The combination of Beautiful Soup and Selenium will do the job of dynamic scraping. The data rendered by JavaScript links can be made available by automating the button clicks with Selenium and then can be extracted by Beautiful Soup.

