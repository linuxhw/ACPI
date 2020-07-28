ACPI Tables
===========

This is a repository of decoded ACPI tables for various computers collected
by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload -dump-acpi

Contents
--------

1. [ About     ](#about)
2. [ Notebooks ](#notebooks)
3. [ Desktops  ](#desktops)
4. [ Servers   ](#servers)

About
-----

The structure of the directory is the following:

    {TYPE}/{VENDOR}/{MODEL PREFIX}/{MODEL}/{HWID}

    ( e.g. Notebook/Lenovo/G570/G570 20079/87FB42D5B9E2 )

Notebooks
---------

| MFG              | Model                  | HWID         |
|------------------|------------------------|--------------|
| ASUSTek Computer | 1215N                  | 9A77F30CC078 |
| ASUSTek Computer | A3L                    | F71442C2DD56 |
| ASUSTek Computer | E403NA                 | E3A7CFB90011 |
| ASUSTek Computer | G752VL                 | FC552E246162 |
| ASUSTek Computer | G752VS                 | 2C3A54B9621B |
| ASUSTek Computer | K53BY                  | BE1217B3A172 |
| ASUSTek Computer | K54HR                  | CDCECF3994DD |
| ASUSTek Computer | N53Jf                  | 72185E9A7C5E |
| ASUSTek Computer | N53Ta                  | 44FD90565A2A |
| ASUSTek Computer | X200CA                 | 8CF325A2BCD9 |
| ASUSTek Computer | X71SL                  | C5769FF2BEDC |
| ASUSTek Computer | X750JB                 | F58754409DC7 |
| Aava Mobile Oy   | INARI8-LTBN-1          | A658B5B6E0CB |
| Acer             | Aspire A315-42G        | DC953747E73F |
| Acer             | Aspire E1-571G         | 56A1CBDE0299 |
| Acer             | Aspire E1-571G         | 80E357275D08 |
| Acer             | Aspire E5-571          | FE8D2745B442 |
| Acer             | Aspire E5-571G         | D9DF65E3962C |
| Acer             | Nitro AN515-42         | 7D6CB7ACB520 |
| Acer             | Peppy                  | 77DD53F16CF4 |
| Alienware        | 17 R5                  | 2B5491E1A559 |
| Apple            | MacBookPro14,3         | 91077C25D705 |
| Avell High Pe... | C75 RTX MUV-G1750 R... | B4CC55E338B5 |
| BBEN             | z10                    | 65E372FCAFD3 |
| CCE              | Capella & IbexPeak-... | 47908F284309 |
| Dell             | G3 3579                | 28F1D7BB6F35 |
| Dell             | Inspiron 3558          | 7C3F03888987 |
| Dell             | Latitude E5450         | E1BA902CF2E6 |
| Dell             | Latitude E5520         | E746086B8F59 |
| Dell             | Latitude E6520         | C019B771B42C |
| Dell             | Latitude E6530         | 8B5EC6878A4B |
| Dell             | Latitude E6540         | 478086798418 |
| Dell             | Latitude E7470         | D4D1BF2C15BB |
| Dell             | Precision 5540         | 33C46A09AA00 |
| Dell             | Precision 7530         | 5B887671E31F |
| Dell             | XPS 13 7390            | 6E5EDD6F0EBC |
| Dell             | XPS 13 9360            | 31C80E9937FE |
| Dell             | XPS 15 7590            | FCAA93EB64E7 |
| Hewlett-Packard  | 15                     | 07149FC6072A |
| Hewlett-Packard  | Compaq 6730b           | 795F37601A0A |
| Hewlett-Packard  | ENVY TS 15             | 3B3FD352A709 |
| Hewlett-Packard  | ENVY m6                | 4A3F47F3A0D9 |
| Hewlett-Packard  | ENVY m6                | 4EB247E5B835 |
| Hewlett-Packard  | EliteBook 2740p        | 0A6CC5DD2EF6 |
| Hewlett-Packard  | EliteBook 820 G4       | 5CBF54885D83 |
| Hewlett-Packard  | EliteBook 8740w        | 6EA92286C100 |
| Hewlett-Packard  | EliteBook 8740w        | C619FE23190E |
| Hewlett-Packard  | EliteBook Folio 9470m  | 524B6B1AD490 |
| Hewlett-Packard  | G42                    | A1AAA80A9E8E |
| Hewlett-Packard  | G62                    | D4B22D617BFD |
| Hewlett-Packard  | Laptop 14-cf0xxx       | 42F2CB5F9E38 |
| Hewlett-Packard  | Laptop 15-db0xxx       | 532B72E8E7AC |
| Hewlett-Packard  | Mini 5101              | D143AED9806A |
| Hewlett-Packard  | Pavilion Notebook      | 45CC6121C541 |
| Hewlett-Packard  | Pavilion dv8           | D8B9EB76B074 |
| Hewlett-Packard  | ProBook 4540s          | F9464A10DAC3 |
| Hewlett-Packard  | ProBook 470 G0         | 7206C3577DFF |
| Hewlett-Packard  | Stream 13              | ED889F5F2A86 |
| Hewlett-Packard  | TouchSmart tx2         | 6909B67B540B |
| Hewlett-Packard  | ZBook Studio G5        | 39AAE603D78B |
| IT Channel Pty   | NH50_70RH              | 3A881F598779 |
| Insyde           | BayTrail               | 9F287627613B |
| Lenovo           | Flex 2-15              | 8F84E14F5157 |
| Lenovo           | G570 20079             | 45D05063F068 |
| Lenovo           | G570 20079             | 92B1F90D7EAE |
| Lenovo           | G710 20252             | CD846FB97BC3 |
| Lenovo           | IdeaPad 310-15IKB 80TV | B9544046A48A |
| Lenovo           | IdeaPad 330S-14IKB ... | 3060C8F822F9 |
| Lenovo           | IdeaPad U310           | 3AC887234B79 |
| Lenovo           | ThinkPad 11e 3rd Ge... | 2A3A2DBF3FD4 |
| Lenovo           | ThinkPad E595 20NFC... | 26FEFDA4DE0C |
| Lenovo           | ThinkPad Edge E431 ... | 6D85F40A9B08 |
| Lenovo           | ThinkPad Mini10 350... | EAC15D3F8438 |
| Lenovo           | ThinkPad P52 20M9CT... | 7F49922756AE |
| Lenovo           | ThinkPad T470 W10DG... | 54A59AE22AFF |
| Lenovo           | ThinkPad T61 76641FG   | 765F0725EA93 |
| Lenovo           | ThinkPad T61p 64575KU  | 11FB59AAE306 |
| Lenovo           | ThinkPad W510 4875W17  | 822D8852D7EB |
| Lenovo           | ThinkPad W540 20BHS... | F5785B0C6551 |
| Lenovo           | ThinkPad X1 Carbon ... | 66976DD8FE3D |
| Lenovo           | ThinkPad X1 Carbon ... | BE3AACE7B6D7 |
| Lenovo           | ThinkPad X230 2325A60  | AE4563D1F6CF |
| Lenovo           | ThinkPad X380 Yoga ... | 5EDC3F139B76 |
| Lenovo           | ThinkPad X61 Tablet... | 175B115C38BD |
| Lenovo           | ThinkPad X61 Tablet... | A54FD909734A |
| MSI              | GE60 0NC-GE60 0ND      | D2F5133B920A |
| MSI              | GP63 Leopard 8RD       | 52757605F366 |
| MSI              | GT70                   | 90552E3B1017 |
| MSI              | GT70                   | D4EFA09F0CFD |
| MSI              | MS-N031                | 237F541314EF |
| MSI              | PR200                  | 94CECEDC956C |
| MSI              | X460-X460DX            | 7AA60F771207 |
| Notebook         | N8xEJEK                | 336D5712545D |
| Razer            | Blade                  | F55394D068BE |
| Samsung Elect... | 300V3A-300V4A-300V5... | 35CC56EF66E3 |
| Samsung Elect... | 305U1A                 | 09E2C5E73434 |
| Samsung Elect... | 355V4C-355V4X-355V5... | 51CDAFB26356 |
| Samsung Elect... | Q310                   | 94C0252E4BC9 |
| Samsung Elect... | RF510-RF410-RF710      | 0D3B24930741 |
| Samsung Elect... | RF510-RF410-RF710      | 5BEB13CF77EB |
| Sony             | SVE1713S1RW            | 506CDC50E671 |
| Timi             | TM1701                 | 6F3EF48DD098 |
| Toshiba          | Satellite A135         | D67BA1A5ADD8 |
| Toshiba          | Satellite C70D-B       | D0292BFAFD2C |
| Toshiba          | Satellite L655         | 5DFEE87972AA |
| Toshiba          | Satellite P500         | EA4A81982518 |
| Toshiba          | Satellite Pro L630     | 2BCF481E15A0 |
| Toshiba          | Satellite Pro L630     | E4A738095425 |
| Toshiba          | TECRA A50-A            | 36303D77C8F0 |

Desktops
--------

| MFG              | Model                  | HWID         |
|------------------|------------------------|--------------|
| ASRock           | 870 Extreme3           | 96943D290A28 |
| ASRock           | B450 Pro4              | 2B7468FF1136 |
| ASRock           | G31M-S                 | 53A47C01E2B6 |
| ASRock           | X370 Gaming X          | FD61EDF83841 |
| ASUSTek Computer | All Series             | 21299B1F4635 |
| ASUSTek Computer | All Series             | 6B158AE6BD79 |
| ASUSTek Computer | F1A75-M LE             | 0DD8332C0CDD |
| ASUSTek Computer | H110M-A-M.2            | C8AF5B504787 |
| ASUSTek Computer | M2NPV-VM               | 01FB14E3CB98 |
| ASUSTek Computer | M4A78T-E               | 83CD211F5082 |
| ASUSTek Computer | M5A78L-M PLUS-USB3     | 1429FA6A44BB |
| ASUSTek Computer | P4P800                 | 92967C173382 |
| ASUSTek Computer | P5GC-MX                | 84CD51FC834B |
| ASUSTek Computer | P8H67-M                | D4F93141130B |
| ASUSTek Computer | P8P67                  | 153751203A61 |
| ASUSTek Computer | PRIME A320M-K          | 7A97D933DB40 |
| ASUSTek Computer | PRIME B250M-PLUS       | 55D7B7DDD6EA |
| ASUSTek Computer | PRIME X370-PRO         | 22F59A67504C |
| ASUSTek Computer | PRIME X370-PRO         | A169FD97AB0E |
| ASUSTek Computer | ROG Maximus XI FORMULA | 5E84C606C2ED |
| ASUSTek Computer | SABERTOOTH 990FX       | 3D77ED0B498A |
| ASUSTek Computer | SABERTOOTH 990FX       | B015992EFDE5 |
| ASUSTek Computer | Z170-A                 | 829C11128B18 |
| Acer             | Aspire R3600           | C85DE8E38D84 |
| Acer             | Aspire Z3-615          | E37DB50E1157 |
| Aquarius         | Aquarius Pro P30 S75   | 0485A3072F96 |
| Aquarius         | Aquarius Pro P30 S75   | 9753F4AD3EFB |
| Aquarius         | Aquarius Pro, Std, ... | C81391734654 |
| Biostar          | TB250-BTC PRO          | 0DD393D67EFC |
| Dell             | Inspiron 530           | DEF2DEF61AED |
| Dell             | Precision Tower 5810   | 998589835EA1 |
| Gigabyte Tech... | 990XA-UD3              | 16D86A6F85C2 |
| Gigabyte Tech... | B450M DS3H             | D9E9E66D46A4 |
| Gigabyte Tech... | B75M-D3V               | 98E089E19203 |
| Gigabyte Tech... | GA-MA78LMT-US2H        | 883557B73AAA |
| Gigabyte Tech... | H270-HD3               | 7698BC6E9003 |
| Gigabyte Tech... | Q87M-D2H               | 4A407DB4786C |
| Gigabyte Tech... | X570 AORUS PRO         | D33A09A909D4 |
| Gigabyte Tech... | Z170X-Gaming 5         | 3F59130A5FF7 |
| Gigabyte Tech... | Z270N-WIFI             | C5AACAD1CD45 |
| Gigabyte Tech... | Z390 I AORUS PRO WIFI  | F80EFC3E557E |
| Gigabyte Tech... | Z87-HD3                | 6B00753B50AA |
| Hewlett-Packard  | 450-a100ns             | C9D5E5E25DCF |
| Hewlett-Packard  | 750-467c               | D213850B6974 |
| Hewlett-Packard  | Compaq 6005 Pro MT PC  | 86BB28345D1D |
| Hewlett-Packard  | Compaq dc5800 Small... | B5AE0C22424E |
| Hewlett-Packard  | EliteDesk 800 G1 SFF   | F13506CA489E |
| Hewlett-Packard  | GU620AA-ABE m9080.es   | 7C75A10C1DDC |
| Hewlett-Packard  | Z400 Workstation       | FF7C21B8CB39 |
| Hewlett-Packard  | h8-1080sc              | 25250FD435E2 |
| Intel            | DG965LV AAD36275-501   | 9EEB4575F468 |
| Intel            | DG965LV AAD36275-501   | F0588ABD2042 |
| MSI              | MS-7519                | 4067500F99BB |
| MSI              | MS-7721                | 3EF15301B047 |
| MSI              | MS-7752                | 14FAD414B696 |
| MSI              | MS-7A38                | 53B5D217D45C |
| MSI              | MS-7B19                | 0FE3C97F624E |
| MSI              | MS-7B78                | E18238CFE532 |
| MSI              | MS-7B79                | 58CCA16AFBB8 |
| Supermicro       | X8SIL                  | 40AECBFF4573 |
| TONK             | C31                    | 7F7E8D75C7FF |
| TONK             | TN1402                 | ABC6298CB633 |
| ZOTAC            | NM10                   | 27F12A855946 |

Servers
-------

| MFG              | Model                  | HWID         |
|------------------|------------------------|--------------|
| AIC              | FB201-LX               | E9F0ABF1FB7A |
| DEPO Computers   | Super Server           | 5ED617DD5961 |
| DEPO Computers   | Super Server           | F84E17B9619B |
| Hewlett-Packard  | ProLiant DL380e Gen8   | CB05571909C8 |
| STSS             | Flagman TP100.3        | 34DC8A4302D7 |
| Supermicro       | H8DGU                  | 57ED146F2C3C |
| Supermicro       | H8QG6                  | 28567EC2EFB1 |
| Supermicro       | X8DTN+-F               | 319567CDA949 |
| Supermicro       | X9DRD-7LN4F-X9DRD-EF   | E23334E6B08A |

Convertibles
------------

| MFG              | Model                  | HWID         |
|------------------|------------------------|--------------|
| Dell             | Latitude 7400 2-in-1   | 5DA0C196CB26 |
| Lenovo           | Yoga C640-13IML 81UE   | 91A793680B40 |

