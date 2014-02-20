GIT-Cheatsheet
==============

Cheatsheet für reguläre GIT-Nutzung bei Schreiber &amp; Freunde

##Submodul hinzufügen
```
git submodule add UrlToGit RelativeUrlToLocalDirectory
```
Beispiel: git submodule add https://github.com/Automattic/custom-metadata.git wp-content/plugins/custom-metadata

##Alle Submodule zurücksetzen
```
git submodule foreach git reset --hard
```

##Alle Submodule aktualisieren
```
git submodule foreach git pull
```

##Submodul entfernen
```
git submodule deinit RelativeUrlToLocalDirectory
git rm RelativeUrlToLocalDirectory
```
