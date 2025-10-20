# 🧩 Python Greetings Pipeline

CI/CD piegādes konveijers Python mikropakalpojumam, kas izveidots, izmantojot **GitHub Actions**.  
Projekts demonstrē nepārtrauktas integrācijas un piegādes (CI/CD) procesu automatizāciju ar vairāku vides (dev, staging, preprod, prod) atbalstu.

## 🎯 Mērķis
Izveidot pilnu piegādes konveijeru Python REST API servisam, kas:
- klonē aplikācijas un testu repozitorijus,
- instalē Python un Node.js atkarības,
- izvieto servisu vairākās vidēs (dev → staging → preprod → prod),
- izpilda API testus katrā vidē.

## ⚙️ Izmantotās tehnoloģijas
- **GitHub Actions** – CI/CD konveijera automatizācija  
- **Python** – mikropakalpojuma izstrādei  
- **PM2** – Python servisa procesu pārvaldība  
- **Node.js + NPM** – API testu izpilde ar ārēju ietvaru  
- **course-js-api-framework** – ārējais testēšanas ietvars  
- **YAML konfigurācija** – CI/CD plūsmas definēšanai  

## ▶️ Darbība
Konveijers tiek iedarbināts katra `push` gadījumā.  
Katrs posms (install, deploy, test) tiek izpildīts secīgi četrās vidēs, un katrā tiek veikti API testi, lai nodrošinātu stabilu izvietojumu.


