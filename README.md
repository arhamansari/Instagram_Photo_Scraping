# Instagram_Photo_Scraping
Scraping Instagram using Python libraries like Selenium,BeautifulSoup,Requests,Webdriver.

In this project I have scrapped photos from instagram.

Steps :

1)Request page from .get method or Webdriver method.

2)Once the page is received go to input which contains username and password. Use .send_keys() method to send Username and Password

2) After entering username and password Now we have to click Login Button find link for login button by .find_element_by_xpath(axis//node/predicate) method .Click the login button using .click() or .submit() button in Selenium.

3)Once we are login cancel all the pop ups and search for the profile you have target.Profile should be visible Publicly.

4)Use OS library to create folder and Use shutil to download and copy image and add extension of '.jpg' file


<img src = "https://github.com/arhamansari/Instagram_Photo_Scraping/blob/master/Insta_scraping_done.gif">Glimpse</img>
