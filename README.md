# Deploy_React_App_to_AWS_EC2-

## 1. Create account in AWS and validate your card details for future payments.

## 2. Login to AWS, and in home page select your `region` and select `EC2` from `All Services` (Top right corner)
![image](https://user-images.githubusercontent.com/26189907/85496323-b9fbea00-b5f9-11ea-8edc-c0d5c1d2b553.png)

## 3. Once `EC2` page is opened, click on `Launch Instance` Button.
![image](https://user-images.githubusercontent.com/26189907/85496717-6938c100-b5fa-11ea-8d3e-cfb9abf8bb3a.png)

## 4. Now you will see 7 steps in top (currently you are in step #1), Here in step 1 select `Microsoft Windows Server 2019 Base` (this is available for free tire.)
![image](https://user-images.githubusercontent.com/26189907/85497331-5e326080-b5fb-11ea-8ebb-d5610426604a.png)

## 5. Now you will move to step 2, here select the free tire instance and click on `Next : Configure instance details` button at bottom of page.
![image](https://user-images.githubusercontent.com/26189907/85497837-3bed1280-b5fc-11ea-9614-145c09c5a9b2.png)

## 6. Here in Step #3, dont make any changes keep default settings. And click on `Next : Add storage` buttom at bottom.
![image](https://user-images.githubusercontent.com/26189907/85497950-73f45580-b5fc-11ea-8515-adaad0090a87.png)

## 7. Here in Step #4, dont make any changes keep default storage size (30 GB). And click on `Next : Add Tags` buttom at bottom.
![image](https://user-images.githubusercontent.com/26189907/85498210-e36a4500-b5fc-11ea-9cee-bf2e4621c413.png)

## 8. Here in Step #5, dont make any changes keep default settings. And click on `Next : COnfigure security group` buttom at bottom.
![image](https://user-images.githubusercontent.com/26189907/85498375-317f4880-b5fd-11ea-8354-9c486d1b91bb.png)

## 9. This is important step, Here in St2p #6 you have to open some of the ports of your VM so that it can be accessed from outside, after adding Rules click on `Review and Launch` buttom at bottom.
![image](https://user-images.githubusercontent.com/26189907/85498787-fe898480-b5fd-11ea-9c46-9c37bfbcd802.png)

## 10. This is final step, Here in Step #7 please review all your settings and click on `Launch` button at the bottom.
![image](https://user-images.githubusercontent.com/26189907/85498976-5aeca400-b5fe-11ea-9125-c362d22656ab.png)

## 11. Once you click on Launch button, you will see a LightBox Asking to generete Public/Private key to access your VM.
### a.) Create and download `.pem` file, it will help you in connecting to your VM
![image](https://user-images.githubusercontent.com/26189907/85501995-16640700-b604-11ea-8f9d-5c28544372b6.png)
### b.) Once you click on `Launch` button you will see below screen, saying that your instance has been launched. You can click on `View Instance` button to view it.
![image](https://user-images.githubusercontent.com/26189907/85502571-2fb98300-b605-11ea-9ac2-cb17963b1e6b.png)

## 12. Your Launched instance will look like below, You can click on `connect` button to connect it.
![image](https://user-images.githubusercontent.com/26189907/85502746-95a60a80-b605-11ea-9703-c708125b26f1.png)

## 13. After clicking on `connect` button, you will see a light box with 2 options. 
![image](https://user-images.githubusercontent.com/26189907/85503185-a905a580-b606-11ea-88d5-a4c0b4f34579.png)

## 14. Fron this lightbox first click on `Get Password` button then upload your `.pem` file which you have downloaded in Step #11. (Note down the password)
![image](https://user-images.githubusercontent.com/26189907/85503496-6bede300-b607-11ea-8e30-03b7afa4530b.png)

## 15. Once you get the password, close the lightbox and again click on `connect` button and this time click on `Download Remote Desktop File` button and run the downloaded file.
![image](https://user-images.githubusercontent.com/26189907/85503629-b8392300-b607-11ea-9acf-66ff26b327f8.png)






