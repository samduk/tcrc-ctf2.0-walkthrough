- ssh -i tcrc3\_ssh tcrc3@52.172.253.159
- password: tcrcCTF{Thankgod\_you\_didn't\_forget\_base64}

- scp tcrc3@52.172.253.159:/home/tcrc3/samdup/flag.txt .
- same password 

It shows the same flag as the tcrc1 flag. Therefore, I am going to use the flag which is embeded in the meta file. 
- exiftool flag.txt 
- tcrcCTF{meta\_data\_is\_powerful}

