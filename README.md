 chaîne CI automatisée qui se déclenche : 
1. à chaque push sur main, 
2. et sur chaque pull request. 

 Comporte trois étapes distinctes : 

1. Analyse SCA (Software Composition Analysis) 
■ Détecter les vulnérabilités dans les dépendances du projet. 

2. Analyse SAST (Static Application Security Testing 
■ Identiﬁer les failles dans le code source. 

3. Analyse de Secret Scanning 
■ Rechercher d’éventuels secrets exposés (clés, mots de passe, tokens). 

Outils choisis :
1. OWASP Dependency Checker
2. Semgrep
3. TruffleHog
