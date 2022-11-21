---
marp: true
theme: default
style: |
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
---

# En grundläggande kurs i Linux, AWS och SSH

---

# Detta behövs inför kursen

Windows-datorer
1. Datorer med Windows behöver ha Putty installerad. [https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
2. aws-linux-demo.ppk filen behöver sparas ned. Filen går att hitta på [https://knowit.sharepoint.com/:f:/r/sites/O365-Development/Shared%20Documents/Cloud%20native/SSH-key?csf=1&web=1&e=qbYYiW](https://knowit.sharepoint.com/:f:/r/sites/O365-Development/Shared%20Documents/Cloud%20native/SSH-key?csf=1&web=1&e=qbYYiW). Spara ned aws-linux-demo.ppk på valfri plats på hårddisken.

---

MacOS/Linux datorer
1. Datorer med MacOS och Linux har terminalprogram förinstallerad och behöver därför inte installera något särskilt program.
2. aws-linux-demo.pem filen behöver sparas ned. Filen går att hitta på [https://knowit.sharepoint.com/:f:/r/sites/O365-Development/Shared%20Documents/Cloud%20native/SSH-key?csf=1&web=1&e=qbYYiW](https://knowit.sharepoint.com/:f:/r/sites/O365-Development/Shared%20Documents/Cloud%20native/SSH-key?csf=1&web=1&e=qbYYiW). Spara ned awd-linux-demo.pem på ~/.ssh/ katalogen.

---

| Deltagare 	| AWS host 	|
|-----------	|----------	|
| Axel      	|          	|
| Azeb      	|          	|
| Dennis    	|          	|
| Erik      	|          	|
| Hussam    	|          	|
| Johan     	|          	|
| Patrik    	|          	|
| Simon     	|          	|
| Sofie     	|          	|
| Extra 1   	|          	|
| Extra 2   	|          	|

---

# Introduktion:


Mentimeter - 

---

# Övningar:
1. Skapa ny mapp "Cookies" i hemkatalogen. Skapa ytterligare en mapp "Cakes" i hemkatalogen.
2. Gå till mappen Cookies och skapa en textfil som får heta "chocolate-cookie.md" i valfri editor. 
3. Gå till mappen Cakes och skapa en textfil som får heta "princess-cake.md" i valfri editor.
4. Kör kommandot `logger "smurf"`. Detta kommer att skapa ett loggmedelande i systemlogg som finns i /var/log katalogen. I vilken av loggfilerna där hamnade "smurf" meddelandet? 

---
