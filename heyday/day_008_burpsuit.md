# Day 5 – Burp Suite Introduction

## What is Burp Suite?
Burp Suite is a **web application security testing tool**.  
It works as a **proxy** between the browser and the server.

It allows security testers to:
- Intercept HTTP/HTTPS requests
- Analyze web traffic
- Find security vulnerabilities (ethically)

---

## How Burp Suite Works
1. Browser sends a request
2. Burp Suite intercepts the request
3. Tester views or modifies the request
4. Request is sent to the server
5. Server sends response back through Burp

Burp acts as a **middleman**.

---

## Why Burp Suite is Important
- Understand how websites communicate
- Analyze cookies, headers, and parameters
- Essential tool for web security testing
- Widely used by professionals

---

## Main Components of Burp Suite
- **Proxy** – Intercepts requests and responses
- **Target** – Shows application structure
- **Repeater** – Resends modified requests
- **Intruder** – Automated testing (advanced)
- **Logger** – Records HTTP traffic

---

## Proxy (Most Important for Beginners)
- Intercepts browser traffic
- Allows viewing HTTP requests
- Helps understand cookies and sessions

---

## What Can Be Seen in Requests
- URL
- HTTP method (GET / POST)
- Headers
- Cookies
- Parameters

---

## Ethical Usage Rule
Burp Suite must only be used on:
- TryHackMe labs
- Practice applications
- Applications you own or have permission to test

❌ Never use on random websites.

---

## What I Learned
Burp Suite helps understand web traffic.
It is a core tool for learning web security.
