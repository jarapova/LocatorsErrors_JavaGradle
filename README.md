# LocatorsErrors_JavaGradle
https://docs.google.com/spreadsheets/d/1x2mwodQNhiS3vL5xeYL1rC5IAwLQVHuj1Gb53y89Buc/edit#gid=0



# TA locator is invalid.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Java-Gradle.git""
2. Run ""gradle test --tests InitialLocatorWithInvalidTAName --info"""	
* Expected error: TrueAutomation locator ta-Name contains unsupported characters. Please make sure to use only letters, numbers, colon and underscore symbols in locator names. (WARNING: The server did not provide any stacktrace information)	"
* Actual error: TrueAutomation locator ta-Name contains unsupported characters. Please make sure to use only letters, numbers, colon and underscore symbols in locator names. (WARNING: The server did not provide any stacktrace information)
Command duration or timeout: 0 milliseconds
For documentation on this error, please visit: http://seleniumhq.org/exceptions/no_such_element.html
Build info: version: '3.11.0', revision: 'e59cfb3', time: '2018-03-11T20:26:55.152Z'
System info: host: 'MacBook-Pro-Mac.local', ip: 'fe80:0:0:0:1ced:8761:61e8:4634%en0', os.name: 'Mac OS X', os.arch: 'x86_64', os.version: '10.14.5', java.version: '12'
Driver info: io.trueautomation.client.driver.TrueAutomationDriver
Capabilities {acceptInsecureCerts: false, acceptSslCerts: false, applicationCacheEnabled: false, browserConnectionEnabled: false, browserName: chrome, chrome: {chromedriverVersion: 75.0.3770.8 (681f24ea911fe7..., userDataDir: /var/folders/sv/7zszrx0952v...}, cssSelectorsEnabled: true, databaseEnabled: false, goog:chromeOptions: {debuggerAddress: localhost:54294}, handlesAlerts: true, hasTouchScreen: false, javascriptEnabled: true, locationContextEnabled: true, mobileEmulationEnabled: false, nativeEvents: true, networkConnectionEnabled: false, pageLoadStrategy: normal, platform: MAC, platformName: MAC, proxy: Proxy(), rotatable: false, setWindowRect: true, strictFileInteractability: false, takesHeapSnapshot: true, takesScreenshot: true, timeouts: {implicit: 0, pageLoad: 300000, script: 30000}, unexpectedAlertBehaviour: ignore, unhandledPromptBehavior: ignore, version: 75.0.3770.80, webStorageEnabled: true}
Session ID: 01510ad0e5672034c768a3a0617c1416
*** Element info: {Using=xpath, value=//span[@class='RveJvd snByac']__ta__ta-Name__ta__}"
# Element was not found on the page by initial locator.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Java-Gradle.git""
2. Run ""gradle test --tests InitialLocatorNotExistOnUsePage --info"""	
* Expected error: NOT_FOUND	
* Actual error: NOT_FOUND (WARNING: The server did not provide any stacktrace information)
# Initial locator is invalid.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Java-Gradle.git""
2. Run ""gradle test --tests TALocatorWithInvalidInitialLocator --info"""	"
* Expected error:
1) Expected error: Unable to locate element { using: ""class name"", selector: ""//RveJvd snByac"" }
2) Expected error: Unable to locate element { using: ""css selector"", selector: "".RveJvd snByac"" }
3) Expected error: Unable to locate element { using: ""id"", selector: ""//identifierId"" }
4) Expected error: Unable to locate element { using: ""link text"", selector: ""//Справка"" }
5) Expected error: Unable to locate element { using: ""name"", selector: ""//identifier"" }
6) Expected error: Unable to locate element { using: ""partial link text"", selector: ""//Справка"" }
7) Expected error: Unable to locate element { using: ""xpath"", selector: ""span[@class='RveJvd snByac']"" }"	"
* Actual error:
1) Actual error: Unable to locate element { using: ""class name"", selector: ""//RveJvd snByac"" } (WARNING: The server did not provide any stacktrace information)
2) Actual error: Unable to locate element { using: ""css selector"", selector: "".RveJvd snByac"" } (WARNING: The server did not provide any stacktrace information)
3) Actual error: Unable to locate element { using: ""id"", selector: ""//identifierId"" } (WARNING: The server did not provide any stacktrace information)
4) Actual error: Unable to locate element { using: ""link text"", selector: ""//Справка"" } (WARNING: The server did not provide any stacktrace information)
5) Actual error: Unable to locate element { using: ""name"", selector: ""//identifier"" } (WARNING: The server did not provide any stacktrace information)
6) Actual error: Unable to locate element { using: ""partial link text"", selector: ""//Справка"" } (WARNING: The server did not provide any stacktrace information)
7) Actual error: Unable to locate element { using: ""xpath"", selector: ""span[@class='RveJvd snByac']"" } (WARNING: The server did not provide any stacktrace information)"
# Element was not found on the page by TA locator.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Java-Gradle.git""
2. Run ""gradle test --tests SmartLocatorInDatabase --info"""	
* Expected error: NOT_FOUND	
* Actual error: NOT_FOUND (WARNING: The server did not provide any stacktrace information)
# TA locator was not found in database.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Java-Gradle.git""
2. Run ""gradle test --tests SmartLocatorNotInDatabase --info"""	
* Expected error: NOT_FOUND	
* Actual error: NOT_FOUND (WARNING: The server did not provide any stacktrace information)
