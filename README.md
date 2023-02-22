# OSD_Openrisc_or1k_Unamiga_CYC1000

First to thank to Edu Arana and Neuro to still mantain a repository with the OSD openrisc:

Primero agradecer que tanto Neuro y Edu Arana, pusieran a disposición los fuentes del OSD:

https://github.com/neurorulez/UnAmigaOsd

The problems that arise at this commmon core is that the core is programed allways as 32Mbytes at base.
But an inner work for CYC1000 could be done.


The minimig core uses his own soc risc processor in order to deal with the OSD.

This risc procesors are first used in TERASIC DE1, and is a family of a mips32 ork1000 or or1200.

El core de minimig usa para el desempeño del OSD un core libre que implementando un mips de 32bits, dependiendo de la elección un or1000 o un or1200 el orxxxx significa openrisc.

The first Minimig core that uses the or1k:

El primer Minimig core que sepa que use este openrisc para el OSD es:

https://github.com/rkrajnc/minimig-de1


The opencore for or1k:

El core libre open risc:

https://opencores.org/projects/or1k/


With a revision of the OSD to meet the requirements of the CYC1000 8MBX16BIT with a fast accesss sdram, The core unamiga could do better and could have more optimized memory scheme.


Entre la parte del OSD y la parte del core unamiga del cual disfruta en CYC1000 con la placa de entradas y salidas ATLAS se podría obtener un mejor aprovechamiento de los 8Mbytes que dispone la CYC1000.

Manual or1k;
https://openrisc.io/or1k.html

Acronimos:
OSD -> On Screen Display.

E/S -> Entradas/Salidas.

I/O -> Input/Output.

CYC1000 -> https://shop.trenz-electronic.de/en/Products/Trenz-Electronic/CYC1000-Intel-Cyclone-10/ .

or1k -> Open Risc processor 1000 or 1200 a mips32 cpu.


