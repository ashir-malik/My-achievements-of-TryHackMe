# Room: Windows Fundamentals 1  
**Platform:** TryHackMe  
**Difficulty:** Beginner  
**Date Completed:** 26th October 2025  

---

## 🗒️ Room Summary  
This room helped me understand the basics of the Windows operating system so I know how it’s structured, what the main system folders do, and how users interact with it. I learnt about different Windows editions, how the Desktop and File Explorer work, and how files are organized inside the system. It also explained the purpose of important folders like `C:\Windows\System32`, the role of user accounts and permissions, what UAC (User Account Control) does, and how to use the Task Manager to monitor running programs.  

---

## 🔑 Key Takeaways  
- Windows has multiple editions such as Home, Pro, and Enterprise which are each designed for different users and use cases.  
- The Desktop and File Explorer make it easy to manage and access files.  
- The `C:\Windows\System32` folder contains critical system files that keep Windows running properly.  
- User accounts and profiles define access levels and permissions, ensuring each user’s privacy and data separation.  
- UAC (User Account Control) helps protect the system by asking for permission before making major changes.  
- Task Manager is a powerful tool to check performance, manage processes, and end unresponsive programs.  

---

## 📸 Some Screenshots  
- I used the utility `lusrmgr.msc`:  
  ![Lusrmgr](/images/bateek1.png)  
- Checking the groups which the following user is a member of as follows:   
  ![System32-Folder](/images/bateek2.png)  
---

## 💡 Why It Matters  
Understanding Windows fundamentals is essential for cybersecurity since a lot of attacks target or exploit Windows systems. Knowing how the operating system functions internally helps in identifying unusual system behavior and securing it effectively.
