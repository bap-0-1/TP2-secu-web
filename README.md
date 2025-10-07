 chaîne CI automatisée qui se déclenche : 
1. à chaque push sur main, 
2. et sur chaque pull request. 

 Comporte trois étapes distinctes : 

 1. Analyse SCA (Software Composition Analysis) 
Détecter les vulnérabilités dans les dépendances du projet. 
■ Exemples d’outils : Snyk, OWASP Dependency-Check, Depandabot etc 

 

2. Analyse SAST (Static Application Security Testing 
■ Identiﬁer les failles dans le code source. 
■ Exemples d’outils : Snyk Code, Semgrep, Bandi, CodeQL, . 

 

3. Analyse de Secret Scanning 
■ Rechercher d’éventuels secrets exposés (clés, mots de passe, tokens). 
■ Exemples d’outils : Gitleaks, TrufﬂeHog, GitHub Advanced Security.

Outils choisis :
1.
2.
3. TruffleHog
