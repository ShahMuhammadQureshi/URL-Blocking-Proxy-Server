# URL-Blocking Proxy Server 🛡️

A simple Python-based proxy server that blocks access to specified websites. Designed as a university assignment to demonstrate network programming and content filtering using socket and multiprocessing modules.

## 📌 Features

- Intercepts HTTP requests via a proxy server
- Blocks specific websites listed in `blocked_sites.txt`
- Sends a custom 403 Forbidden response when a blocked site is requested
- Handles multiple connections using multiprocessing
- Supports basic HTTP communication over port 80

## 🧠 Learning Outcomes

- Socket programming fundamentals
- Network interception and filtering logic
- Handling client-server communication
- Process management in Python
- Attention to detail in request parsing and error handling

## 🔧 Requirements

- Python 3.8+
- No third-party libraries required

## 🚀 How to Run

1. Clone the repository
2. Add domains to `blocked_sites.txt` (one per line)
3. Run the script:

```bash
python proxy_server.py
