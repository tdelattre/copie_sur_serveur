# copie_sur_serveur
Script permettant la copie de fichiers écoacoustiques avec signalement sonore de la fin de copie
> nocache rsync -r --info=progress2 /media/tdelattre/2D3A-9992/* pshnas2/data/TERRAIN_2023_NAS/SESSION_HIVERNALE/S5/317/

copie de source (carte sd) vers destination (nas)

> ; ( speaker-test -t sine -f 1000 )& pid=$! ; sleep 1s ; kill -9 $pid


script permettant d'émettre un son d'une seconde à la fin de la copie



nocache rsync --recursive --info=progress2 --bwlimit=50000 -ae 'ssh -p 51022' /media/tdelattre/X10\ Pro/S4/ nom@adresse.du.serveur:DATA_2025/bats/S4/
