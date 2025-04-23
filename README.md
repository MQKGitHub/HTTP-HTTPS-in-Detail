## 🛡️ What is HTTP(S)?

**Room:** [What is HTTP(S)? — TryHackMe](https://tryhackme.com/room/httpindetail)  
**Status:** ✅ Completed  
**Date:** *(22 April 2025)*  

### 🎯 Objective  
To understand how HTTP and HTTPS work, the structure of requests and responses, key headers, status codes, and the role of cookies in web communication.  

---  

### 🗝️ Key Concepts  
- HTTP vs HTTPS – HTTP is the basic protocol for loading websites; HTTPS is the secure, encrypted version.  
- URLs – Tell the browser how and where to access resources online, including things like path, query string, and port.  
- HTTP Methods – Define the action for a request (GET to retrieve, POST to submit data, PUT to update, DELETE to remove).  
- Requests & Responses – The client sends a request; the server replies with a response including a status code and data.  
- Status Codes – Show the result of a request (e.g. 200 OK, 404 Not Found, 500 Server Error).  [HTTP Status Code Examples](https://github.com/MQKGitHub/Status-Code-Image-References)
- Headers – Extra info added to requests/responses (e.g. browser type, content type, cookies, etc).  
- Cookies – Small pieces of data saved in the browser to track sessions and remember users.  

---  

### 🛠️ Tools Used  
- Browser Developer Tools — for inspecting HTTP traffic and cookies  
- TryHackMe Virtual Machine and built-in tools

---  

### ⚠️ Challenges Faced  
- Understanding how all parts of a URL fit together was a bit confusing at first.  
- Breaking down requests/responses helped things click, especially seeing real examples in Dev Tools.  

---  

### 🧠 What I Learned  
- Gained a clear understanding of how web communication happens behind the scenes.  
- Learned how different HTTP methods signal intent and how status codes show the result.  
- Realised how cookies make stateless HTTP feel "stateful" by tracking sessions.  

---  

### 🌐 Real-World Application  
> Understanding how HTTP works is essential for security testing, web development, and spotting vulnerabilities like insecure cookies or misconfigured headers.

---  

### 💭 Reflections  
- It was interesting to see how much goes on in a single webpage load.  
- I’d pay more attention to HTTP headers and status codes when troubleshooting in future.  
- The structure of a request and response is something I won’t forget.
