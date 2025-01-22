# Loginizer Manual Configuration

This guide outlines the detailed configuration of the Loginizer plugin to strengthen your WordPress website's login security.



## **Brute Force Settings**

1. **Max Retries**: 3  
   - Maximum failed attempts allowed before lockout.  
2. **Lockout Time**: 15 minutes  
   - Time the user is locked out after exceeding maximum retries.  
3. **Max Lockouts**: 5  
   - Maximum number of lockouts before the lockout time is extended.  
4. **Extend Lockout**: 24 hours  
   - Time to extend lockout duration after reaching maximum lockouts.  
5. **Reset Retries**: 24 hours  
   - Time interval to reset failed login attempts counter.  
6. **Email Notification**: After 1 lockout  
   - Email notification is sent after the specified number of lockouts. Set to `0` to disable notifications.  
7. **Email Address**: `youremail@growsafehse.com`  
   - Failed login attempt notifications will be sent to this email.  
8. **Trusted IPs**: Disabled  
   - If enabled, only whitelisted IPs can log in.  
9. **Blocked Screen**: Disabled  
   - If enabled, a custom error page is shown for locked-out or blacklisted users.  



## **Login Notification**

1. **Enable Notification**: Enabled  
   - Sends notifications for successful login attempts.  
2. **Disable for Whitelisted IPs**: Disabled  
   - Do not send notifications for whitelisted IPs.  
3. **Send Email as HTML**: Enabled  
   - Sends notifications in HTML format.  



## **Loginizer Security Settings**

### **Rename Login Page**

1. **New Login Slug**: (Leave blank to reset to default)  
   - Rename `wp-login.php` to a custom login page URL (e.g., `mylogin`).  

2. **Access Secretly Only**: Enabled  
   - Ensures only users with the exact URL can access the login page.  



### **XML-RPC Settings**

1. **Disable XML-RPC**: Enabled  
   - Prevents the use of XML-RPC to protect against potential attacks.  
2. **Disable Pingbacks**: Enabled  
   - Disables WordPress pingbacks to mitigate misuse.  



### **Rename Admin Page**

1. **New wp-admin Slug**: (Leave blank to reset to default)  
   - Rename `wp-admin` to a custom URL (e.g., `my-admin` or `login_page`).  

2. **Disable wp-admin Access**: Enabled  
   - Disables access to the old `wp-admin` URL.  

3. **Update .htaccess**: Enabled  
   - Updates the `.htaccess` file for the new admin slug.  



### **CSRF Protection**

1. **Enable CSRF Protection**: Enabled  
   - Adds a session string to admin URLs to protect against CSRF attacks.  
2. **Update .htaccess**: Click
   - Update the `.htaccess` file to enforce the CSRF protection settings.  



### **Change Admin Username**

1. **Current Username**: `yourname`  
   - The current administrator username.  
2. **New Username**: (Leave blank to reset)  
   - Set a new username for the administrator.  



### **Username Auto Blacklist**

1. **Username(s)**: `admin`  
   - Automatically blacklist usernames like `admin` or other common variations.  



### **New Registration Domain Blacklist**

1. **Domain(s)**: (Leave blank to reset)  
   - Specify domains to block registrations from.  



### **Limit Concurrent Sessions**

1. **Enable**: Disabled  
   - Limit the number of devices a user can log in to concurrently.  
2. **Limit Type**:  
   - **Block**: Blocks all login attempts if the limit is reached.  
   - **Destroy**: Revokes all other sessions on successful login.  
3. **Max Session Count**: 1  
   - Maximum number of sessions a user can create.  
4. **Exclude Roles**: None  
   - Excluded roles (e.g., Administrator, Editor) will not face session limits.  



