# Wordfence Manual Configuration

This project contains the configuration of WordPress Plugins from scratch that makes the website strong against attacks like:

## Getting Started

To get started:

1. Download `WordFence Plugin` and enable Free Version through following Obtain License Key Steps.
2. Download `Loginizer` For Enhanced Brute Force Attacks.
3. Download `HSTS Ready` - For implementing HTTP Strict Transport Security (HSTS) to prevent MiTM Attacks.
4. Visit each folder on the left one by one to understand the Configuration Steps.



## Configuration Steps

Go to **WordFence Plugin > All Options**

### 1. **General Wordfence Options**

1. Update Wordfence automatically when a new version is released? > On  
   - Why: It keeps the plugin version updated automatically.  
2. Where to email alerts > `youremail@domain.com`  
3. How does WordFence get IPs? > Let Wordfence use the most secure method to get visitor IP addresses. Prevents spoofing and works with most sites.  
4. Look up visitor IP locations via Wordfence servers > On  
5. Hide WordPress version > On  
6. Disable Code Execution for Uploads directory > On  
7. Pause live updates when window loses focus > On  



### 2. **Dashboard Notification Options**

1. Updates Needed (Plugin, Theme, or Core) > On  



### 3. **Email Alert Preferences**

1. Email me if Wordfence is deactivated > On  
2. Email me if the Wordfence Web Application Firewall is turned off > On  
3. Alert me with scan results of this severity level or greater > Low  
4. Alert when an IP address is blocked > On  
5. Alert when someone is locked out from login > On  
6. Alert when someone is blocked from logging in for using a password found in a breach > On  
7. Alert when the "lost password" form is used for a valid user > On  
8. Alert me when someone with administrator access signs in > On  
9. Alert me when there's a large increase in attacks detected on my site > On > 0  



### 4. **Activity Report**

1. Enable email summary > Once a Week (Optional)  
2. Enable activity report widget on the WordPress dashboard > On  



### 5. **Advanced Firewall Options**

1. Rules  
   1. Turn On for All Options  



### 6. **Brute Force**

1. Enable brute force protection > On  
2. Immediately lock out invalid usernames > admin  
3. Prevent the use of passwords leaked in data breaches > For Admin Only  



### 7. **Additional Options**

1. Enforce strong passwords > On  
2. Don't let WordPress reveal valid users in login errors > On  
3. Prevent users registering 'admin' username if it doesn't exist > On  
4. Prevent discovery of usernames through '/?author=N' scans, the oEmbed API, the WordPress REST API, and WordPress XML Sitemaps > On  
5. Disable WordPress application passwords > On  



### 8. **Scan Scheduling**

1. Enabled  
2. Let Wordfence choose when to scan my site (recommended) > On  



### 9. **Basic Scan Type Options**

1. Standard Scan  



### 10. **General Options**

1. Scan for misconfigured How does Wordfence get IPs (opens in new tab) > On  
2. Scan for publicly accessible configuration, backup, or log files (opens in new tab) > On  
3. Scan for publicly accessible quarantined files (opens in new tab) > On  
4. Scan core files against repository versions for changes (opens in new tab) > On  
5. Scan theme files against repository versions for changes (opens in new tab) > On  
6. Scan plugin files against repository versions for changes (opens in new tab) > On  
7. Scan wp-admin and wp-includes for files not bundled with WordPress (opens in new tab) > On  
8. Scan for signatures of known malicious files (opens in new tab) > On  
9. Scan file contents for backdoors, trojans, and suspicious code (opens in new tab) > On  
10. Scan file contents for malicious URLs (opens in new tab) > On  
11. Scan posts for known dangerous URLs and suspicious content (opens in new tab) > On  
12. Scan comments for known dangerous URLs and suspicious content (opens in new tab) > On  
13. Scan WordPress core, plugin, and theme options for known dangerous URLs and suspicious content (opens in new tab) > On  
14. Scan for out of date, abandoned, and vulnerable plugins, themes, and WordPress versions (opens in new tab) > On  
15. Scan for suspicious admin users created outside of WordPress (opens in new tab) > On  
16. Check the strength of passwords (opens in new tab) > On  
17. Monitor disk space (opens in new tab) > On  
18. Monitor Web Application Firewall status (opens in new tab) > On  
19. Scan files outside your WordPress installation (opens in new tab) > On  
20. Scan images, binary, and other files as if they were executable (opens in new tab) > On  



### 11. **Performance Options**

1. Use low resource scanning (reduces server load by lengthening the scan duration) > On  



### Import Entire Configuration

If you would like to import the entire configuration using the "All Options" settings, here is the code:

```bash
1f458e1f67b471a84c8931f7b0691fc11161eec79c54b0b98c2680b5789a1ec16d7086a1f75d00654bcba449cba501cd9b1090ffd7c969094de09be69976a2cc
```

