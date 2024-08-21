# Wireshark Home Lab

## Objective


The objective of this home lab is to demonstrate proficiency in Wireshark by successfully completing the designated tasks within the TryHackMe environment.

### Skills Learned


- Leveraged Wireshark's endpoint functionality to refine packet searches and identify specific data.
- Utilized HTTP and IPV4 Statistics to gather information that was needed to complete the objective
- Employed HTTP and IPv4 statistics to extract necessary information for objective completion.
- Applied IP filters to streamline packet analysis.
- Used comparison operators to isolate packets critical to the objective.
- Implemented TCP filters to identify packets using specific ports.
- Combined TCP and HTTP protocol filters in a single line to obtain targeted information and achieve the objective.

### Tools Used

- Wireshark

## Objective 1
1. Launched the Wireshark Packet Operations module

2. Tryhackme Objective 1: Investigate the resolved addresses. What is the IP address of the hostname starts with "bbc"? -

3. I opened the Excercise pcap and selected statistics > then selected resolved addresses. This is what appeared below.

   ![image](https://github.com/user-attachments/assets/fa5e494e-c161-4b52-af4c-f82ea2f59b79)

4. Then I searched "bbc" in the search bar and the IP address appeared.

   ![image](https://github.com/user-attachments/assets/bc0f6f3e-067f-4d33-b733-f1cd778739fc)

## Objective 2

1. Tryhackme Objective 2: What is the number of IPv4 conversations?

2. Navigated to statistics and then selected conversations

3. Below is a screenshot with the answer that reflects 435.

![image](https://github.com/user-attachments/assets/61b15b22-a399-48d8-aa0d-795ec9cdc1b8)

## Objective 3

1. Tryhackme Objective 3: How many bytes (k) were transferred from the "Micro-St" MAC address?

2. Navigated to statistics and selected endpoints.

3. Then I checked the name resolution box and was able to find Micro-St and that 7474 bytes were transferred from it.

![image](https://github.com/user-attachments/assets/976a1c92-22a9-4164-b1f8-10f85df57f00)

## Objective 4

1. Tryhackme Objective 4: What is the number of IP addresses linked with "Kansas City"?

2. Selected statistics and then endpoints.

3. Selected the name resolution box.

4. Then I catagorized the endpoints by city. The end result was 4.

![image](https://github.com/user-attachments/assets/e8548c56-300a-4d8e-805c-3f3eb3c89b96)

## Objective 5

1. Tryhackme Objective 5: Which IP address is linked with "Blicnet" AS Organisation?

2. Utilizing endpoint within Wireshark I was able to find the organization under the IPV4 tab and unchecked the name resolution box and it displayed the IP address.

![image](https://github.com/user-attachments/assets/c5d1f748-676a-41f5-b2a7-e0a4d2965c80)

![image](https://github.com/user-attachments/assets/ec1bc38b-c198-4991-932a-8aeaa6743cbf)

## Objective 6

1. Tryhackme Objective 6: What is the most used IPv4 destination address?

2. Navigated to statistics > IPV4 statistics > Then selected destination and ports.

3. Then I catigorized the destinations by count and got the result.

![image](https://github.com/user-attachments/assets/11ca2955-0cef-486e-b815-e4e8190a2744)

## Objective 7

1. Tryhackme Objective 7: What is the max service request-response time of the DNS packets?

2. Navigated to statistics and selected DNS.

3. Found the max service request-response time and it is shown in the screenshot below.

![image](https://github.com/user-attachments/assets/839959a3-d3b7-409c-bcaa-ad77469df946)

## Objective 8

1. Tryhackme Objective 8: What is the number of HTTP Requests accomplished by "rad[.]msn[.]com?

2. Navigated to statistics > HTTP > and selected requests.

![image](https://github.com/user-attachments/assets/b64899de-a3a4-426e-b95a-3e0d70fc52d2)

![image](https://github.com/user-attachments/assets/2ce775f7-7461-4bc5-a224-4e2f6eca6efc)

## Objective 8

1. Tryhackme Objective 8: What is the number of IP packets?

2. Typed in ip and pressed enter. At the bottom of the page it displays the total amount of packets.


![image](https://github.com/user-attachments/assets/1cac502b-cf37-4c1f-916d-ca285ca6157d)

## Objective 9

1. Tryhackme Objective 9: What is the number of packets with a "TTL value less than 10"?

2. Typed in the the comparison operator and got the correct result of 66.

![image](https://github.com/user-attachments/assets/696b62fb-5ed9-43e6-ae04-da418e7ea58a)

## Objective 10

1. Tryhackme Objective 10: What is the number of packets which uses "TCP port 4444"?

2. Utilized the proper tcp command to prompt Wireshark to reveal the amount of packets that use TCP 4444.

![image](https://github.com/user-attachments/assets/4821b288-cc7b-40bf-8d90-89cddcdf4c84)

## Objective 11

1. Tryhackme Objective 11: What is the number of "HTTP GET" requests sent to port "80"?

2. Utilized 2 different queries, the first portion was to reveal all the HTTP GET requests. After and the second portion showed all of the TCP packets sent to port 80.

![image](https://github.com/user-attachments/assets/1472d7af-da9b-4641-a660-c224cdbf19d6)




# Conclusion

This project is just the beginning of exploring Wireshark's full capabilities. It was designed to showcase a solid understanding and proficiency in using the tool. I gained valuable insights and knowledge while working through the modules.












   


   



