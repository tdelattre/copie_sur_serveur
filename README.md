# copie_sur_serveur
Script permettant la copie de fichiers écoacoustiques avec signalement sonore de la fin de copie
> rsync -r --info=progress2 /media/tdelattre/2D3A-9992/* pshnas2/data/TERRAIN_2023_NAS/SESSION_HIVERNALE/S5/317/
copue de source (carte sd) vers destination (nas)
> ; ( speaker-test -t sine -f 1000 )& pid=$! ; sleep 1s ; kill -9 $pid
script permettant d'émettre un son d'une seconde à la fin de la copie
