# OSD_Openrisc_or1k_Unamiga_CYC1000

The minimig core uses his own soc risc procesor in order to deal with the OSD.

This risc procesors are first used in DE1, and is a family of a mips32 ork1000 or or1200.

El core de minimig usa para el desempeño del OSD un core libre que implementa un mips de 32bits, dependiendo de la elección un or1000 o un or1200 el orxxxx significa openrisc.

The first Minimig core that uses the or1k:
El primer Minimig core que sepa que use este openrisc para el osd es:

https://github.com/rkrajnc/minimig-de1


The opencore for or1k:
El core libre open risc:

https://opencores.org/projects/or1k/


With a revision of the OSD to meet the requirements of the CYC1000, The core unamiga could do better and could have more optimized memory schemes.


Entre la parte del osd y la parte del core unamiga del cual disfruta en cyc1000 con la placa de entradas y salidas ATLAS se podría obtenner un mejor aprovechamiento de los 8Mbytes que dispone la CYC1000.

