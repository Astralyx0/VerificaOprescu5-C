** Comandi Usati **

// subito dopo aver creato la cartella
//per inizializzare una repository vuota in cui contenere la cartella
git init
> Initialized empty Git repository in C:/5Ct-i/Oprescu/Oprescu_riccardo_20261020/esercizio1/.git/

//successivamente per aggiungere i contenuti nell'area di "staging" 
git add .

//ogni tot tempo / modifica, dopo "git add ."
git commit -m "messaggio"


//per fare il login 
gh auth login
//e navigando tra i prompt, si fa il login alla piattaforma github

// una volta creata la repository su github
//per pushare :

git remote add origin https://github.com/Astralyx0/VerificaOprescu5-C.git
git branch -M main
git push -u origin main