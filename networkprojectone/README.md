The small office network that I built is a simple one, requiring two subnets, one for Accounting and one for Delivery.


The IP for these need to start with 192.168.40.0

With the two subnets, I used the basic subnet formula of 2^n = n, while n = the no. of subnets

Subnets landed on 255.255.255.128

I was tasked to input static IP Ranges for each department. Each department needs 2 or more Computers and at least 1 printer.

So department Accounts I set the ranges from 192.168.40.1-192.168.40.126 with the Network ID being 192.168.40.0, and the broadcast ID being 192.168.40.127 respectively.

In department Delivery, I set the ranges from 192.168.40.129-192.168.40.254 with the Network ID being 192.168.40.128 and the Broadcast ID being 192.168.40.255 respectively



![Screenshot 2024-07-27 at 11 29 09 PM](https://github.com/user-attachments/assets/4104fd49-d044-4ed3-b3ba-5b364d271d08)
![Screenshot 2024-07-27 at 11 42 42 PM](https://github.com/user-attachments/assets/6f9515e0-097d-4f61-bb72-0e67c95174f1)
![Screenshot 2024-07-27 at 11 44 02 PM](https://github.com/user-attachments/assets/d26211c3-0208-4107-9ef3-448823e2b584)
![Screenshot 2024-07-27 at 11 45 58 PM](https://github.com/user-attachments/assets/cc98a6db-3a61-4a4b-b3c2-faca82ca6c78)
