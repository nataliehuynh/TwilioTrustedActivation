# TwilioTrustedActivation
Twilio Trusted Activation with Verify and Lookup API. This project will allow you test Twilio Verify and Lookup API with your account.

## Prerequisite
1. [Twilio Account](https://console.twilio.com/)
2. [Twilio Serverless](https://www.twilio.com/en-us/serverless)
3. [Twilio Verify](https://www.twilio.com/verify)
## Getting Started
1. Create a [Twilio Service](https://console.twilio.com/us1/develop/functions/services)
<img width="1406" alt="Screen Shot 1" src="https://user-images.githubusercontent.com/587503/219128424-6192a1b7-c18a-49c7-8969-dfc63604f832.png">

2. Click on Add => Add Function
<img width="1406" alt="Screen Shot 2" src="https://user-images.githubusercontent.com/587503/219128847-cc8509c3-86ae-4f30-8d93-b15123c8639e.png">

3. Add lookup_type, safe_list, sent_otp, verify_otp and verify_sna to functions by copying and pasting the code from github project under functions folder, set your functions to Public (Replace Verify Services ID 'VAxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'in sent_otp, verify_otp and verify_sna file )
<img width="1406" alt="Screen Shot 3" src="https://user-images.githubusercontent.com/587503/219130401-d08973fc-6830-40f9-bc13-80beb9007fc1.png">

4. Create a new [Twilio Verify Serice](https://console.twilio.com/us1/develop/verify/services) Provide Friendly name and select: SMS, Whatsapp (will need to request for [Whatsapp Sender](https://www.twilio.com/docs/whatsapp/tutorial/requesting-access-to-whatsapp)), Voice and Enable Fraud Guard. Set your parameter preference and save
<img width="1406" alt="Screen Shot 3" src="https://user-images.githubusercontent.com/587503/219750560-2b397c88-e182-4f2a-a433-c8119ba2dff4.png">

5. Replace Verify Service SID 'VAxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'in sent_otp, verify_otp and verify_sna function

6. Click on Add => Upload File => Upload index.html file from github project and set to Public

7. Change urlSend (5 instance of it in index.html) with your unique project URL, will be "https://projectName-XXXX.twil.io"
<img width="200" alt="Screen Shot 4" src="https://user-images.githubusercontent.com/587503/219131651-78b5ed2d-7e8a-4b14-9508-c4de3883fc2f.png">

8. Click on Deploy All from image above

9. Open Browser and go to "https://projectName-XXXX.twil.io/index.html"
<img width="1406" alt="Screen Shot 4" src="https://user-images.githubusercontent.com/587503/219133969-07a03440-309a-4524-8d48-c9cb7b951888.png">

10. Project Loaded, Have Fun!
