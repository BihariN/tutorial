GitHub segédlet
VSC terminál - git bash (ha ninch elyen, akkor git SCM telepítése)
mkdir tutorial - make directory tutorial nevű mappa
cd tutorial/ - change directory
echo "GitHub segédlet" >> readme.md - readme.md fájl létrehozása és a szöveg beszúrása
git init - mappa inicializálása
git config --global --list - globális beálítások listázása
git remote -v - távoli repo-k cymének lekérdezése
git remote add origin https://github.com/BihariN/tutorial.git - távoli rope hazzáadása origin néven
git remote remove origin - origin nevű távoli repo eltávolitása
git add readme.md - változtatások mentése (staging)
git commit -m "first commit" - commit hozzáadása
git brach -M main - az ág átnevezésemain-re
git push -u origin main - távoli repo-ba feltölti a ...