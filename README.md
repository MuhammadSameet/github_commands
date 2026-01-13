# github_commands

Step 1 – Apne project folder me jao
cd CoreStock_Admin

Step 2 – GitHub se saari new branches lao
git fetch

Ye command GitHub se apiintegration branch bhi le ayega.

Step 3 – Check karo ab kaunsi branches hain
git branch -a


Tumhe ye dikhega:

master
remotes/origin/master
remotes/origin/apiintegration

Step 4 – apiintegration branch ko local banao
git checkout -b apiintegration origin/apiintegration


Ab tum apiintegration branch par ho.

Step 5 – Confirm karo
git branch


Star (*) apiintegration ke aage hoga.

Ab tumhare paas dono ka code hai ✅

master → stable code

apiintegration → new API wala code

Switch karna ho:

git checkout master


ya

git checkout apiintegration
