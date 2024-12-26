<div align="center">
  <a href="https://github.com/mpeyre-s/42_born2beroot"><img src="https://github.com/mpeyre-s/42_project_badges/raw/main/badges/born2beroot.svg"/></a>
  <p>The aim of this project is to set up and configure a virtual machine to understand the fundamentals of system administration and Linux security.</p>
  <br>
</div>

# ➡️ Competencies Acquired

- **Linux System Fundamentals**: Gained a deep understanding of the Linux operating system, including its structure, core components, and essential tools.

- **User and Group Management**: Learned to manage users and groups, including the creation, deletion, and assignment of permissions to ensure proper system security.

- **Strong Password Policies**: Implemented and enforced a strong password policy to enhance system security and mitigate brute-force attacks.

- **SSH Configuration**: Mastered Secure Shell (SSH) setup and configuration for secure remote access to the virtual machine.

- **Firewall Management**: Configured and maintained a firewall using `ufw` to control network traffic and protect the system from unauthorized access.

- **System Updates and Security**: Learned to keep the system secure and up to date by managing software updates and monitoring vulnerabilities.

- **Automated Services and Monitoring**: Configured essential services like `cron` for automation and used monitoring tools to ensure system health and performance.

- **Disk Partitioning and LVM**: Gained experience in disk management using Logical Volume Manager (LVM) to optimize storage flexibility and efficiency.

- **Administrative Practices**: Developed the skills to manage administrative tasks, such as resource monitoring, process management, and troubleshooting system issues.

# ➡️ VM Features and Specifications

1. **Operating System**:  
   - Installed and configured a lightweight Linux distribution (Debian or Ubuntu) for the virtual machine.

2. **Password Policy**:  
   - Enforced a strong password policy with the following requirements:  
     - Minimum length: 10 characters.  
     - Must include uppercase, lowercase, numbers, and special characters.  
     - Password expiration: 30 days.  
     - History: Prevent reuse of the last 5 passwords.  
     - Lockout after 3 failed login attempts.  

3. **SSH Configuration**:  
   - Configured SSH to allow secure remote access:  
     - Disabled root login via SSH.  
     - Changed the default port for added security.  
     - Set up public/private key authentication.  

4. **Firewall (UFW)**:  
   - Enabled and configured `ufw` (Uncomplicated Firewall):  
     - Allowed only essential ports (e.g., SSH).  
     - Logged and monitored unauthorized access attempts.  

5. **User Roles and Groups**:  
   - Created dedicated user accounts with restricted permissions.  
   - Configured `sudo` for administrative privileges.  

6. **LVM (Logical Volume Manager)**:  
   - Implemented LVM for flexible and efficient disk partitioning.  
     - Created and resized logical volumes for future scalability.  

7. **Service Monitoring**:  
   - Set up `cron` jobs for periodic system updates and log rotation.  
   - Configured monitoring tools to track CPU, memory, and disk usage.  

This project provided hands-on experience in configuring a secure and efficient Linux server environment, laying the foundation for advanced system administration tasks.
