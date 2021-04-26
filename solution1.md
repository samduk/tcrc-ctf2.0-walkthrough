### Don't get lured by the file extension, you need to check the file type. 
### Step 1
- file flag.txt 
- [screenshot]
- file is a png format. 

I ran an exiftool to check the meta data 

- exiftool flag.txt 
- and I got 
	- tcrcCTF{meta\_data\_is\_powerful}
I was like yeah.. but it was not the key because if it is key I could able to log into the tcrc2 user. 
Therefore, I had to scp the image out and view it. 

- scp tcrc1@52.172.253.159:/home/tcrc1/samdup/flag.txt . 
- eog flag.txt 
screenshot 

Solution1: tcrcCTF{now\_you\_know\_about\_file\_extensions!!!}


