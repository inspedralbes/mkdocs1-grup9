# mkdocs1-grup9
mkdocs1-grup9 created by GitHub Classroom

## Integrants del grup:
Oscar Leal

Yenifer Wu Zhang

## Com hem fet la pràctica?
1. Primer de tot, crearem un nou repositori al github.com, ens ho connectem  
2. Després, farem un git clone del url del github per poder baixar els documents
3. Una vegada fet el git clone, farem un commit i push de la carpeta mkdocs.
4. Per crear la carpeta mkdocs -> mkdocs new nom_carpeta i ens ho conectem amb una màquina virtual amb puTTy.
5. Quan fem el push, els altres integrants del repositori podran fer el git clone i git pull.
6. A partir d'aqui treballarem de manera que a l'hora de fer els commits i push, no ens doni conflictes 
7. Per veure com ha quedat la pàgina web de mkdocs hem de posar la comanda $mkdocs serve -a 0.0.0.0:8000
8. I ens ho connectem amb el navegador de la màquina local posant el ip de la màquina virtual IP_MAQUINA_VIRTUAL:8000
9. Una vegada comprovat hem acabat tot, farem $mkdocs build -d /var/www/html i tindrem la pagina muntada ja en el servidor apache
