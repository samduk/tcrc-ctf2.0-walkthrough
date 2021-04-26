- ssh -i tcrc9_ssh tcrc9@52.172.253.159
- Password: tcrcCTF{its\_steganography\_3030}
- cd samdup 
- ls 
I need to download the pcap file because I do not know how to use tshark but wireshak. 
- sudo apt install wireshark-gtk -y
- scp tcrc9\_ssh tcrc9@52.172.253.159:/home/tcrc9/capture.pcap
- wireshark capture.pcap
- http (use this filter and follow the login TCP stream)
- tcrcCTFtshark\_is\_cmdline\_of\_wireshark}
