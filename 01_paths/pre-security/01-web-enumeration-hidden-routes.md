# Web Enumeration – Hidden Routes

Tags: #web #enumeration #discovery #attack-surface #presecurity #tryhackme #offensive

## Concept

Web applications often contain routes, directories or endpoints that are not directly visible through normal navigation. These hidden routes may expose additional functionality, configuration files or administrative interfaces.

---

## What Problem This Addresses

When visiting a web application, the visible pages usually represent only a small part of what actually exists on the server.

Hidden routes can reveal:
- Admin panels
- Development or backup files
- Misconfigured resources
- Additional attack surface

---

## What Is Being Discovered

- Directories not linked from the main site
- Endpoints guessed from common naming patterns
- Forgotten or temporary resources

This process is part of **web enumeration**, not exploitation.

---

## When to Apply This

- A web service is accessible
- The visible content is limited or uninteresting
- Further discovery is needed before moving on

Hidden route discovery is usually performed early during web assessment.

---

## Example Tool

One common tool used for this purpose is `dirb`, Dirbuster.

```bash
dirb http://target
```
