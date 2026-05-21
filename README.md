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
```<img width="1373" height="793" alt="Screenshot 2026-05-21 201225" src="https://github.com/user-attachments/assets/4454687a-e2b3-4117-9258-b3fa12f95c53" />
<img width="1907" height="1012" alt="Screenshot 2026-05-21 201147" src="https://github.com/user-attachments/assets/b11c7ef0-82cf-46ac-883d-9aeb3a614d2d" />
<img width="1901" height="970" alt="Screenshot 2026-05-21 201129" src="https://github.com/user-attachments/assets/28fa9ed5-14b6-4612-803c-3ae3a7feb12f" />
<img width="1900" height="999" alt="Screenshot 2026-05-21 201114" src="https://github.com/user-attachments/assets/24a8b3d3-8e04-4080-aab8-13d803ed9f8f" />
<img width="1904" height="951" alt="Screenshot 2026-05-21 201059" src="https://github.com/user-attachments/assets/edc0ff9a-e41a-4ffd-a5c5-1781f97af23a" />

****CONCLUSION****
I initially struggled understanding chmod values like 770 and 755, but later understood they represent rwx permissions numerically.
