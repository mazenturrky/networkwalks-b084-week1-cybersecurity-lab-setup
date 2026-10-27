# networkwalks-b084-week1-cybersecurity-lab-setup
Cybersecurity Lab setup
first : download virtualbox 
second : install virtualbox
third : download kali linux 2026.3 https://www.kali.org/get-kali/#kali-virtual-machines
forth : extract all (kali file)
fifth : open kali from virtualbox
sixth : go to setting and edit the connection to NAT Network with ip address 10.0.0.0/24 and DNS 8.8.8.8
i have faced a problem in network from virtualbox and after checking everything i used this command to solve the connection problem (sudo nmcli connection modify "Wired connecton 1" ipv4.dad-timeout 0) and it worked immediately 
