# Engeto lekce 5 - Git a Githubgit st
Testovací repozitář v rámci akademie engeta
git clone - clonování depozitáře
git status - podívání se na stav  
git commit -m "" - přidání komentáře k provedeným změnám
ls - zobrazení listu ve kterém se aktuálně nacházím
git log -
git push - změny provedené u mě na pc se propíší i na github server
git add . -- zařazení všech změněných souborů do úložiště
repozitář - místo kde se ukládá náš kód
jak propsat změny na guthub server:
1. uložit přes save (File - Save)
2. příkaz git add . 
3. příkaz git commit -m "" = okomentovat co za změny jsme provedli 
4. příkaz git push = propsání na github serverg

git pull - propsání změn se serveru na můj počítatč
git diff - změna souboru
1. Nezměněn díky větám: 
# my-github-repo
I will test my Git knowledge on this repo.
I have added new text into this file.
2. Připraven k zapsání díky větě: This is a staged line
3. Změněn díky větě: This is an unstaged line

git diff HEAD README.md - Kdybychom chtěli porovnat poslední commit (nezměněn) se všemi změnami (změněn i připraven k zapsání)
git diff README.md - Pro porovnání stavů změněn a připraven k zapsání můžeme použít
git diff --staged README.md nebo git diff --cached README.md - Pro porovnání stavů (poslední commit) a připraven k zápisu

.gitignore - uvádíme ty soubory, které se mají ignorovat. Pokud neuvedeme nic, budou se ukládat všechny soubory.