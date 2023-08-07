# Chat-App
In this chat application, when you open it first on your browser, there is shown a signup form where you have to signup with your details like name, email, password, and image. Email and image field is fully validated which means you’ve to enter a valid email and an image file only. Once you signed up successfully, you’ll be redirected to the user’s page where you can see your full name, image, status, and logout button to the top, and users, like you, appear on the bottom if someone has signed up.

On this page, you can see their image, name, status, and the last message if they sent to you. You have to click on the particular user or you can also search any existing user with their name then you’ll be redirected to the chat page and there you can see the image, name, status of that user who is going to chat.

Once you send a message to another user then immediately that message appears in your chat box and another user chatbox too which you’ve sent the message. On the message receiver chatbox, this user received the message with the sender image. Remember chatbox will be automatically scrolled to the bottom once the chatbox starts scrolling. You can log out from the chat application at any time and once you log out, immediately all other users will know that you’ve been log out or offline.

Once you log out, you can again login and with your email and password that you used when signing up for the form. If you entered the correct credentials then you’ll be redirected to the user’s page and all other users will immediately know that you’ve logged on and now active.

# To see how it works:
Download the code and once it is downloaded, just extract the zip file then you’ll see the folder name with ChatApp. Copy this folder and paste it inside htdocs folder of your XAMPP then start your apache and MySQL from the XAMMP control panel.


After completing these steps, go to your browser and open this URL localhost/phpmyadmin then create a new database name with a chatapp. After creating the database, there you can see an import option, just click on that and import the SQL file which is in the ChatApp folder. Everything is done now, just open this URL localhost/chatapp that’s it. Your chat application is ready to chat.
