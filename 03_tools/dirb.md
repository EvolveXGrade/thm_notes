# dirb or dirbuster

Tags: #tool #web #enumeration #discovery #attack-surface #offensive #dirb #dirbuster

---

## Purpose

`Dirbuster` is a tool used to discover hidden directories and files in web applications by brute-forcing common names. It helps identify parts of a web application that are not directly accessible through normal navigation.

---

## What Problem It Solves

Web applications often contain:
- Unlinked directories
- Forgotten admin panels
- Backup or development files

`Dirbuster` automates the process of testing common paths to uncover this hidden attack surface.

---

## When to Use It

- A web service is accessible
- Visible content is limited or incomplete
- You are in the **enumeration phase**, not exploitation

`Dirbuser` is typically used early during web assessment.

---

## Basic Usage

```bash
dirb http://target
```

This uses a default wordlist to test common directory and file names.

---

## Notes

- The specific tool is interchangeable (e.g. gobuster, ffuf)
- The key skill is recognizing when directory enumeration is needed
- Results should be analyzed, not blindly exploited
