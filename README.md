# Get Your IP Address using Python

This Python script prints your IP address using `socket.gethostbyname(socket.gethostname())`.


## Usage
Run the following Python script:

```python
import socket

hostname = socket.gethostname()
ip_address = socket.gethostbyname(hostname)

print("Your IP address is:", ip_address)

