# Room: Linux Fundamentals Part 3  
**Platform:** TryHackMe  
**Difficulty:** Beginner  
**Date Completed:** 4th October 2025  

## 🗒️ Room Summary
This room wrapped up the Linux Fundamentals series and gave me a lot of practical tools. I learned how to work with text editors inside the terminal, use really useful utilities like `scp`, `wget`, and even host a quick web server with `python3 -m http.server`. I also studied how processes run in Linux, how to automate tasks with crontabs, how to manage system packages using `apt`, and how to check system logs to see what’s going on in the background.  

## 🔑 Key Takeaways
- Terminal text editors like nano or vim are used to edit files without leaving the terminal.  
- Useful utilities:  
- `scp` → copy files between machines securely.  
- `wget` → download files from the internet.  
- `python3 -m http.server` → start a quick local web server.  
- Processes can be listed and monitored using commands like `ps` or `top`.  
- Crontabs let you automate tasks on schedule (like backups or scripts).  
- `apt` is used for updating, installing, and removing software packages.  
- Logs in `/var/log` show what’s happening in the system and are important for troubleshooting and security.  

## 🖥️ Practical Learning
I edited files using nano, practiced downloading files with wget, and tested file transfer with scp. Running `python3 -m http.server` helped me understand how simple hosting works. I also created a crontab entry to automate a task and used `apt update` and `apt upgrade` to keep the system clean. Finally, I opened system logs to see how they record everything from login attempts to application errors.  

## Some screenshots here
- Editing files in nano:  
![Linux-nano](/images/linux-nano.png)  
- Hosting a server with Python:  
![Linux-httpserver](/images/linux-httpserver.png)  

## Why this matters
This room felt like moving from “learning Linux” to “actually managing Linux.” These skills are the base of what system admins and cybersecurity people do every day editing configs, automating tasks, keeping the system updated, and checking logs for problems or attacks. It’s the step that makes you more confident working on real systems.
