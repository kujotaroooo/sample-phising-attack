# Phishing Simulation 




---

##  Clone the Project

Clone this repository to get started:

```bash
https://github.com/kujotaroooo/sample-phising-attack.git
cd server.py
```


---



---

##  Installation Steps

### 1. Prepare Your Environment

Make sure Python is installed.

Open your terminal and run:

```bash
cd C:\server.py     # Or wherever you placed the folder
python -m venv venv
.\venv\Scripts\activate
```

### 2. Install Required Libraries

```bash
pip install flask
```

---

##  How to Start the Phishing Server

### Step 1: Activate and Run Python Server

```bash
cd C:\server.py
.\venv\Scripts\activate
python server.py
```

![Python Flask Server](screenshots/py.png)

### Step 2: Start ngrok Tunnel

Make sure `ngrok.exe` is downloaded and either:

- Placed in your project folder, or
- Added to your system PATH.

Then run:

```bash
cd C:\ngrok         # Or wherever ngrok.exe is located
ngrok http 8080
```

![NGROK RUNNING](screenshots/ngrok.PNG)

---

##  Public Access Link

ngrok will provide a link like:

```
https://xxxx-xxx-xxx.ngrok-free.app
```

✅ This link works across networks (not just on the same Wi-Fi).

## GO TO BROWSER PASTE THAT LINK

you will see your template of facbook there like this:

THIS INTERFACE IS CAN BE MODIFY

![browse](screenshots/1.png)



## THE PASSWORD AND USERNAME STORED 

check it:

![](screenshots/2.png)
|
![](screenshots/3.png)
|
![](screenshots/4.png)


## MAKE SURE NGROK AND PYSERVER STILL RUNNING WHILE PERFORMING

pyserver:

![](screenshots/5.png)


ngrok:

![](screenshots/6.png)

note!:
without ngrock the phishing cant be accesss online, ngrock create route for the local website
##  Author

**kujotaroooo** 
