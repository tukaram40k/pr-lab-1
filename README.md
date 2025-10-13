# HTTP File Server with TCP Sockets

### Course: Computer Networks

### Author: Rudenco Ivan

---

### Contents of the source directory
- `share`: folder served by the server
- `server.py`: server code
- `client.py`: client code

### Docker compose file

### Starting the container

### Starting the server
Run `python server.py share`

![alt text](img/imagge.png)

### Contents of the served directory
- `nested`: nested folder for bonus task
- `index.html`
- `img.png`
- `doc.pdf`

### Requests of files in the browser
- Nonexistent file:
![alt text](img/image-1.png)
- HTML file with image:
![alt text](img/imagee.png)
- PDF file:
![alt text](img/image-2.png)
- PNG file:
![alt text](img/image-3.png)

### Client and saving files (bonus point)
Running the client:
![alt text](img/image-4.png)

`img.png` is saved into `save`:
![alt text](img/image-5.png)

### Directory listing (bonus point)
Directory listing:
![alt text](img/image-6.png)

Nested directory listing:
![alt text](img/image-7.png)