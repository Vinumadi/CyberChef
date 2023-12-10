# CyberChef
Cyber Chef is an indispensable tool in the world of cybersecurity, providing data analysts and cyber professionals with the means to efficiently manipulate and transform data. With its vast array of features and capabilities, Cyber Chef empowers users to streamline their data analysis processes and enhance their threat hunting endeavours.

Basic Use cases on Cyber Chef

From Hexadecimal string to the encoded data:

Step1: Copy the Hexadecimal string into the “input” Tab.
Step2: Drag and drop “From Hex” to “Recipe” Tab.
Step3: Click on “Bake” or enable the option of “Auto Bake” found in Recipe Tab to get results.

Example:
43 6f 6e 67 72 61 74 75 6c 61 74 69 6f 6e 73 2c 20 79 6f 75 20 68 61 76 65 20 63 6f 6d 70 6c 65 74 65 64 20 43 79 62 65 72 43 68 65 66 20 63 68 61 6c 6c 65 6e 67 65 20 23 31 21 0a 0a 54 68 69 73 20 63 68 61 6c 6c 65 6e 67 65 20 65 78 70 6c 6f 72 65 64 20 68 65 78 61 64 65 63 69 6d 61 6c 20 65 6e 63 6f 64 69 6e 67 2e 20 54 6f 20 6c 65 61 72 6e 20 6d 6f 72 65 2c 20 76 69 73 69 74 20 77 69 6b 69 70 65 64 69 61 2e 6f 72 67 2f 77 69 6b 69 2f 48 65 78 61 64 65 63 69 6d 61 6c 2e 0a 0a 54 68 65 20 63 6f 64 65 20 66 6f 72 20 74 68 69 73 20 63 68 61 6c 6c 65 6e 67 65 20 69 73 20 3 20 28 6b 65 65 70 20 74 68 69 73 20 70 72 69 76 61 74 65 29 2e 0a 0a 54 68 65 20 6e 65 78 74 20 63 68 61 6c 6c 65 6e 67 65 20 63 61 6e 20 62 65 20 66 6f 75 6e 64 20 61 74 20 68 74 74 70 73 3a 2f 2f 70 61 73 74 65 62 69 6e 2e 63 6f 6d 2f 47 53 6e 54 41 6d 6b 56 2e

Result: The data is encoded in the Hexadecimal string and gives the Encoded results.

Base 64 decode:  

Step1: Copy the below string into the “input” Tab.
Step2: Drag and drop “From Base64” to “Recipe” Tab.
Step3: Click on “Bake” or enable the option of “Auto Bake” found in Recipe Tab to get results.

Example:
U28gbG9uZyBhbmQgdGhhbmtzIGZvciBhbGwgdGhlIGZpc2gu

Result: The data is encoded in the Base 64 string and gives the Encoded results.

Email Analysis:

Email Analysis made easier with the Cyber chef, By doing operations like “Extract IP Address”, “Extract Domains” and “Extract email addresses”
Step1: Copy the original message/ header information of the mail into the “input” Tab.
Step2: Enable the option of “Auto Bake” found in Recipe Tab.
Step3: Drag and drop “Extract IP Address” to “Recipe” Tab to get the “IP Address”.
Step4: Drag and drop “Extract Domains” to “Recipe” Tab to get the “Domains”.
Step5: Drag and drop “Extract email addresses” to “Recipe” Tab to get the “Email address”.
Note: Delete/Clear the recipe tab after following the Step3, Step4 and Step5

Example:

Results:
The IP, Domains and Email Addresses are easily extracted from the original message.

IP Header Analysis: 
Scenario: Say Analyst is Analyzing the Packets in Wireshark and want to analyze the IPv4 header, the cyber chef helps in Analyzing the details of an IPv4.

Step1: Copy the below IP header string into the “input” Tab.
Step2: Drag and drop “Parse IPv4 header” to “Recipe” Tab.
Step3: Click on “Bake” or enable the option of “Auto Bake” found in Recipe Tab to get results.

Example:
 4500003c1c46 40004006 0000c0a8 0001c0a8 0002
 
Results:
The “Parse IPv4 header” operation will give the complete details of the IP address.

URL Decode: 
Step1: Copy the below script from ‘UAB’ to ‘cCI=’ into the “input” Tab.
Step2: Drag and drop “From Base64”, ”Extract URLs”, ”Defang URL” to “Recipe” Tab.
Step3: Click on “Bake” or enable the option of “Auto Bake” found in Recipe Tab to get results.

Example:
powershell.exe -enc UABvAHcAZQBYAFMAaABLAGWAbAAgACQAZQBuAGMAcgB2ADoAUwB0AGUAbQAuAE4AZQBsAGIAUABhAGwAaQBjAHIAIAAtAG4AbwBwAHIAbwBmAGkAVwBpAGQAZQByACAAIgBodHRwczovL2JpbmcuY29tL2luZGV4LnBocCI=

Results: The above string will give the details of the URL encoded in the script.

QR Decode:
Create or decode any QR code with the cyber chef, the below provided QR code will give the data encoded in it.
Step1: Load the QR code by downloading the image into the system to the“input” Tab.
Step2: Drag and drop “Parse QR code“ to  the “Recipe” Tab.
Step3: Click on “Bake” or enable the option of “Auto Bake” found in Recipe Tab to get results.

Example:
QR Code

Results:
The QR code gives the decoded data in it.

Summary: 
In these above use cases, we illuminated the strategies employed by attackers to conceal their motivations. We also explored how defenders can leverage existing tools at their disposal to thwart malicious activities.

Happy Baking!










