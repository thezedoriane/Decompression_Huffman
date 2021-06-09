# Decompression_Huffman
Ce programme est écrit en java.
Il permet de décompresser des fichiers .bin par la méthode d'Huffman.

Pour être utilisé il est nécessaire de posséder la fichier .bin que l'on souhaite décompresser, et un fichier .txt contenant à la première ligne le nombre de caractères différents, et pour chacune des lignes suivantes un caractère utilisé et son nombre d'occurence, séparé par un espace. Dans le fichier .txt, les caractères doivent être triés par odre croissant d'occurrence et selon leur code ascii. C'est à dire qu'après avoir été trié par fréquence, pour les caractères ayant même fréquence ils doivent être trié selon leur code ascii.
Ces deux fichiers doivent se situés à la racine du programme, par exemple pour les utilisateurs d'eclipse il doivent être placés dans le fichier : .../eclipse-workspace/Nom_du_projetjava .

Pour éxécuter ce programme dans le code du fichier "Execution", dans la classe Test, il faut indiquer le nom des fichiers comme indiqué à la ligne 6.
