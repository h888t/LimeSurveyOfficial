To update branches with changes from LimeSurvey (`vendor` is LimeSurvey repo
at Github, `origin` is Survos clone of it at Github):

    git checkout master
    git pull vendor master
    git push origin master
    git checkout dev
    git pull vendor dev
    git push origin dev
