# fingerprintsensor
- This repository contains code for a fingerprint sensor so that it sense a fingerprint.

- The user is asked to place the finger on the sensor , if the fingerprint matches , the app then opens up.

- The code for the same to detect the fingerprint is availaible in 
    1. onAuthenticationFailed() - exectued if failed authentication.
    2. onAuthenticationSucceeded(FingerprintManager.AuthenticationResult result) - executed if successful authentication.
    3. onAuthenticationError(int errMsgId, CharSequence errString) - Displays error occurred during authentication.
    
    -These functions implemented in fingerprintsensor/src/main/java/com/google/www/fingerprintsensor/FingerprintHandler.java
    
- If the fingerprint gets matched , the Main2Activity.xml file in the same location gets executed , ans the UI is shown.
- The UI for the same is designed as well , with a navigation bar on top as well.
____________________________________________________________________________________________________________________________
