# HTTP Echo Server

A simple multithreaded server built with Python.  
The server consists of two parallel services:
1. An HTTP file server running on port 3000
2. A TCP echo server running on port 5000

This project demonstrates multithreading, low-level socket programming, and HTTP file serving.

## 🚀 Features

- HTTP server serving static files (HTML, images, JSON etc.)
- TCP echo server that receives text messages and echoes them back
- Runs both servers in parallel using Python `threading.Thread`
- Clean file handling and error management
- Example use case of `http.server` + `socket`

## 🏗️ Technologies

- Python 3.8+
- Standard libraries only (`http.server`, `socket`, `threading`, `os`, `json`)

## 📦 Installation

1. Clone this repository:

```bash
git clone https://github.com/pawel544/http_echo_server.git
cd http_echo_server
