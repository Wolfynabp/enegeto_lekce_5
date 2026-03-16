# Engeto lekce 5 - Git a Githubgit st
Testovací repozitář v rámci akademie engeta
git clone - clonování depozitáře
git status - podívání se na stav  
git commit -m "" - přidání komentáře k provedeným změnám
ls - zobrazení listu ve kterém se aktuálně nacházím
git log - zobrazení historii commitu
git push - změny provedené u mě na pc se propíší i na github server
git add . -- zařazení všech změněných souborů do úložiště
git stash - odloží sledované soubory na dočasný úložný prostor
git blame - používáme ve spojení s určitým souborem. Příkaz zjišťuje, kdo upravil kterou verzi určitého řádku.

repozitář - místo kde se ukládá náš kód
jak propsat změny na guthub server:
1. uložit přes save (File - Save)
2. příkaz git add . 
3. příkaz git commit -m "" = okomentovat co za změny jsme provedli 
4. příkaz git push = propsání na github serverg

git pull - stažení poslední verze ze vzdáleného repozitáře na GitHubu
git diff - porovnává vybrané soubory mezi jednotlivými stromy Gitu
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

fork - kopírování souboru z github serveru jiného uživatele githubu
merge
1. pull request
2. zelené tlačítko New pull request
3. první kolonka by měla obsahovat náš nazev_uctu/repozitar_ktery_kopirujeme (např. Wolfynabp/github_trial)
4. stranka se přenačte druhé okno (compare:) vybereme co přesně chceme kopírovat (např. add_readme)
5. zmáčkneme zelené tlačítko Create pull request a pak přidat popisek
6. a znovu zelené tlačítko Create pull request
7. po jakýchkoliv úpravách případně odsouhlasení od kolegů a hlášení githubserveru, že tam neniní konflikt můžu zmáčknout tlačítko Merge pull request
8. mohu přidat komentář jinak zmáčknu commit merge
9. pokud větech nepotřebuji mohu zmáčknout delet branch