# Splunk-Project
Utilize your Splunk skills to design a powerful monitoring solution to protect Vandaly from security attacks.

MONITORING SPLUNK

As the worldwide leader of importing and exporting, Vandalay Industries has been the target of many adversaries attempting to disrupt their online business. Recently, Vandaly has been experiencing DDOS attacks against their web servers.

Not only were web servers taken offline by a DDOS attack, but upload and download speed were also significantly impacted after the outage. Your networking team provided results of a network speed run around the time of the latest DDOS attack.
Upload file into Splunk.

Create a report to determine the impact that the DDOS attack had on download and upload speed. Additionally, create an additional field to calculate the ratio of the upload speed to the download speed.

![Image](https://user-images.githubusercontent.com/98360708/185762541-914fd67f-fe2b-43b2-8f1f-8b42666291d4.png)

Step 1: Create a report to determine the impact that the DDOS attack had on download and upload speed. Additionally, create an additional field to calculate the ratio of the upload speed to the download speed.

We can see in or chart and our stats when the attacked started because of the sudden decline of Upload megabits and when our systems recover.
The attack started at 2/23/20 11:30PM
Our systems started recovering around 8:30PM and fully recovered at 11:30PM
Our systems were down for about 8-10.

![Image](https://user-images.githubusercontent.com/98360708/185762640-1564fa91-21c5-46ef-8028-56c7b255e37c.png)


NESSUS SCAN

Scenario: Due to the frequency of attacks, your manager needs to be sure that sensitive customer data on their servers is not vulnerable. Since Vandalay uses Nessus vulnerability scanners, you have pulled the last 24 hours of scans to see if there are any critical vulnerabilities.

Step 2: Create a report determining how many critical vulnerabilities exist on the customer data server. Then, build an alert to notify your team if a critical vulnerability reappears on this server.

![image](https://user-images.githubusercontent.com/98360708/185764177-6f329912-e692-4c0e-b418-3af2312d4acb.png)

This image represents A report of the database IP Address 10.11.36.23 associated critical events

![image](https://user-images.githubusercontent.com/98360708/185764184-5a3b9ca3-ea1d-42e3-9902-2fbb9fc67f4f.png)

Create alert to send soc@vandalay.com for critical alerts for the database

![image](https://user-images.githubusercontent.com/98360708/185764195-f0638012-0ac3-4a61-80f4-9afc6736f57f.png)


DRAWING BASELINE

Scenario: A Vandaly server is also experiencing brute force attacks into their administrator account. Management would like you to set up monitoring to notify the SOC team if a brute force attack occurs again.

Step 3: Analyze administrator logs that document a brute force attack. Then, create a baseline of the ordinary amount of administrator bad logins and determine a threshold to indicate if a brute force attack is occurring.

Upload Admin logs.

![image](https://user-images.githubusercontent.com/98360708/185764219-74aab28d-ff16-4250-a784-e755d426f6fc.png)

Examine log in’s to determine if there is a brute force attack happening.

The attack happened on 02/21/22 at 9AM – 02/21/22 at 1PM

![image](https://user-images.githubusercontent.com/98360708/185764226-c5656b63-7967-483d-9bec-a34b202e0555.png)

Create a baseline alert to notify your team whenever there is unusual number of attempts

![image](https://user-images.githubusercontent.com/98360708/185764229-3bed329c-e946-430e-b323-ee8f0507d623.png)
