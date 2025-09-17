# Ubuntu-Inspired Image Fetcher 

> "I am because we are"- Ubuntu philosophy  

This program embodies the Ubuntu spirit by connecting respectfully to the wider web community, fetching images, and organizing them for later appreciation.

---

 Features
- Prompt the user for **one or multiple image URLs**
- Create a `Fetched_Images` folder automatically
- Download and save images with proper filenames
- Prevent duplicate downloads (via file hash check)
- Validate HTTP headers (saves only if `Content-Type` is an image)
- Graceful error handling for invalid URLs, network issues, and bad responses
- Uses polite request headers to respect web servers

---

 Requirements
- Python 3.x
- `requests` library

Install `requests` if not already installed:
```bash
pip install requests
