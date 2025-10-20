# ElevateLabs_Task_1
Today i have used namp and done TCP scanning using command : nmap -sS 192.168.1.0/24(IP) and also found my local IP range.
Then i had used command nmap -A (IP) for aggressive scanning where i got lot of details like OS detection, its version and status of ports.
Through wireshark i have analyzed packet capturing. by selecting eth0() then i had selected one packet and read the information about it.
After finding the open ports i had reserached about them. for me port 53/tcp was open, this port enables to leak all the hostnames. 

 go through the pdf in ElevateLabs_Task_1_file to understand more.
