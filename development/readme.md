# Wangan Midnight Maximum Tune 6
## Modding Reference Tool
### Created by Damon M [@SirScrubbington](https://www.twitter.com/SirScrubbington)

### Table of Contents
* [Introduction](#introduction)
* [Hex Indexes](#hexindexes)
* [Hex Values](#hexvalues)

### Introduction
Hello! I'm Damon, and I've been working on a save editing tool for Maximum Tune 6 on 
Teknoparrot and JConfig. The following document shows the indexes of where data is stored
in Maximum Tune 6 saves, as well as some of the hex values for different properties
such as car ids, aero kits, license plate designs etc. 

### Hex Indexes

### Hex Values 

|  Offset  | 00 | 01 | 02 | 03 | 04 | 05 | 06 | 07 | 08 | 09 | 0A | 0B | 0C | 0D | 0E | 0F | 
| -------- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | 
| 00000010 | | | | | | | | | | | | | | | | |
| 00000020 | | | | | | | | | | | | | | | | |
| 00000030 | | | | | Car ID| | | | Car Colour | | | | | | | |
| 00000040 | Rims | | | | Rims Colour | | | | Body Kit | | | | Hood | | | |
| 00000050 | | | | | | | | | Wing | | | | Mirror | | | |
| 00000060 | Neon | | | | Trunk | | | | Plate Frame | | | | Plate Frame Colour | | | |
| 00000070 | Plate Number | Plate Number | | | Power | | | | | | | | | | | |
| 00000080 | Handling | | | | Car Rank | | | | | | | | | | | |
| 00000090 | Sticker Type | | | | | | | Sticker ID | | | | | | | | |
| 000000A0 | Title | Title | Title | Title(?) | | | | | | | | | | | | |
| 000000B0 | | | | | | | | | | | | | | | | |
| 000000C0 | | | | | | | | | | | | | | | | |
| 000000D0 | | | | | | | | | | | | | | | | |

#### Car Indexes
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 86 | ACURA New NSX (ACURA) |
| 87 | ACURA NSX (ACURA) |
| 6D | Audi R8 5.2 FSI quattro [R8] |
| 6E | Audi RS 4 Avant [RS4] |
| 73 | BMW 2002 TURBO [2002] |
| 69 | BMW M1 [E26] |
| 65 | BMW M3 [E92_MAT] |
| 52 | BMW M3 [E92] |
| 6A | BMW M3 CSL [E46] |
| 72 | BMW M6 Gran Coupe [M6] |
| 7A | BMW MINI Cooper S Crossover [R60] |
| 64 | BMW Z4 S DRIVE 35is [E89P] |
| 51 | BMW Z4 S DRIVE 35is [E89] |
| 66 | CHEVROLET CAMARO SS RS [CAMAROT] |
| 03 | CHEVROLET CAMARO SS RS [CAMARO_MAT] |
| 02 | CHEVROLET CAMARO SS RS [CAMARO] |
| 53 | CHEVROLET Camaro Z28 [Z28] |
| 54 | CHEVROLET Corvette STING RAY [C2] |
| 04 | CHEVROLET CORVETTE Stingray [C3] |
| 01 | CHEVROLET ZR1 [ZR1T] |
| 00 | CHEVROLET ZR1 [ZR1] |
| 70 | Dodge Charger SRT8 [SRT8] |
| 6F | Dodge Viper SRT10 [SRT10] |
| 88 | HONDA INTEGRA TYPE R [DC2] |
| 7F | HONDA New NSX [NC1] |
| 80 | HONDA NSX [NA1] |
| 81 | HONDA NSX-R [NA2] |
| 83 | HONDA S2000 [AP2] |
| 82 | HONDA S660 [JW5] |
| 7B | Lamborghini Aventador LP700-4 [LP700] |
| 7C | Lamborghini Countach LP400 [LP400] |
| 7E | Lamborghini Diablo VT [DIABLO] |
| 7D | Lamborghini Miura P400S [P400S] |
| 0D | MAZDA COSMO SPORT <110S> [L10B] |
| 09 | MAZDA EUNOS COSMO TYPE|S [JCESE] |
| 55 | MAZDA EUNOS ROADSTER <MX-5> [NA6CE] |
| 0B | MAZDA MAZDASPEED ATENZA [GG3PS] |
| 0A | MAZDA MAZDASPEED ATENZA [GG3P] |
| 74 | MAZDA ROADSTER ND [ND5RC] |
| 89 | MAZDA ROADSTER ND RF [NDERC] |
| 05 | MAZDA ROADSTER RS RHT [NCEC] |
| 06 | MAZDA RX-7 Type R [FD3S] |
| 08 | MAZDA RX-8 Type S [SE3P] |
| 56 | MAZDA SAVANNA GT <RX-3> [S124A] |
| 07 | MAZDA SAVANNA RX-7 <RX-7 GT-X> [FC3S] |
| 0C | MAZDA SAVANNA RX-7 TURBO SE | Limited [SA22] |
| 6C | Mercedes-Benz 190E 2.5-16 Evolution2 [W201] |
| 57 | Mercedes-Benz 500E [W124] |
| 67 | Mercedes-Benz SLK 350 BlueEFFICIENCY [R172P] |
| 58 | Mercedes-Benz SLK 350 BlueEFFICIENCY [R172] |
| 6B | Mercedes-Benz SLS AMG [C197] |
| 59 | MITSUBISHI GALANT VR-4 [E39A] |
| 18 | MITSUBISHI GTO TWIN TURBO [Z16A] |
| 16 | MITSUBISHI LANCER Evolution III GSR [CE9A_GSR] |
| 17 | MITSUBISHI LANCER Evolution III RS [CE9A_RS] |
| 0F | MITSUBISHI LANCER Evolution IX MR GSR [CT9A9_MR] |
| 14 | MITSUBISHI LANCER Evolution V GSR [CP9A5_GSR] |
| 15 | MITSUBISHI LANCER Evolution V RS [CP9A5_RS] |
| 13 | MITSUBISHI LANCER Evolution VI GSR [CP9A6_GSR] |
| 12 | MITSUBISHI LANCER Evolution VI RS [CP9A6_RS] |
| 10 | MITSUBISHI LANCER Evolution VIII MR GSR [CT9A8_GSR] |
| 11 | MITSUBISHI LANCER Evolution VIII MR RS [CT9A8_RS] |
| 0E | MITSUBISHI LANCER EvolutionX GSR [CZ4A] |
| 1A | MITSUBISHI PAJERO EVOLUTION [V55W] |
| 19 | MITSUBISHI STARION GSR|VR [A187A] |
| 29 | NISSAN 180SX TYPEIII [RPS13] |
| 27 | NISSAN FAIRLADY Z [S30] |
| 25 | NISSAN FAIRLADY Z 300ZX [Z31 / Z31ANIV] |
| 24 | NISSAN FAIRLADY Z 300ZX [Z32] |
| 77 | NISSAN FAIRLADY Z NISMO [Z34N] |
| 8B | NISSAN FAIRLADY Z S130 [GS130] |
| 22 | NISSAN FAIRLADY Z Version ST [Z34] |
| 23 | NISSAN FAIRLADY Z VersionS [Z33] |
| 2B | NISSAN FUGA 370GT Type S [Y51] |
| 5A | NISSAN GLORIA Gran Turismo ULTIMA [Y33] |
| 1B | NISSAN GT-R [BNR35] |
| 84 | NISSAN GT-R MC [BNR35MC] |
| 76 | NISSAN GT-R NISMO [BNR35N] |
| 1C | NISSAN GT-R SpecV [BNR35V] |
| 75 | NISSAN LAUREL 25 CLUB|S [C35] |
| 8A | NISSAN LEOPARD Ultima [UF31] |
| 85 | NISSAN SILVIA K| s [PS13] |
| 28 | NISSAN SILVIA spec DR [S15] |
| 2A | NISSAN SKYLINE COUPE 370GT Type S [CV36] |
| 20 | NISSAN SKYLINE GT-R [BNR32] |
| 21 | NISSAN SKYLINE GT-R [KPGC10] |
| 1F | NISSAN SKYLINE GT-R Vspec [BCNR33] |
| 1D | NISSAN SKYLINE GT-R VspecII [BNR34] |
| 1E | NISSAN SKYLINE GT-R VspecII nur [BNR34_NUR] |
| 5B | NISSAN SKYLINE RS X [R30] |
| 5C | NISSAN STAGEA Autech Version 260RS [WC34] |
| 90 | PORSCHE 718 CAYMAN S [718CS] |
| 8F | PORSCHE 928GT [928GT] |
| 8C | PORSCHE 930 911 Turbo S [930TS] |
| 8D | PORSCHE 964 911 Turbo 3.6 [964T36] |
| 8E | PORSCHE 991 911 Turbo S [991TS] |
| 2C | RUF CTR [R964] |
| 78 | RUF RCT [RCT] |
| 2D | RUF RGT [R997] |
| 2E | RUF RK coupe [RKC] |
| 5D | RUF Rt35 [R991] |
| 36 | SUBARU ALCYONE SVX Version L [CXD] |
| 5F | SUBARU BRZ [ZC6] |
| 31 | SUBARU IMPREZA WRX Sti [GDB] |
| 30 | SUBARU IMPREZA WRX STI [GDBF] |
| 2F | SUBARU IMPREZA WRX STI [GRB] |
| 32 | SUBARU IMPREZA WRX Sti specC Limited [GDB_C] |
| 34 | SUBARU IMPREZA WRX Sti VersionVI [GC8] |
| 33 | SUBARU IMPREZA WRX typeRA Sti VersionVI [GC8_RA] |
| 35 | SUBARU LEGACY B4 2.0GT spec DB [BL5] |
| 38 | SUBARU LEGACY B4 2.5GT S Package [BM9] |
| 71 | SUBARU LEVORG [VMG] |
| 37 | SUBARU R2 [RC2] |
| 5E | SUBARU WRX STI [GVB] |
| 50 | TOYOTA 2000GT [MF10_MAT] |
| 4F | TOYOTA 2000GT [MF10] |
| 61 | TOYOTA 86 GT [ZN6] |
| 48 | TOYOTA ARISTO V300 VERTEX EDITION [JZS161T] |
| 47 | TOYOTA ARISTO V300 VERTEX EDITION [JZS161] |
| 4E | TOYOTA CELICA SUPRA [MA61_US] |
| 42 | TOYOTA CELSIOR [UCF10T/_V1/_V2/_V3/_V4] |
| 3D | TOYOTA CELSIOR [UCF10/_V1/_V2/_V3/_V4] |
| 3C | TOYOTA CHASER Tourer V [JZX100] |
| 49 | TOYOTA COROLLA [NZE121] |
| 4C | TOYOTA CROWN ATHLETE [GRS204] |
| 68 | TOYOTA HIACE VAN [KDH201VH] |
| 62 | TOYOTA HIACE VAN [KDH201V] |
| 4B | TOYOTA HIACE WAGON [KZH100GH] |
| 4A | TOYOTA HIACE WAGON [KZH100G] |
| 79 | TOYOTA MARKII TOURER V [MARK2] |
| 3B | TOYOTA MR2 GT-S [SW20] |
| 60 | TOYOTA SOARER 2.5GT-TWIN TURBO [JZZ30] |
| 4D | TOYOTA SPRINTER TRUENO GT APEX [AE86] |
| 3A | TOYOTA SUPRA 2.5GT TWIN TURBO R [JZA70] |
| 39 | TOYOTA SUPRA RZ [JZA80] |

#### Aero Kits
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 | Stock |
| 01 | Aero Set I (New) | 
| 02 | Aero Set J (New) | 
| 03 | Aero Set K (New) | 
| 04 | Aero Set A |
| 05 | Aero Set B |
| 06 | Aero Set C |
| 07 | Aero Set D |
| 08 | Aero Set E |
| 09 | Aero Set F |
| 0A | Aero Set G |
| 0B | Aero Set H |

#### Rear Wings
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 | Stock Wing |
| 01 | GT Wing Straight |
| 02 | Exclusive Wing A |
| 03 | GT Wing 3D |
| 04 | Exclusive Wing B |
| 05 | GT Wing Twin |
| 06 | GT Wing 3D 2 |
| 07 | Exclusive Wing C |
| 08 | GT Wing Swan |
| 09 | No Wing |

#### Car Hoods
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 | Stock |
| 01 | FRP Bonnet A |
| 02 | FRP Bonnet B |
| 03 | FRP Bonnet C |
| 04 | Original Style Bonnet (Carbon) |
| 05 | Carbon Bonnet (with duct 1) |
| 06 | Carbon Bonnet (with duct 2) |
| 07 | Carbon Bonnet (with duct 3) |
| 08 | FRP Bonnet D |

#### Mirrors
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 | Stock |
| 01 | Aero Mirror |
| 02 | Carbon Aero Mirror | 

#### Trunks
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 | Stock |
| 01 | Carbon Trunk | 

#### Neons
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 | No Neon |
| 01 | Green |
| 02 | Blue |
| 03 | Red |
| 04 | Yellow |
| 05 | Purple |
| 06 | Green Tribal |
| 07 | Blue Tribal |
| 08 | Red Tribal |
| 09 | Yellow Tribal |
| 10 | Purple Tribal | 

#### Plate Frames
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 00 | Stock | 
| 01 00 | Blue YM Speed |
| 01 01 | Purple MACH |
| 01 02 | Pink RGO |
| 01 03 | White Garage ACE |
| 01 04 | Red R200 Club |
| 01 05 | Silver FLAT |
| 01 06 | Black Bird |
| 01 07 | Yellow ZERO |
| 01 08 | Green Auto |
| 01 09 | Light Blue GT Cars |
| 02 00 | Black with Red Stripe |
| 02 01 | Black with Orange Stripe |
| 02 02 | Black with Yellow Stripe |
| 02 03 | Black with Green Stripe |
| 02 04 | Black with Purple Stripe |
| 02 05 | Black with Light Blue Stripe |
| 02 06 | Black with Dark Blue Stripe |
| 02 07 | Black with White Stripe |
| 03 00 | White Light Surround (Left, Right, Top, Bottom) |
| 04 00 | Green Light (Left Right Only) |
| 04 01 | Blue |
| 04 02 | Purple |
| 04 03 | Pink |
| 04 04 | Yellow | 

#### Districts
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 | Blank |
| 01 | Hokkaido |
| 03 | Iwate |
| 05 | Akita |
| 10 | Toyama |
| 28 | Fukuoka |
| 0D | Tokyo |
| 0E | Kanagawa |
| 2F | Okinawa | 

#### Rims
##### Credits: Discord TGR24#7257

| Hex Code | Value | 
| -- | ----------- |
| 00 | Stock |
| 0A | Yokohama Model T5 (T5) |
| 0B | Watanabe Eight Spoke (EIGHT) |
| 0C | Watanabe Forged Mg Cyclone (CYCL) |
| 0D | Watanabe Stellar (STEL) |
| 0E | Watanabe GR-8 |
| 0F | Watanabe New RS8 (RS8) |
| 01 | Yokohama Advan Racing RCIII (RC3) |
| 02 | Yokohama Advan Racing TCIII (TC3) |
| 03 | Yokohama Super Advan Racing ver.2 |
| 04 | Yokohama Advan Racing RG-D2 (RGD2) |
| 05 | Yokohama Advan Racing RGIII (RG3) |
| 06 | Yokohama Advan Racing RSII (RS2) |
| 07 | Yokohama Advan Racing RS-D (RSD) |
| 08 | Yokohama AVS Model T6 |
| 09 | Yokohama Advan Racing GT (ARGT) |
| 10 | Rays VR CE28N (CE28) |
| 11 | Rays Gram Lights 57ANA (57ANA) |
| 12 | Rays Lucianna Stratagia (LUCI) |
| 13 | Rays Gram Lights 57D (57D) |
| 14 | Rays VR TE37 Saga (37SAGA) |
| 15 | Rays VR TE037 DURA (37DURA) |
| 16 | Rays VR GT-Type M (GTM) |
| 17 | Rays Gabbana (GABB) |
| 18 | Rays VR RE30 (RE30) |
| 19 | Rays Gram Lights 57F (57F) |
| 1A | Rays 57 Accelerate (57AC) |
| 1B | Rays ZE40 (ZE40) |
| 1C | (Unknown) |
| 1D | Enkei Racing RPF1 (RPF1) |
| 1E | Enkei Racing Revolution NT03R (NT03RR) |
| 1F | Enkei WPS JL01 |
| 20 | Enkei Racing RS05 (RS05) |
| 21 | Enkei Racing JS+M |
| 22 | Enkei ES-TARMAC (TARMAC) |
| 23 | Enkei Performance Line PF07 |
| 24 | (Unknown) |
| 25 | OZ Crono 3 |
| 26 | OZ Rally Racing (RR) |
| 27 | OZ ForgiataGT (ForGT) |
| 28 | OZ Leggenda (LEGG) |
| 29 | OZ Superturismo LM (SUPE) |
| 2A | OZ Formula HLT |
| 2B | OZ Zeus HLT Forged (ZEUS) |
| 2C | OZ Torino (TRIN) |
| 2D | OZ Versilia (VERS) |
| 2E | OZ Ultraleggera (ULEG) |
| 2F | BBS RI-D |
| 30 | BBS RI-A |
| 31 | BBS FS |
| 32 | BBS RG-R |
| 33 | BBS Super-RS (SRS) |
| 34 | BBS RI-D |
| 35 | BBS LM |
| 36 | BBS FZ-MG |
| 37 | Yokohama Advan Racing RG-D (RGD) |
| 38 | Yokohama Advan Racing TC II (TC2) |
| 39 | Yokohama Racing Model T7 (T7) |
| 3A | (Unknown) |
| 3B | Yokohama Advan Racing RSII |
| 3C | Yokohama Advan Racing RZ |
| 3D | Yokohama AVS Model T6 (T6) |
| 3E | Enkei Racing RS+M |
| 3F | (Unknown) |
| 40 | Yokohama Kreutzer Vi |
| 41 | Yokohama Advan Racing RZ-DF (RZDF) |
| 42 | Yokohama Advan Model F50 (F50) |
| 43 | Rays VR TE37 (TE37) |
| 44 | Rays GT Type C |
| 45 | Rays BL-10-SX |
| 46 | Rays Shotgun (SHOT) |
| 47 | Rays X401 (X401) |
| 48 | (Unknown) |
| 49 | Rays 77NTL (77NTL) |
| 4A | Rays G10 (G10) |
| 4B | Rays SPR-EX |
| 4C | Rays F2B |
| 4E | (Unknown) |
| 4F | Rays Arpione (ARPI) |
| 50 | Rays V350 (V350) |
| 51 | (Unknown) |
| 52 | Rays Scudo (SCUD) |
| 53 | (Unknown) |
| 54 | Rays Homura 2X8GT | 

#### Power
##### Credits: Myself

| Hex Code | Value | 
| -- | ----------- |
| 00 | 0 Points (Stock) |
| 01 | 1 Point (360 HP) |
| 02 | 2 Points | 
| 03 | 3 Points | 
| 04 | 4 Points | 
| 05 | 5 Points | 
| 06 | 6 Points | 
| 07 | 7 Points | 
| 08 | 8 Points | 
| 09 | 9 Points |
| 0A | 10 Points (600 HP) |
| 0B | 11 Points (620 HP) |
| 0C | 12 Points (640 HP) |
| 0D | 13 Points (660 HP) |
| 0E | 14 Points (680 HP) |
| 0F | 15 Points (700 HP) |
| 10 | 16 Points (720 HP) |
| 11 | 17 Points (740 HP) |
| 12 | 18 Points (760 HP) |
| 13 | 19 Points (780 HP) |
| 14 | 20 Points (800 HP) |
| 15 | 21 Points (815 HP) |
| 16 | 22 Points (830 HP) |
| 17 | 23 Points (835 HP) |
| 18 | 24 Points (840 HP) | 

#### Handling
##### Credits: Myself

| Hex Code | Value | 
| -- | ----------- |
| 00 | 0 Points (Stock) |
| 01 | 1 Point |
| 02 | 2 Points | 
| 03 | 3 Points | 
| 04 | 4 Points | 
| 05 | 5 Points | 
| 06 | 6 Points | 
| 07 | 7 Points | 
| 08 | 8 Points | 
| 09 | 9 Points |
| 0A | 10 Points |
| 0B | 11 Points |
| 0C | 12 Points |
| 0D | 13 Points |
| 0E | 14 Points |
| 0F | 15 Points |
| 10 | 16 Points |
| 11 | 17 Points |
| 12 | 18 Points |
| 13 | 19 Points |
| 14 | 20 Points |
| 15 | 21 Points |
| 16 | 22 Points |
| 17 | 23 Points |
| 18 | 24 Points | 

#### Rank
##### Credits: Myself

| Hex Code | Value | 
| -- | ----------- |
| 01 | N | 
| 02 | C9 | 
| 03 | C8 | 
| 04 | C7 | 
| 05 | C6 | 
| 06 | C5 | 
| 07 | C4 | 
| 08 | C3 | 
| 09 | C2 | 
| 0A | C1 | 
| 0B | B9 | 
| 0C | B8 | 
| 0D | B7 | 
| 0E | B6 | 
| 0F | B5 | 
| 10 | B4 | 
| 11 | B3 | 
| 12 | B2 | 
| 13 | B1 | 
| 14 | A9 | 
| 15 | A8 | 
| 16 | A7 | 
| 17 | A6 | 
| 18 | A5 | 
| 19 | A4 | 
| 1A | A3 | 
| 1B | A2 | 
| 1C | A1 | 
| 1D | S9 | 
| 1E | S8 | 
| 1F | S7 | 
| 20 | S6 | 
| 21 | S5 | 
| 22 | S4 | 
| 23 | S3 | 
| 24 | S2 | 
| 25 | S1 | 
| 26 | SS9 | 
| 27 | SS8 | 
| 28 | SS7 | 
| 29 | SS6 | 
| 2A | SS5 | 
| 2B | SS4 | 
| 2C | SS3 | 
| 2D | SS2 | 
| 2E | SS1 | 
| 2F | SSS9 | 
| 30 | SSS8 | 
| 31 | SSS7 | 
| 32 | SSS6 | 
| 33 | SSS5 | 
| 34 | SSS4 | 
| 35 | SSS3 | 
| 36 | SSS2 | 
| 37 | SSS1 | 
| 38 | SSSS | 

#### Sticker Type
##### Credits: 

| Hex Code | Value | 
| -- | ----------- |
| 00 | None | 
| 01 | Used | 

#### Sticker IDs
##### Credits: 

| Hex Code | Value | 
| -- | ----------- |
| 00 | None |
| 01 | Fire Pattern |
| 02 | Fire Pattern 2 | 
| 03 | Circle | 
| 04 | Circle 2 | 
| 05 | Triangle | 
| 06 | Spear | 
| 07 | Snake | 
| 08 | Bat | 
| 09 | Star | 
| 0A | Shooting Star | 
| 0B | Thunder Volt | 
| 0C | Illumination | 
| 0D | Arrow | 
| 0E | Tribal | 
| 0F | Tribal 2 | 
| 10 | Tramp | 
| 11 | Tramp 2 | 
| 12 | Heart | 
| 13 | Angel Heart |
| 14 | Raibun | 
| 15 | Plum Cloud | 
| 16 | Wave Sentence | 
| 17 | Maze | 
| 18 | Pulse | 
| 19 | Equalizer | 
| 1A | Paint | 
| 1B | Long Horn | 
| 1C | Wangan URL | 
| 1D | Galaga | 
| 1E | Pac-Man | 
| 1F | Love | 
| 20 | Emotion | 
| 21 | Square | 
| 22 | Pine | 
| 23 | Trap | 
| 24 | Wing | 
| 25 | Tribal 3 | 
| 26 | Tribal 4 | 
| 27 | Techno | 
| 28 | Techno 2 | 
| 29 | Beard | 
| 2A | Flash | 
| 2B | Scratch | 
| 2C | Antique | 
| 2D | Arrow 2 | 
| 2E | Checker Flag | 
| 2F | Checker Flag 2 | 
| 30 | Puzzle | 
| 31 | Puzzle 2 | 
| 32 | Wave | 
| 33 | Fang | 
| 34 | Lock-On | 
| 35 | Chain | 
| 36 | Street | 
| 37 | No Trespassing | 
| 38 | Barcode | 
| 39 | Zipper | 
| 3A | Wangan URL 2 | 