P4-Project-report-latex
=======================
## Lige nogle tommelfingerregler at huske ##

* **DO NOT TOUCH ANYTHING WHEN IN DA MASTER BRANCH!**
* Når du laver en ny branch:
 * Skift først til masteren (i GitHub app'en)
 * Sync den så du får de nyeste opdateringer
 * Lav derefter en ny branch
* Er du færdig med en opgave på din branch, så giv besked og lav derefter en ny branch, hvis du vil gå igang med nyt (hvorfor? se "Gør merging nemmere")
* LAD VÆRE MED AT SLETTE BRANCHES SELV! i stedet...
 * Skift til master-branchen (i app'en)
 * Åben git-shell (tryk på tandhjulet og vælg "Open a shell here")
 * Skriv følgende (uden citations-tegn): <br>
   "git fetch" - tryk enter <br>
   "git remote prune origin" - tryk enter <br>
 * Tilbage i app'en: <br>
   Tryk pil tilbage (oppe i venstre hjørne) <br>
   Tryk refresh i toppen - vent <br>
   Gå nu ind på repositoriet og se at gamle branches nu burde være forsvundet

### Gør merging nemmere ###
Jo færre filer du ændrer på i en branch jo nemmere vil det være at merge den ind i masteren. Specielt vil det være en dårlig idé både at lave nyt arbejde (starte nyt kapitel) og derfter rette stavefejl mv. i en andens arbejde. Hvis to sidder i hver deres branch og ændrer på de samme steder i samme filer, vil det give problemer når begge skal merges ind i masteren.

**Bottom line:** Del opgaverne så meget op så længe det er logisk og lav hver opgave i en ny branch (giv evt. hver branch et navn der indikerer hvem der arbejder på den og hvad der bliver arbejdet på)
