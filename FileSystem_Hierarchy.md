-------------------------  File System Hierarchy in Linux  -------------------------------

1. / : Root Directory (starting point of the file system everything begins Here.)

2. /bin : essential user commands (ls, cp, mv, cat, echo, etc..) availble in single user and multiple user mode. 

3. /sbin : system administration commands (fdisk, reboot, ifconfig). mostly for root user. 

4. /usr : user applications and programs (largest directory in linux). 
 contains (/usr/bin, /usr/sbin, /usr/lib, /usr/local)

5. /boot : Bootloader files, linux kernel, GRUB config system boots from here...

6. /etc : system configuration files (passwd, hosts, ssh, fstab)

7. /home : user home directories (e.g., /home/rahul, /home/hiloni). 

8. /root : Home directory for root user 

9. /lib : shared libraries required by programs in /bin and /sbin

10. /var : variables data - logs, mail, print, jobs, cache (/var/log).

11. /tmp : temporary files created by system/apps, deleted automatically. 

12. /dev : Devices files - treat hardware as files (/dev/sda, /dev/usb, /dev/tty). 

13. /proc : virtual filesystem, kernel and process into (CPU, Memory details) 
- No read files

14. /sys : system and hardware information works with /proc. 

15. /media : automatically mount point, manually mounted devices or partitions

16. /opt : optimal / third-party software (Chrome, VMare, etc.) its installed manually 

17. /srv: Data for servers (web server, FTP server data)

18. /run : Runtime Variable data - process IDs and sockets after boot. 

19. /bin : binaries (common Commands)

20. /sbin : system binaries

21. /etc : ediatable text configs 

22. /home : user's homes

23. /var : Varibles Changing Data 

24. /tmp : Temporary files 

25. /dev : Devices

26. /proc :  processes and kernel info 

27. /usr : user installed programs 

28. /boot : Boot files 

// why fiels system Hierarchy is Important in linux 
- keep linux organized 
- ensures compatibility between distros 
- standard locations make trouble shooting easier
- developers know where to place files


