# Task5

Lets start this task:
In this task you see about packet capturing and filtering using wireshark 

Sorry first because this repo is for chill guys :)

Let's understand some protocols:
Defination in my way :-

TCP → Bhai yeh road ka traffic police hai, sab packets line mein aur safely destination tak leke jaata hai.

HTTP → Browser aur server ka gossip chat — "bhai mujhe page de, main tujhe response deta hu".

DNS → Internet ka contact list — naam (google.com) ko number (IP address) mein convert karta hai.

For Foreigners:
TCP - Is a realible and connection oriented protocol means your traffic is encrypted and safe.
    "If attacker intercept the packets but they can't decode them."

HTTP - This protocol is used to render hyperlinks and webpages to server and it also help user to interact with server.

DNS - According to his name domain name system it converts domain to ip address because we can't learn every ip address :)

Let's learn how can you capture traffic you need a tool called wireshark 
1. Open it and select your interface like wlan0
2. Now click on blue button
3. Now it "start capturing packets” 🦈
4. Now save the file, Open it and click on filter search and add "http||dns||tcp" and enter it.(if you don't understand check a screenshot i shared.)
5. Save it as filtered_packets or any name you want.

"Sorry for bad english and fun i am this type of person and this is whole writeup by me"

Note : "Sample wireshark files are attached so, for learning purpose only."
