# latex_page_garde
Page de garde UBL avec Latex

POUR UTILISER LA PAGE DE GARDE UDBL, UTILISER DANS VOTRE FICHIER DE TRAVAIL
1. TELECHARGE SUR LE GITHUB, LE PROJET DANS VOTRE DOSSIER DE TRAVAIL
2. INCLURE LE FICHIER A VOTRE PROJET COMME INDIQUE CI-DESSOUS
        \documentclass{artcle}
        \usepackage[utf8]{inputenc}
        \usepackage[left=2cm, right=2cm, top=2cm, bottom=2cm]{geometry}
        \usepackage{ragged2e}
        \usepackage{graphicx}
        \usepackage{url}

        \input{latex_page_garde/page_garde}
        \begin{document}
           Mon document .........
        \end{document}
3. UTILISER LA COMMANDE SUIVANTE DANS VOTRE TRAVAIL EN SUIVANT LA SYNTAXE SUIVANTE :
     \pagedegardeudbl{TITRE DU DOCUMENT}
                     {NOM DE L'AUTEUR}
                     {NOM DU DIRECTEUR}
                     {NOM DU CO-DIRECTEUR}
                     {NOM DE LA FILIERE ET PROMOTION}
4. VOICI L'EXEMPLE FINAL ET COMPLET

 

          \documentclass{book}
          \usepackage[utf8]{inputenc}
          \usepackage[left=2cm, right=2cm, top=2cm, bottom=2cm]{geometry}
          \usepackage{ragged2e}
          \usepackage{graphicx}
          \usepackage{url}
          
          \input{latex_page_garde/page_garde}
          \begin{document}
             \pagedegardeudbl{Migration de la telephonie classique vers la ToIP}
                             {André MUTOKE}
                             {Emile MUTOKE}
                             {Baudouin BANZA}
                             {L4 TLC et Reseaux}
          \end{document}
