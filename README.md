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

| Deltagare 	| AWS host                                            	|
|-----------	|-----------------------------------------------------	|
| Extra 1      	| ec2-16-171-3-213.eu-north-1.compute.amazonaws.com   	|
| Azeb      	| ec2-16-170-240-123.eu-north-1.compute.amazonaws.com 	|
| Dennis    	| ec2-13-53-129-79.eu-north-1.compute.amazonaws.com   	|
| Erik      	| ec2-13-51-194-242.eu-north-1.compute.amazonaws.com  	|
| Emelie    	| ec2-13-51-160-254.eu-north-1.compute.amazonaws.com  	|
| Johan B   	| ec2-16-171-5-138.eu-north-1.compute.amazonaws.com   	|
| Johan Å   	| ec2-16-171-10-211.eu-north-1.compute.amazonaws.com  	|
| Jonathan  	| ec2-16-170-204-198.eu-north-1.compute.amazonaws.com 	|
| Patrik    	| ec2-16-171-43-55.eu-north-1.compute.amazonaws.com   	|
| Simon     	| ec2-16-170-203-241.eu-north-1.compute.amazonaws.com 	|
| Sofie     	| ec2-16-171-7-76.eu-north-1.compute.amazonaws.com    	|
| Louise B    	| ec2-13-49-49-38.eu-north-1.compute.amazonaws.com    	|
| Louise J   	| ec2-16-171-15-69.eu-north-1.compute.amazonaws.com   	|
| Josefine  	| ec2-16-171-21-9.eu-north-1.compute.amazonaws.com    	|
| Emil Ö   	| ec2-13-51-204-98.eu-north-1.compute.amazonaws.com   	|
| Emil T   	| ec2-16-170-235-239.eu-north-1.compute.amazonaws.com 	|
| Olof   	| ec2-13-53-155-152.eu-north-1.compute.amazonaws.com  	|
| Frida   	| ec2-13-51-207-53.eu-north-1.compute.amazonaws.com   	|
| Jennifer   	| ec2-16-170-251-145.eu-north-1.compute.amazonaws.com 	|
| John   	| ec2-13-49-68-251.eu-north-1.compute.amazonaws.com   	|

---

# Introduktion:


Mentimeter - Gå till menti.com och ange följande kod: 1632 0608 

---

# Linux command list

## Secure Shell
- ssh

---

## Navigering
- cd
- pwd
- ls
- clear
- echo
- history

---

## Dokumentation
- man
- --help

---

## Filhantering
- touch
- cat
- less
- more
- mv
- mkdir
- rm
- vim/vi
- nano

---

## Search
- grep
- find

---

## System
- logger
- top
- kill
- sudo
- apt update, apt upgrade, apt install
- cmatrix
- ping
- exit

---

## Behörighet
- chown
- chmod

---

# Övningar:
1. Skapa ny mapp "Cookies" i hemkatalogen. Skapa ytterligare en mapp "Cakes" i hemkatalogen.
2. Gå till mappen Cookies och skapa en textfil som får heta "chocolate-cookie.md" i valfri editor. 
3. Gå till mappen Cakes och skapa en textfil som får heta "princess-cake.md" i valfri editor.
4. Lägg in lite text i princess-cake.md filen.
5. Ändra namnet på princess-cake.md till princess-cake.txt
6. Flytta filen pricess-cake.txt till "Cookies" i hemkatalogen.
7. Ta bort princess-cake.txt filen från "Cookies" i hemkatalogen.
8. Kopiera chocolate-cookie.md filen från "Cookies" till "Cakes" katalogen.
9. Kontrollera att svd.se domänen är uppe och är aktiv.
10. Kör kommandot `logger "smurf"`. Detta kommer att skapa ett loggmedelande i systemlogg som finns i /var/log katalogen. I vilken av loggfilerna där hamnade "smurf" meddelandet? 

---
