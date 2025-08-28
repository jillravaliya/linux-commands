# linux-commands

Imagine I’m your senior admin, and I ask:
"Tell me your username, your working directory, and which Linux version you’re using."
👉 You’ll solve this just with the 4 commands above.

1.  Check who you are (your user)
```bash
whoami
```
Output: prints your current logged-in username.

2. Check where you are (your current directory),
```bash
pwd
```
Output: full path of your current location (e.g. /home/xiang).
   
3. Check what system you’re running:
```bash
uname -a
```
Output: Linux kernel + system info

4. Check distribution details,
```bash
cat /etc/os-release
```
Output: Ubuntu/Debian/Fedora version info.
