# Burp Loader
	**Prequisite -> Download .jar file for Burp Suite Pro from -->  **https://portswigger.net/burp/releases/download?product=pro&version=2021.2.1&type=Jar****
	**Download Burp Loader files. Then Follow Below Steps for Activation**
-----------------------------------------------------------------
	**1. Place Both files in same Directory**
		If Windows	: C\User\abcd\Downloads\BurpSuitePro\
		If Linux 	: /home/<user>/Downloads/BurpSuitePro
	**2. Run This Command. Replace "___" with Version**
		1. If Windows:
			"C:\Program Files\Java\jdk-13.0.2\bin\java.exe" --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:BurpSuiteLoader_v2020.11.3.jar -noverify -jar burpsuite_pro_v202_____.jar
		2. If Linux:
			/usr/lib/jvm/java-11-openjdk-amd64/bin/java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:BurpSuiteLoader_v2020.11.3.jar -noverify -jar burpsuite_pro_v202_____.jar
	**3. Use old burploader**
		java -jar burploader-old.jar
	**4. Activate Burp Suite Pro Manually with Burploader-old.jar**
		1. Modify License String like "license to Siddharth"
		2. Copy License key from Burploader-old.jar and paste in Burp Suite Pro.
		3. Select Manual Activation Option on your bottom Right in Burp Suite Pro.
		4. Copy License Request from BurpSuite_Pro and paste in Burploader-old.jar
		5. Copy license response from Burploader-old and paste in BurpSuite_Pro, and next and Done
