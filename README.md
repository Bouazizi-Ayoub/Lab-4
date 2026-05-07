# Lab-4

# Règles de sécurité et périmètre:

- Analysez uniquement des APK autorisés (fournis par l'enseignant ou générés par vos soins).
- N'utilisez pas d'applications tierces du Play Store sans autorisation explicite.
- Ne tentez pas d'exploiter des vulnérabilités découvertes.
- Travaillez uniquement avec des données fictives.
- Ce lab est strictement pédagogique et vise à comprendre les mécanismes de sécurité.

# Définitions:

- APK (Android Package) : format d'archive contenant tous les éléments d'une application Android (code,ressources,manifeste,signatures)
- DEX (Dalvik Executable) : format de bytecode utilisé par la machine virtuelle Android (Dalvik/ART)
- Manifest : fichier XML déclarant les composants, permissions et configurations d'une application Android
- Décompilation : processus de conversion du bytecode en code source lisible (approximatif)
- Obfuscation : technique visant à rendre le code difficile à comprendre (renommage de variables, restructuration)
- Exported : attribut indiquant si un composant Android est accessible depuis d'autres applications
- Signature : mécanisme cryptographique garantissant l'intégrité.


# Task 1 — Préparer le workspace et vérifier l'APK

# Vérifiez que l'APK est bien une archive ZIP :


<img width="534" height="47" alt="image" src="https://github.com/user-attachments/assets/e443da68-b09f-4b44-9e06-57befe99401e" />


# Listez le contenu de l'APK :



<img width="590" height="289" alt="image" src="https://github.com/user-attachments/assets/2e6c464e-9298-4ceb-ae76-9fb4fa0ab1e7" />



# Calculez le hash de l'APK pour traçabilité :



<img width="718" height="38" alt="image" src="https://github.com/user-attachments/assets/69d12a94-2ea6-4650-bf45-ddb539eeebcd" />





# Vérifiez la signature de l'APK :




<img width="664" height="307" alt="image" src="https://github.com/user-attachments/assets/2baf1ba2-12ee-4807-b73d-4a8bf9037546" />



# Task 3 — Analyse avec JADX GUI (20-30 min)



# resources/AndroidManifest.xml:



<img width="850" height="463" alt="image" src="https://github.com/user-attachments/assets/b4f4779d-5b55-4be1-8a80-e184f542e26a" />





# resources/res/values/strings.xml:



<img width="1010" height="211" alt="image" src="https://github.com/user-attachments/assets/258df1fc-ab27-48c3-a017-bd180f4b8afb" />



# L analyse du Manifest:



<img width="642" height="436" alt="image" src="https://github.com/user-attachments/assets/d59dee03-82e2-4501-9830-3d6509adffb2" />



# Task 6 — Comparaison JADX vs JD-GUI



<img width="243" height="389" alt="image" src="https://github.com/user-attachments/assets/06a448fa-d9b3-4fc4-89d2-c9de77fbdf7a" />


