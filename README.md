# Podstawy-poruszania-sie-w-GIT
lab3
# Podstawy poruszania się w GIT
 lab3
Główny:
Wprowadzenie:
#zad1
git commit
git commit

#zad2
git branch bugFix
git checkout bugFix

#zad3
git branch bugFix
git checkout bugFix
git commit
fit checkout main
fit commit
git merge bugFix

#zad4
git branch bugFix
git checkout bugFix
git commit
git checkout main
git commit
git checkout bugFix
git rebase main

Rozkręcenie:
#zad1
git checkout c4

#zad2
git checkout c4
git checkout HEAD^

#zad3
git checkout c6
git branch -f main HEAD
git checkout main~3
git branch -f bugFix HEAD~1

#zad4
git reset local~1
gir checkout pushed
git revert pushed

Przenoszenie pracy:
#zad1
git cherry-pick c3
git cherry-pick c4 c7

#zad2
git rebase -i HEAD~3
git branch -f main HEAD

Po trochu wszystkiego:
#zad1
git rebase -i HEAD~2
git commit --amend
git rebase -i HEAD~2
git branch -f main caption

#zad2
git checkout main~
git cherry-pick c2
git branch -f main HEAD~1
git cherry-pick c2
git cherry-pick c3

#zad3
git tag v0 c1
git tag v1 c2
git checkout v1

#zad4
git describe main
git describe side
git describe v1
git describe
git describe c5
git commit

#zad5
git rebase main bugFix
git checkout side
git rebase -i HEAD~3
git rebase bugFix side
git rebase side another
git branch -f main

Tematy zaawansowane:
#zad1
git rebase main bugFix
git rebase bugFix side
git rebase side another
git rebase another main

#zad2
git branch bugWork main^^2^

#zad3
git checkout one
git cherry-pick C4 C3 C2
git checkout two
git cherry-pick C5 C4 C3 C2
git branch -f three C2

#__________________________________________
Zdalny:
Push & Pull -- Zdalne repozytoria:
#zad1
git clone

#zad2
git commit 
git checkout o/main
git commit

#zad3
git fetch

#zad4
git pull

#zad5
git clone
git fakeTeamwork 2
git commit
git pull

#zad6
git commit
git push
git commit
git push

#zad7
git clone
git fakeTeamwork
git commit
git pull --rebase
git push

#zad8
git reset --hard o/main
git checkout -b feature C2
git push origin feature

Do źródła i dalej -- zaawansowane zdalne repozytoria:
#zad1
git fetch
git rebase o/main side1
git rebase side1 side2
git rebase side2 side3
git rebase side3 main
git push

#zad2
git checkout main
git pull
git merge side1
git merge side2
git merge side3
git push

#zad3
git checkout -b side o/main
git commit
git pull --rebase
git push

#zad4
git push origin main
git push origin foo

#zad5
git push origin main^:foo
git push origin foo:main

#zad6
git fetch origin main~1:foo
git fetch origin foo:main
git checkout foo
git merge main

#zad7
git push origin :foo
git fetch origin :bar

#zad8
git pull origin bar:foo
git pull origin main:side
