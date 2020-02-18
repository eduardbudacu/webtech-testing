# Evaluare generală proiecte Tehologii Web

## Faza 0 

* formarea echipelor 
* alocarea temelor de produs
* git repo

## Faza 1 - documentare 

* Este prezentat obiectivul general al aplicației
* Este prezentat grupul țintă pentru care se adresează aplicația
* Sunt identificate produse similare 
* Este propusă o schiță de design a aplicației
* Sunt descrise componente aplicației
* Sunt identificate entități și tipurile de request-uri HTTP

## Faza 2 - prima versiune cu backend și frontend minimal

* Este publicat un server web funcțional
* Server-ul servește conținutul static al directorului build de pe frontend
* Sunt definite modele pentru entitățile din baza de date
* Credențialele la baza de date sunt stocate într-un fișier de configurare pentru care există un model versionat
* Pe git NU sunt stocate credentiale sau alte date sensibile
* Există un script cu care se realizează structura bazei de date și sunt introduse date de test
* Sunt definite rute pentru operațiile CRUD pe fiecare entitate
* Endpoint-urile de API răspund cu statusul corespunzător operației realizate și returnează date în format JSON (atunci când este cazul)
* Este publicată o versiune minimală de frontend
* Este generată structura inițială (create-react-app, vue cli, sau angular cli) sau este implementat propriul mecanism de build
* Este definită o componentă de test
* Sunt definite fișiere de configurare (eg. adresa de bază pentru API)
* Este testată comunicarea cu backend-ul (folosind fetch, axios sau XMLHttpRequest))
* Aplicația pornește în modul de dezvoltare
* Comenzile de build generează versiunea de producție
* Sunt descrise instrucțiuni de pornire în README.md

# Demo day

Aplicața completă - se livrează în ultimul seminariu (demo) cu o singura regulă:

No slides, no bulls*it!

Se vor demonstra:

* funcționalitățile aplicației (responsabil de produs)
* arhitectura produsului și mediul de lucru (responsabil de proiect)
* produsul pe componente front-end / back-end / db (întreaga echipă)

Prezentare: 10 min + Q&A
