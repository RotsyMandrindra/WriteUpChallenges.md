# WriteUpChallenges.md

1° FTP - Authentification : Filtrer les paquets par FTP:

    11	7.639420	10.20.144.150	10.20.144.151	FTP	81	Request: PASS *******
    

2° TELNET - Authentification : Filtrer par telnet:

    login: .."........"ffaakkee

    . Password:user . Last login: Thu Dec 2 21:32:59 on ttyp1 from bam.zing.org
    

3° Ethernet Trame : convertion du code hexadécimal en chaîne de caractères:

    xxd -r -p ch12.txt
    
    xxd : convertir un chaîne de caractères en hexadécimal.
    xxd -r : convertir un hexadécimal en chaîne de caractères.
    -p : supprimer les espaces dans le code hexadécimal.

    echo Password== | base64 -d
    
    
4° Twitter- Authentification :

    echo Password== | base64 -d
    

5° Bluetooth - Fichier inconnu :

    Crypter le code : 0C:B3:19:B9:4F:C6GT-S7390G via le site https://www.sha1.fr/
    Mot de passe obtenu : c1d0349c153ed96fe2fadf44e880aef9e69c122b 
