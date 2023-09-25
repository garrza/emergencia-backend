# HACKMTY 2023 - EmergencIA
## Inteligent operator for the emergency sector

App backend:

Recived calls with twilio, used Google Cloud Speech for transcribing calls.

Created an API that sent the transcription into the main backend of the app.
Tokenized and classified the caller, its situation, the location of the incident, the emotions found during the call, 
and an overall assesment of the appropiate service the victim may need.

Main backend sent a parsed JSON file into our app database, ensuring a stable, measurable, and secure way of answering calls to 911 that would've been left unanswered.
