# linux-user-permissions-lab
This lab demonstrates Linux user management, group management, and file permissions on an Azure Linux Virtual Machine.

**Skills Practiced**
- Azure Virtual Machines
- SSH access
- Linux user management
- Linux groups
- File permissions
- chmod
- chown
- Cloud security basics
-
-
-   **Commands Used**
## Create Users

```bash
sudo adduser devops1
sudo adduser tester1
```

## Create Group

```bash
sudo groupadd cloudteam
```

## Add Users to Group

```bash
sudo usermod -aG cloudteam devops1
sudo usermod -aG cloudteam tester1
<img width="1373" height="793" alt="Screenshot 2026-05-21 201225" src="https://github.com/user-attachments/assets/90f37e09-e224-4dad-b980-48979490f582" />
<img width="1907" height="1012" alt="Screenshot 2026-05-21 201147" src="https://github.com/user-attachments/assets/1b36ade8-b32d-4673-9910-664975c3b713" />
<img width="1901" height="970" alt="Screenshot 2026-05-21 201129" src="https://github.com/user-attachments/assets/2549aa22-b8b4-4c46-84d1-de361e52866c" />
<img width="1900" height="999" alt="Screenshot 2026-05-21 201114" src="https://github.com/user-attachments/assets/fcc8521a-8de6-4a21-9657-1b3a3708d90c" />
<img width="1904" height="951" alt="Screenshot 2026-05-21 201059" src="https://github.com/user-attachments/assets/fc615c83-3588-4f45-9f28-7fdc23e8efc2" />

****CONCLUSION****
I initially struggled understanding chmod values like 770 and 755, but later understood they represent rwx permissions numerically.
