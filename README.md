+ git clone - копіює репозиторій(папку з файлами) на компютер
+ git branch "branchName" - створює гілку з назвою "branchName"
+ git checkout "branchName" - переходить на гілку з назвою "branchName"
+ git checkout -b "branchName" - створюємо гілку з назвою "branchName" і переходимо на неї
+ git add . - зберігаємо зміни в файлах
+ git commit -m "commit message" - підписуємо збереженні зміни в файлах
+ git push - відправляємо зміни на сайт github
+ git pull - отримуємо останні зміни з сайту github
+ git status - показуємо статус проекту
+ git branch - показуємо список гілок в проекті
+ git branch -r - показуємо список гілок на сайті github
+ git branch -a - показуємо список гілок на компютері та на сайті github
+ git fetch - отримуємо зміни з сайту github
+ git stash - зберігаємо не збережені зміни в файлах і кладемо їх в буфер обміну
+ git stash apply - вставляємо збережені зміни з буфера обміну
+ git merge "banchName" - зливаємо гілку з назвою "branchName" в поточну гілку
+ git merge --abort - відміняємо зливання гілок
+ git branch -d branchName - видаляє гілку локально з проекту
+ git push origin --delete name - видаляє гілку з сайту github
+ git diff - показує відрізки рядків між двома версіями файлу (між двома комітами) / щоб вийти з режиму перегляду історії натиcни "q" 
+ git log - показує історію комітів / щоб вийти з режиму перегляду історії натиcни "q" 
+ cd gitTutorial - переходимо в папку gitTutorial

+ відкатити main до попреднього стану можна => git log -> вибери номер потрібного коміту -> git checkout #коміта -> якщо код влаштовує то створи нову гілку git checkout -b <new-branch-name>
+ cd <name-of-folder-you-need-to-get-in>
