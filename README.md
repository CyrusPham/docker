# Install Docker On Ubuntu
### Step 1: Use the apt command to install the docker.io package
```bash
sudo apt install docker.io
```
### Step 2: Start docker and enable it to start after the system reboot:
```bash
sudo systemctl enable --now docker
```
### Step 3: Optionally give any user administrative privileges to docker
```bash
sudo usermod -aG docker SOMEUSERNAME
```
You will need to log out and log in to apply the changes.
### Step 4: Check docker version
```bash
docker --version
```
### Step 5: Run docker test using the hello-world container:
```bash
docker run hello-world
```
