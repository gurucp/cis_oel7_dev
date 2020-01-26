Ansible-OEL-Benchmarks 

Note: Please ensure these changes are apropriate to your environment before executing this role. This is only applicable for Oracle Enterprise Linux 7.x only. 


Here are the list of tested no downtime required benchmarks which has been implemented as on Jan-26-2020



 1.1.1.1 Ensure mounting of cramfs filesystems is disabled
 
 1.1.1.2 Ensure mounting of freevxfs filesystems is disabled
 
 1.1.1.3 Ensure mounting of jffs2 filesystems is disabled
 
 1.1.1.4 Ensure mounting of hfs filesystems is disabled
 
 1.1.1.5 Ensure mounting of hfsplus filesystems is disabled
 
 1.1.1.6 Ensure mounting of squashfs filesystems is disabled
 
 1.1.1.7 Ensure mounting of udf filesystems is disabled
 
 1.1.1.8 Ensure mounting of FAT filesystems is disabled - !!!!Check if the system is already using vfat !!!!
 
 1.1.14  Ensure nodev option set on /home partition
 
 1.1.15  Ensure nodev option set on /dev/shm partition
 
 1.1.16  Ensure nosuid option set on /dev/shm partition
 
 1.1.17  Ensure noexec option set on /dev/shm partition
 
 1.1.3 Ensure nodev option set on /tmp partition
 
 1.1.4 Ensure nosuid option set on /tmp partition
 
 1.2.3 Ensure gpgcheck is globally activated
 
 1.3.1 Ensure AIDE is installed
 
 1.3.2 Ensure filesystem integrity is regularly checked
 
 1.4.1 Ensure permissions on bootloader config are configured
 
 1.4.3 Ensure authentication required for single user mode
 
 1.5.1 Ensure core dumps are restricted
 
 1.5.3 Ensure address space layout randomization (ASLR) is enabled
 
 1.5.4 Ensure prelink is disabled
 
 1.7.1.5 Ensure permissions on /etc/issue are configured
 
 2.2.19 Ensure telnet server is not enabled
 
 2.3.1 Ensure NIS Client is not installed
 
 2.3.2 Ensure rsh client is not installed
 
 2.3.3 Ensure talk client is not installed
 
 2.3.4 Ensure telnet client is not installed
 
 2.3.5 Ensure LDAP client is not installed
 
 3.1.1 Ensure IP forwarding is disabled
 
 3.1.2 Ensure packet redirect sending is disabled
 
 3.2.1 Ensure source routed packets are not accepted
 
 3.2.2 Ensure ICMP redirects are not accepted
 
 3.2.3 Ensure secure ICMP redirects are not accepted
 
 3.2.4 Ensure suspicious packets are logged
 
 3.2.5 Ensure broadcast ICMP requests are ignored
 
 3.2.6 Ensure bogus ICMP responses are ignored
 
 3.2.7 Ensure Reverse Path Filtering is enabled
 
 3.2.8 Ensure TCP SYN Cookies is enabled
 
 3.4.1 Ensure TCP Wrappers is installed
 
 3.4.4 Ensure permissions on /etc/hosts.allow are configured
 
 3.4.5 Ensure permissions on /etc/hosts.deny are configured
 
 3.6.1 Ensure iptables is installed
 
 4.1.2 Ensure auditd service is enabled
 
 4.2.1.3 Ensure rsyslog default file permissions configured
 
  5.1.1 Ensure cron daemon is enabled
  
 5.1.2 Ensure permissions on /etc/crontab are configured
 
 5.1.3 Ensure permissions on /etc/cron.hourly are configured
 
 5.1.4 Ensure permissions on /etc/cron.daily are configured
 
 5.1.5 Ensure permissions on /etc/cron.wekkly are configured
 
 5.1.6 Ensure permissions on /etc/cron.monthly are configured
 
 5.1.7 Ensure permissions on /etc/cron.d are configured
 
 5.2.1 Ensure permissions on /etc/ssh/sshd_config are configured
 
 5.4.3 Ensure default group for the root account is GID 0
 
 6.1.2 Ensure permissions on /etc/passwd are configured
 
 6.1.3 Ensure permissions on /etc/shadow are configured
 
 6.1.4 Ensure permissions on /etc/group are configured
 
 6.1.5 Ensure permissions on /etc/gshadow are configured
 
 6.1.6 Ensure permissions on /etc/passwd- are configured
 
 6.1.7 Ensure permissions on /etc/shadow- are configured
 
 6.1.8 Ensure permissions on /etc/group- are configured
 
 6.1.9 Ensure permissions on /etc/gshadow- are configured
 
 6.2.15 Ensure all groups in /etc/passwd exist in /etc/group
 
 6.2.3 Ensure no legacy "+" entries exist in /etc/shadow
 
 6.2.4 Ensure no legacy "+" entries exist in /etc/group
 
 6.2.5 Ensure root is the only UID 0 account
 
 6.2.7 Ensure all users' home directories exist
 
