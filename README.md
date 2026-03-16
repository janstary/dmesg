# dmesg

dmesg collected over the years running OpenBSD on various machines

# laptops

host	model		cpu   # freq D,I,L2,L3   C? mems  freq disk cap makej wifi	               notes

mb	MacBook Air     M1    8 3.00 128,64,4       8    12800 nvme  40 01:27 Broadcom BCM4378 (bwfm)   cam
hp7	EliteBook 820	i7    4 2.10 32,32,256,4 C3 80   12800 mSAT 128 08:30 Intel AC 7260 (iwm)       cam; fbsd
hp5	EliteBook 820	i5    4 1.90 32,32,256,4 C3 42   12800 SSD  128 09:07 Intel AC 7260 (iwm)       cam; win
t410	Thinkpad T410   i5    4 2.67 32,32,256,3 C3 44   12800 SSD  120 09:09 Intel 1000 (1T2R, iwn)    sees 4/8 ram
t420	Thinkpad T420s  i5    4 2.60 32,32,256,3 C3 44   12800 SSD  250 10:45 Intel 6205 (2T2R, iwn)    sees 4/8 ram ; win
x230	Thinkpad X230i	i3    4 2.40 32,32,256,3 C3 44   12800 SSD   60 10:25 Intel 6205 (2T2R, iwn)    sees 4/8 ram

# workstations

host	model		cpu   # freq D,I,L2,L3   C? mems  freq disk cap makej notes

box	Gigabyte H67MA	i7    8 3.70 32,32,256,8 C3 8888 12800 SSD   60 04:27 sees 4/8 ram
kancl   Gigabyte Z68MX  i5    4 3.60 32,32,256,6 C3 4424 10600 M2   128 06:14 sees 4/8 ram
bzm	HP 260 G2       i3    4 2.30 32,32,256,3 C3 84   17000 SSD   40 08:52 DDR4; wifi "Realtek 8723BE" unsupported
netbsd	MSI 7733        i3    4 2.80 256         C3      12800 SATA 300       sees 4/8 ram
freebsd	MSI 7733        i3    4 2.80 256         C3      12800 SATA 320       sees 4/8 ram
debian	MSI 7733        i3    4 2.80 256         C3      12800                sees 4/8 ram

# little boxes

rpi	Raspberry Pi4B  A72   4      48,32,1        8          uSD   32 35:20 without rpicpu.diff
www	APU 2d          412TC 4 1.00 32,32,2     C2 2          uSD   32 34:43
uvt	APU 2e          412TC 4 1.00 32,32,2     C2 2          mSATA 16 37:33
bbb	BeagleBoneBlack A8    1      32,32,256      512        uSD   32 54:17
toposym	APU1C4		T40E  2 1.00 32,32,512   C2 4          mSATA 60 55:56
stary	APU1C		T40E  2 1.00 32,32,512   C2 2          uSD   32 56:40
ppc	Mac Mini 7447A	7447  1 1.50 DD,II,512      1     3200 PATA 160 63:54 macppc (BE)
oct	Ubiquiti SG	CN50  2 0.50 16,32,128      512        USB   16 74:23 octeon (BE)
alix	ALIX 1E         Geode 1 0.50 64,64,128      256        CF    16 161:50 i386
