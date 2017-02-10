# regression-testcases-joor

Setup: 
FF 51.0.1 (64-bit) with Add-Ons

Selenium IDE 2.9.1.1-signed
https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/

Selenium IDE: Flow Control 1.0.4.1-signed.1-signed
https://addons.mozilla.org/en-US/firefox/addon/flow-control/

How To Run: 

1. Start FF. 
2. Open Selenium IDE  Tools->Selenium IDE.
3. Load Test Suite "SendMessage_TestSuite". File -> Open Test Suite ...
4. Verify that test cases has been loaded in the right order (e.g. test cases with #1 should run first then test case #2 etc.) 
5. In the Selenium IDE Window adjust default speed handle in the middle between fast and slow
6. Verify that user is logout from the https://staging.joordev.com/. 
6. Right Click on the first test case and select "Play test suite from here"
