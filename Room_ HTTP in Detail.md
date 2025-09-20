# Room: HTTP in Detail
**Platform:** TryHackMe  
**Difficulty:** Beginner  
**Date Completed:** 20th September 2025  

---

## 🗒️ Room Summary
This room gave me a clear understanding of how the HyperText Transfer Protocol (HTTP) works. I learnt how web browsers and servers communicate with each other using requests and responses. The room also explained anout cookies along with status codes and requets types.

## 🔑 Key Takeaways
- HTTP is the protocol used for communication between a client (like a browser) and a server.  
- Common HTTP request methods include:  
  - **GET**: Retrieve information from a server.  
  - **POST**: Send data to the server (like form submissions).  
  - **PUT**: Update existing information.  
  - **DELETE**: Remove information.  
- Status codes tell us what happened during the request:  
  - **200 OK** → Success.  
  - **301/302** → Redirects.  
  - **403 Forbidden** → Access denied.  
  - **404 Not Found** → Resource missing.  
  - **500 Internal Server Error** → Server-side problem.  
- HTTPS is the secure version of HTTP and uses encryption.
- Oh, and also cookies are also used for security purposes and uh, used for user's convenience. 

## 🖥️ Practical Learning
I practiced capturing HTTP requests and responses using the built-in tools in TryHackMe.  
I looked at request headers, response headers, and saw how cookies and session data are exchanged between client and server.  

## 📸 Some Screenshots
- Example of a GET request:  
![GET-Request](/images/http1.png)  

- POST request sending data:  
![POST-Request](/images/http2.png)  

- A DELETE request for deleting:  
![DELETE-request](/images/http3.png)  

## 🌍 Why HTTP Matters
Every website relies on HTTP/HTTPS for communication. As a cybersecurity learner, understanding this protocol is important to test the vernability of a website.
