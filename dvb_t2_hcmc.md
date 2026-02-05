---
title: "DVB-T2 channel scan in Ho Chi Minh City"
date: 2026-02-05
layout: page
---

# Preface
As of February 2026, free-to-air (FTA) DVB-T2 TV saw increasingly less and less use in Vietnam, with most TV users trending more and more toward using Internet TV which offered convenience and mobility as they can watch most free channels on phones or laptops in comparison to the annoyance of having to put up and antenna. Moreover, a lot of people used on-demand video services and cable providers for subscription-based TV channels means even less people used paid DVB-T2 services. However, there are still a lot of channels being broadcasted over the air (OTA) but the up-to-date information about their channels and multiplexes are not readily available on the Internet with a lot of outdated information mixed in. This is my attempt at reporting what TV channels are available in Ho Chi Minh City and what are their characteristics.

# Methodology
My setup included a standard DVB-T2 set-top box (STB) called TOPT2 (based on MStar MSD7T01 SoC and Rafael Micro R836 tuner) from a local company called Vũ Hồng Minh (VHM), a small 4.3 inch TFT LCD (sold on a lot of sites as monitor for car backup camera) and a homemade loop for the antenna. The STB conveniently reports the properties of the modulation of each channel and what is the PID used by the multiplexes.

# Result
A scan revealed that there are 7 UHF channels currently in use in Ho Chi Minh City. However, I have difficulty receiving channel 25, 27 and 34 right now as my house is surrounded by taller building near by with no line-of-sight reception.Their modulation parameters are as follow:

| Channel      | Modulation Schemes | Guard Interval | FEC | FFT |
|:------------:|:------------------:|:--------------:|:---:|:---:|
| 25 (506 MHz) |                    |                |     |     |
| 27 (522 MHz) |                    |                |     |     |
| 33 (570 MHz) | 64-QAM             | 1/8            | 3/4 | 32k |
| 34 (578 MHz) |                    |                |     |     |
| 42 (642 MHz) | 256-QAM            | 1/8            | 3/5 | 32k |
| 44 (658 MHz) | 256-QAM            | 1/8            | 3/5 | 32k |
| 45 (666 MHz) | 256-QAM            | 1/8            | 3/5 | 32k |

There used to be 2 more UHF channels (channel 30 and channel 55) used by VTC based on old information found on the Internet. However, after VTC ceased transmission in early 2025 those 2 channels are no longer in use. In addition, Ho Chi Minh City does not use VHF for TV transmission.

## Channel 25 (506 MHz) multiplexes

## Channel 27 (522 MHz) multiplexes

## Channel 33 (570 MHz) multiplexes

| Name            | Subscription | PID            | LCN  |
|-----------------|--------------|----------------|------|
| HTV9            | No           | 3701/3801/3701 | 1001 |
| HTV7 HD         | No           | 3702/3802/3702 | 1002 |
| BTV6-SHOPPING 2 | No           | 3703/3803/3703 | 1003 |
| HTV1 HD         | No           | 3704/3804/3704 | 1004 |
| TH CAN THO 1 HD | No           | 3705/3805/3705 | 1005 |
| QPVN HD         | No           | 3706/3806/3706 | 1006 |
| SCTV10          | No           | 3707/3807/3707 | 1007 |
| TH DONG THAP 2  | No           | 2108/1108/2108 | 1008 |
| TH DONG THAP 1  | No           | 3709/3809/3709 | 1009 |
| HTV THE THAO    | No           | 3712/3812/3712 | 1010 |
| BPTTH DA NANG 2 | No           | 3713/3813/3713 | 1011 |
| TH BINH THUAN   | No           | 3714/3814/3714 | 1012 |
| BPTTH TAY NINH  | No           | 3715/3815/3715 | 1013 |
| BPTTH CAN THO 3 | No           | 3716/3816/3716 | 1014 |
| BPTTH DONG NAI  | No           | 3717/3817/3717 | 1015 |

## Channel 34 (578 MHz) multiplexes

## Channel 42 (642 MHz) multiplexes

| Name               | Subscription | PID                | LCN  |
|:------------------:|:------------:|:------------------:|:----:|
| An Ninh TV         | Yes          | 5761/5762/5761     | 0004 |
| VTV5 Tay Nguyen    | Yes          | 5771/5772 AAC/5771 | 0015 |
| VTV5 Tay Nam Bo    | Yes          | 4171/4172 AAC/4171 | 0016 |
| VTV8               | Yes          | 1711/1712 AAC/1711 | 0019 |
| HY - Hung Yen HD   | No           | 4891/4892/4891     | 0078 |
| H1 - Ha Noi 1      | Yes          | 1371/1372 AAC/1371 | 0047 |
| VTV1 HD            | Yes          | 1181/1182 AAC/1181 | 0001 |
| VTV3               | Yes          | 1341/1342 AAC/1341 | 0003 |
| VTV2               | Yes          | 2421/2422 AAC/2421 | 0002 |
| KTV - Khanh Hoa HD | No           | 4811/4812/4811     | 0049 |
| THVL1 - Vinh Long  | No           | 1000/2000/1000     | 0039 |
| Vietnam Today      | Yes          | 1001/1002/1001     | 0010 |

## Channel 44 (658 MHz) multiplexes

| Name                 | Subscription | PID                | LCN  |
|:--------------------:|:------------:|:------------------:|:----:|
| VTV Can Tho          | Yes          | 4121/4122 AAC/4121 | 0017 |
| VTV5                 | Yes          | 4471/4472 AAC/4471 | 0014 |
| VTV4                 | Yes          | 1225/1226 AAC/1225 | 0013 |
| VTV7 HD              | Yes          | 1045/1046 AAC/1045 | 0018 |
| Huong dan khach hang | No           | 4031/4032/4031     | 0011 |
| DW                   | Yes          | 1085/1086 AAC/1085 | 0021 |
| France 24            | Yes          | 2981/2982 AAC/2981 | 0022 |
| Channel News Asia    | Yes          | 4001/4002 AAC/4001 | 0023 |
| Arirang              | Yes          | 1241/1242 AAC/1241 | 0024 |
| TV5 Monde            | Yes          | 1065/1066 AAC/1065 | 0025 |
| NHK World            | Yes          | 1135/1136 AAC/1135 | 0026 |
| BTV9 - An Vien HD    | Yes          | 1000/2000 AAC/1000 | 0044 |
| HTV9                 | Yes          | 1001/1002 AAC/1001 | 0046 |

## Channel 45 (666 MHz) multiplexes

| Name               | Subscription | PID                | LCN  |
|:------------------:|:------------:|:------------------:|:----:|
| NBTV - Ninh Binh   | No           | 2021/2022/2021     | 0072 |
| QPVN HD            | No           | 2581/2582/2581     | 0005 |
| BHTTV - Ha Tinh HD | No           | 4701/4702/4701     | 0079 |
| TN1 - Thai Nguyen  | No           | 4021/4022/4021     | 0012 |
| TTV - Tuyen Quang  | No           | 4991/4992/4991     | 0071 |
| NTV - Nghe An HD   | No           | 2561/2562/2561     | 0050 |
| THVL3 HD           | No           | 2038/2039/2038     | 0070 |
| THP - Hai Phong HD | No           | 4011/4012/4011     | 0075 |
| THP3 - Hai Phong   | No           | 1035/1036/1035     | 0076 |
| VTV9               | Yes          | 1000/2000 AAC/1000 | 0020 |
