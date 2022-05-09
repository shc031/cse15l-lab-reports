# LAB REPORT 3 ![Image](0fbb0991732bbe47e5b419c333b368e1_w48_h48.png)	
> By Rita Chang

## Streamlining ssh Configuration
> I create a file of ```.ssh/config``` with hostname and user name. 

![Image](config1.PNG)	

> This way when I want to login to the remote server, I could just use the ssh command with ieng6(the name after ```Host``` to ) without typing out the whole hostname and user name.

![Image](ieng6login2.PNG)	

> I could also run the ```scp``` command with ```(Name after Host):~/```.

![Image](scp3.PNG)	

---

## Setup Github Access from ieng6

The private key and private key is stored in .ssh on my user account:
![Image](before4.PNG)	

Public key you made is stored on Github:
![Image](KeyUserAccount4.PNG)	

Running git commands to commit and push a change to Github while logged into your ieng6 account:
![Image](gitcommands5.PNG)	

[Resulting Commit](https://github.com/shc031/cse15l-lab-reports/commits/main)

---	

## Copy whole directories with scp -r

