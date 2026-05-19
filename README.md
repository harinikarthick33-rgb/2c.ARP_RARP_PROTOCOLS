# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP

client.py

<img width="500" height="592" alt="WhatsApp Image 2026-05-19 at 8 25 52 AM (1)" src="https://github.com/user-attachments/assets/83e62c62-97cd-4418-a701-7656a7f67f7e" />


server.py

<img width="419" height="253" alt="WhatsApp Image 2026-05-19 at 8 25 52 AM (2)" src="https://github.com/user-attachments/assets/363d2889-48fd-463e-beb2-dd265331f74a" />

## OUPUT - ARP

client.py

<img width="569" height="36" alt="WhatsApp Image 2026-05-19 at 8 25 52 AM (3)" src="https://github.com/user-attachments/assets/37889117-5729-479d-a965-5940ea3ec2d7" />


server.py

<img width="588" height="111" alt="WhatsApp Image 2026-05-19 at 8 25 52 AM (4)" src="https://github.com/user-attachments/assets/5b26370a-bbcb-4f35-bbe3-d3e44792b959" />

## PROGRAM - RARP

client.py

<img width="478" height="562" alt="WhatsApp Image 2026-05-19 at 8 25 52 AM" src="https://github.com/user-attachments/assets/d9713584-5907-4e98-8261-e42982284417" />


server.py

<img width="528" height="241" alt="WhatsApp Image 2026-05-19 at 8 25 52 AM (5)" src="https://github.com/user-attachments/assets/56a0c911-9462-49ea-9dcb-113e635e35f0" />

## OUPUT -RARP

client.py

<img width="375" height="58" alt="WhatsApp Image 2026-05-19 at 8 25 52 AM (6)" src="https://github.com/user-attachments/assets/1b227850-b001-4199-acec-ff1e2e3f4b2d" />


server.py

<img width="604" height="158" alt="WhatsApp Image 2026-05-19 at 8 25 52 AM (7)" src="https://github.com/user-attachments/assets/be0c7f7b-d48e-4a22-ab02-26fa1653088e" />

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
