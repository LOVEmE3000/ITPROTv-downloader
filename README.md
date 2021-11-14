# ITPROTv-downloader

![68747470733a2f2f692e696d6775722e636f6d2f695732696c4f442e706e67](https://user-images.githubusercontent.com/89593059/141672884-43fac4e1-f115-47dd-9fc2-5f6e4604dca5.png)

Get cookies.txt - https://bit.ly/GoogleChrome-GetCookiesTxt

ChromeDriver - http://chromedriver.chromium.org/ 
Check the virsion of your chrome

Now,
In windows:- put chromedriver in C drive
For example:- C:/ChromeDriver/chromedriver.exe

In Linux/Ubuntu:- put chromedrive in /usr/bin/
For example:- /usr/bin/chromedriver


Python - https://www.python.org/downloads/

Step1: clone or download the ITPROTV-DL-MASTER

step2:Now  go to download folder  and extract or unzip the ITPROTV-DL-master file, then open command prompt [cmd]

step3: Run the below command on command prompt [cmd]. It will check all the dependencies and requirements.

       pip install -r requirements.txt
       
step4: Login to ITProTV and visit the course that you want to download.

step5: Now click on the cookie extension and click export.

![68747470733a2f2f692e696d6775722e636f6d2f36516b563952432e706e67](https://user-images.githubusercontent.com/89593059/141672932-d493d64e-1ddb-4fec-8792-4c5d2888d0be.png)

step6: Rename the downloaded itpro.tv_cookies.txt file to cookies.txt and copy it to main of the cloned repo (ITPROTV-DL-master).

step7:removing or commenting out all lines in cookies.txt that do not start with .itpro.tv or app.itpro.tv
      [Comment it by using '#' ] 
      
step8: At last run the below command in cmd

    python driver.py [paste_course_link_here]      
