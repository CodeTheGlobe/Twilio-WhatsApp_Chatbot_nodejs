# Twilio-WhatsApp_Chatbot_nodejs
A whatsapp chatbot using twilio and nodejs

# Setup step 1
First head to twilio.com to create your sandbox account.\n
Copy the accountSid ANDD authToken fffrom the console \n
Replace accountSid ANDD authToken i the routes/messaging.route.js file

# Setup step 2 -Run project locally
npm start
Download ngrok here https://ngrok.com/download and follow thhe instructions to start a tunnel using your localhost link. copy the live url
or 

# Setup step 2 -Host project online 
Head to any hosting platform that allows node application to host project and copy the live url. example www.evennode.com

# Setup step 3
Head back to your console, on your sandbox configuration settings set the URL for when a message comes in to <your live link>/messaging/reply

# Join sandbox
Join your sandbox by sending a message from your whatsapp to the twilio number

# Test phrase to test with
send 'hi', send '1', send '2', send '3', send '4', or any random phrase from your whatsapp to test


