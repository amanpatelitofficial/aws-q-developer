# aws-q-developer

### Make sure your machine is updated and has Libfuse2 installed

````bash
sudo apt-get update
````

`````bash
sudo apt install libfuse2

`````

### Install the deb file for Amazon Q

````bash
curl --proto '=https' --tlsv1.2 -sSf https://desktop-release.q.us-east-1.amazonaws.com/latest/amazon-q.deb -o amazon-q.deb
````

### Install Amazon Q debian file

````bash
sudo apt install -y ./amazon-q.deb
````

### Login 

````bash
q login
````

