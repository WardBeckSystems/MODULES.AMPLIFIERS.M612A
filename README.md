# M612A Audio Distribution Amplifier · Amplifiers

Ward-Beck Systems M612A, 1983|16. Wiki page: [M612A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M612A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 99 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 2 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 288 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 39 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 25 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 93 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1983 - M612A - P004 - 1-1.jpg](MANUALS/1983%20-%20M612A%20-%20P004%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | +40 dB dB continuously variable with +/-3 dB trim (Bridging Gain). |
| **Frequency response** | +/-0.2 dB 20 kHz |
| **Noise** | 40 dB gain: unity gain: Greater than dB below dBm. 4' dBm 20 kHz bw) Greater than dB below (measured over 20 Hz |
| **Harmonic distortion** | Less than 0.2% THD from 20 Hz 20 kHz up +24 dBm output level with 12 outputs simultaneously driven. |
| **Input level** | dBm +14 dBm nominal for dBm output, +24 dBm maximum at unity gain. |
| **Input impedance** | 30,000 ohms greater balanced |
| **Source impedance** | 600 ohms less, balanced unbalanced |
| **Common mode rejection ratio** | Greater than 65 dB. |
| **Common mode voltage** | 70v peak maximum. |
| **Output level** | dBm nominal +24 dBm maximum at each output, 12 outputs maximum. |
| **Output impedance** | 600 ohms resistive actively balanced each output, |
| **Load impedance** | 600 ohms balanced for each output |
| **Output isolation** | dB or greater |
| **Phasing** | The low terminal number the input pair and the low terminal number the output pair are phase |

## Circuit description

From [1983 - M612A - Audio DA (2).pdf](MANUALS/1983%20-%20M612A%20-%20Audio%20DA%20(2).pdf) pages 21-26 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

SAI4-065 AUDIO AMPLIFIER ASSE M8 LY

Thea u d io i n pu l tot h e SA14-065 Amplifier A~ sembl y appears e t pins 1 and 2 oft b e ass e mb l y connKlor. 1'1.2 and 1'1.3 determine the input impedance of I h e a Clive l y balanced inpul. Integrated circuits Ul and U2 with I heir assoc late d components makeup Ihe actlvely balanced preampli f ier. CR I through CR 4 are l i mil ing diodes which prOlec t thea mp l l fie r input from overloading voltage levels.

1'1.8 and C5 set the balance between the two s&quot;,ctions of the p r &quot;,amp l ifl &quot;,r circuit. Thi,.. d ete......ine s t h &quot;, lon gitudl nlll balance o f m e input c irc u i l ryan d there j Kt ion to common mode signal vollage s.

The preampl ifi er output appearing e t pin 8 of Ih e 8 s se mb ly conneclor f.... d son.. half o f the dual gain cont r o i (R202 and 1'1.203). There turn feedback P lli h from 1'1.20 2 appear ll III pin 7 oft he assembly connKlor. The prea mpl1fi er out p u l also conn ecls t o Ihe Trim l e v &quot;,1 control 1'1.201. There i urn path from R201 app e a ring al pin 9 of I h e assembly conn ectercoupl e s through C9 tot h e inpul of booster amp l if ie r U3.

The output of U3 115 coupled 10 the power amp l i fie r output sl age through C12. I t also feeds the sKond half oft he dual gain c onl ro l 1'1.203. There l urn feed back path from R203 appears atp in 10 oft h e assembly conn eClor.

Th '&quot; actively balanced power OUlpu t stage Is made up oft wo amplifiers. In tegraled cir&lt;uil U4 along w ilh 0 1 t h rough a5 makeup the lower half oft h e power OUlpu tamp l i fie r, while U5 along wilh 0 6 t h r o u g n 01 0 mak '&quot; upI n e upper n ai f.

The ou tpu l capability oft his power amplifier i sin excess of 2 1{2 watt &quot; lind appea &quot; '&quot; a t pins 18 and 19 o f Ihe ass e mb l y conn ec lor.

The output from Ihi s amp l if i e r drives the 600 ohms p litter n&quot;, two rks located on the SAI 4_066 assemblies.

Off set adj us l cont r o ls 1'1.2 3 and 1'1.41 are used 10 trim off sel voltage

errors at the amplifier o u tpul 10 eer-c •

**SAI 4 -06 5**

SA 1 4-06~ AUDIO AMPLIFIER ASSEMBLY

The powers u p ply, int eg r alto the SA14-065 assembly derives liS ec vol l&quot;ge l &quot; pp e &quot; rl n g atp ins 2 1 and 22 of I h e assembly connector) from I h4:I e&gt;&lt;lerna l power Ir &quot; n sf o rme r T201 mo&lt;J&quot; ted 0I'l the chan ls of lhe M61V,.

Bridger ec l i fie r CR~ a lO&lt;'lg w l l h C31 and C32 ~t i fie s a&quot; d filters Ih eec volta g e provld l&quot;S1 a &quot;om, &quot;at +/ -32 vol l de OUlpu t. These voltage s drive the power OUlput stage of l he SAl 4-065 directly, a swell a s &lt;IIppearing &lt;lit connector p,n s 15 and 16 fort he purpose of power l&quot;g thee.. le.....al SA.8-111 In dica torDriver Assembly.

The +/ -32 vc f t de vol lag es are f u rlhe r decovpled a&quot;d filler ed b y 0 1 I Ihrough 0 14 a&quot;d C3 l Ih rough C36. This provides +/-21 vo l! deregulated supply voltages to opera Ie l he i &quot; le grated c lrcui l amplifiers of Ihe SAI III_065 amplifier &lt;II ssembly.

**SAI4 _065 AUDIO AMPLIFIER ASSEMBLY**

DESCRIPTION MFG PART NUMBER

cr Ca ~~,,;ltor ISO uF /l0 V Kernel TJ9QE157MOIOAS C2 ISO u F/ to V CJ 117pF Ph ~,li ~ 5 2222 _638_3 &quot;79 C' 2.2 p F 2222 _638 _09228 C, (Va r i able Cap) 2-18 pF 22 22_809_0S003

C, C a p~ cl l or 117 pF 2222-638-3&quot;79 C1 JJ..uF/ 16 V Kernel TJ9003J6M016AS

6.8 pF 33 u F/ 16 V K_, Philips 2222-638-09688

**TJ9003J6MOI6AS**

W 117 pF Ph~!;ps 2222-638-341179 C&quot; 100 pF 2222-638-58101 c te 12 pF 2222-638-1 0129

C&quot; •. 7pF 2222-638..(19478 m 15 pF 2222-638_1 0159

c rs 22 pF 22 u F/l5 V K_, 2222-638-10229

**TJ9OE226M03SAS**

C20 22 pF Philips 2222-638-10229

0.02 2 uF 33 uF/ 10 V K_, ese reo CQ92-MCIOD-22JM

**T3900 3J6M0 IOAS**

C2J 100 ~F Ph:,l i p,. 2222-638_581 01 m 8.2 pF 2222-638-09828 C25 11.7 pF 2222 -638-09478

C26 15 pF 2222-638-10159 C21 68,F 2222-638-52689 C28 22 uF /35 V Kemel T39OE226M035AS C29 22pF 2222 _638_ 10229 CJ« 0.022uF::~:~~s CQ92_MC_lOO_22JM

CJ&lt; 47~, uF / 40 V Ph:,I; pS

en 47 u F/ 25 V 47/2585 200

CJ' 47 uF/25 V

C&quot; 22 u F/25 V 25/2 5 852 00

**5&quot;14-065 AUDIO AMPLIFIER ASSEMBLY**

DESCRIPTION MFG PART NUMBER CJ' C ap~C: lt o.. 22 vF !25 V Si....... ns 22/2585200

70 Diode

cas 8.. ldg e Rectifi e.. EO ' PD40 CR' Diode, Zom.... 51V Motorola IN47578

0' T&quot;a n s isl or National PNl569 0' TN4037 0' PNl569 0' Tl P29B OS TlP308 Q6 PNl569 07 TN4017 0' PNl569 0' TIP29B 0 &gt;0 TIP3Q8

0&quot; TN2102 0&quot; TI&lt;I4037 0&quot; TI&lt;I2 102 0&quot; 1 1&lt;14017

Resi sto.. 1! 4W 5%

220K Philips

**130K**

RS ' lO K

**R' '0**

R7 Resistor 1! 4W I S SK' R, Trim Pot Pih....

&quot; 10tl12.51 'K

R, R..sis lor 1!4W I S &quot;7 Philips

&quot;,0 R..sls lor 1!4W 5S &gt;2K

**R&quot; II OK**

R&quot; m

**R&quot; &quot; K**

WAR C - BECKS YST EMS LTC.

SAI 4-065 AUDIO AMPLIFIER ASSEMBLY

DESCRIPTION MFG PART NUMBER

RIS Resistor l ! lAW 51

**180K**

Ph i lip5

RlJ Trim POI Res ls lor l ! 4W 51

:;OK Pihe r Philips PT lOt&gt; {2.51 50K

**R&gt;8 22**

Resistor lW 51

Resistor 1!4W 51

Philips RS_I !2 l K2

on Resistor 1/2W 51 a.a RJ&lt; a.a

RJ&lt;; Resistor 1! 4W 51 22

Trim Pot

R&quot; Pi her P T 10h (2.5):;OK R&quot; Resistor 1!4W 51 &gt;SK Philips

**R&quot; 22K**

Re5 15l or lW 51.. a RS_l/2.. z

Roe.. aRe si st or 1/4W5S

R&quot; 2K1 Philips

5,1,14_ 065

**SAI4-065 AUDIO AMPLIFIER ASSEMBLY**

DESCRIPTION MFG PART NUMBER

R'&quot; Resistor 1!4W 5% &quot;K P h~/;P S R&quot; Resistor 1!2W 5% 2.2

**R&gt;3 2.2**

Resistor 1! 4W

Resistor 1!4W 5% 5' 22

**R58 22 K**

R59 Resistor 1! 2W 5' 220

U' Inte,~r ~ted CircuitS i~,ne tics

SOCKETS AND MISCELLANEOUS COMPONENTS

U l,U 2, U3 U4,U S 8Pin Dip Socket

04, 05, 0 9,

was recommends the use o f rep l ~cemen t parts made by the specified manufacturers for continued optimum equipment performance.

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVkhXel9hTHNBMTg/view?resourcekey=0-c21oVOzYhFEhF0MmOZsTiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVkhXel9hTHNBMTg&resourcekey=0-c21oVOzYhFEhF0MmOZsTiQ" width="240" alt="1983 - M612A - IMG_3251.jpg"></a><br><sub>1983|16 · IMG_3251</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaldQckppaUkwdkE/view?resourcekey=0-BZuXzVf9k84wPrQG2wcEbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaldQckppaUkwdkE&resourcekey=0-BZuXzVf9k84wPrQG2wcEbQ" width="240" alt="1983 - M612A - IMG_3252.jpg"></a><br><sub>1983|16 · IMG_3252</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTlJOSmIxeUpFR1U/view?resourcekey=0-3TUyffwiYxmohoY_nWPwIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTlJOSmIxeUpFR1U&resourcekey=0-3TUyffwiYxmohoY_nWPwIQ" width="240" alt="1983 - M612A - IMG_3253.jpg"></a><br><sub>1983|16 · IMG_3253</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZEVWbzlSR1VLOFU/view?resourcekey=0-vLhZa9h-o2g_FX94iUVPmA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZEVWbzlSR1VLOFU&resourcekey=0-vLhZa9h-o2g_FX94iUVPmA" width="240" alt="1983 - M612A - IMG_3254.jpg"></a><br><sub>1983|16 · IMG_3254</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd0hXMU1fNUU0V1E/view?resourcekey=0-5uP6PgMMOWLfjLf_ONmsoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd0hXMU1fNUU0V1E&resourcekey=0-5uP6PgMMOWLfjLf_ONmsoA" width="240" alt="1983 - M612A - IMG_3255.jpg"></a><br><sub>1983|16 · IMG_3255</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUUU0dTVwd0xBTkk/view?resourcekey=0-pZ7zZUN0c_xVbL2qvqy7TQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUUU0dTVwd0xBTkk&resourcekey=0-pZ7zZUN0c_xVbL2qvqy7TQ" width="240" alt="1983 - M612A - IMG_3256.jpg"></a><br><sub>1983|16 · IMG_3256</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKblJNOVRKLVBSd00/view?resourcekey=0-EqHHtoPgXgxBMwGOWaC4zg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKblJNOVRKLVBSd00&resourcekey=0-EqHHtoPgXgxBMwGOWaC4zg" width="240" alt="1983 - M612A - IMG_3257.jpg"></a><br><sub>1983|16 · IMG_3257</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmZuR0pIZVg3RDg/view?resourcekey=0-6SAlasiAoE7WntNdvrQ2Og" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmZuR0pIZVg3RDg&resourcekey=0-6SAlasiAoE7WntNdvrQ2Og" width="240" alt="1983 - M612A - IMG_3258.jpg"></a><br><sub>1983|16 · IMG_3258</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZEczQmE3Y0NVem8/view?resourcekey=0-PvE2TKXvIijGIMLKznExyQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZEczQmE3Y0NVem8&resourcekey=0-PvE2TKXvIijGIMLKznExyQ" width="240" alt="1983 - M612A - IMG_3259.jpg"></a><br><sub>1983|16 · IMG_3259</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRVNNam5QMTYxY1k/view?resourcekey=0-KQSXaYKb3gL82FkeKsE0tw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRVNNam5QMTYxY1k&resourcekey=0-KQSXaYKb3gL82FkeKsE0tw" width="240" alt="1983 - M612A - IMG_3260.jpg"></a><br><sub>1983|16 · IMG_3260</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXFXOTFoVVRMNlE/view?resourcekey=0-HwMrZWSyF0pptN0wmAsgzQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXFXOTFoVVRMNlE&resourcekey=0-HwMrZWSyF0pptN0wmAsgzQ" width="240" alt="1983 - M612A - IMG_3261.jpg"></a><br><sub>1983|16 · IMG_3261</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZE5PYS0wQXpkVGM/view?resourcekey=0-zCigRmn0QRHfgWnRS9In0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZE5PYS0wQXpkVGM&resourcekey=0-zCigRmn0QRHfgWnRS9In0A" width="240" alt="1983 - M612A - IMG_3262.jpg"></a><br><sub>1983|16 · IMG_3262</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKandCazJsVzlDUE0/view?resourcekey=0-68kH9c7VJNsnSH5C3qzzcQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKandCazJsVzlDUE0&resourcekey=0-68kH9c7VJNsnSH5C3qzzcQ" width="240" alt="1983 - M612A - IMG_3263.jpg"></a><br><sub>1983|16 · IMG_3263</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQk1sb3ExLTY4WDQ/view?resourcekey=0-Li_YfId_osQWLsJBTPgmoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQk1sb3ExLTY4WDQ&resourcekey=0-Li_YfId_osQWLsJBTPgmoQ" width="240" alt="1983 - M612A - IMG_3264.jpg"></a><br><sub>1983|16 · IMG_3264</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZFBLNU1HV05KcVE/view?resourcekey=0-1Esz-1G2CMt_DdXCBxrKaA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZFBLNU1HV05KcVE&resourcekey=0-1Esz-1G2CMt_DdXCBxrKaA" width="240" alt="1983 - M612A - IMG_3265.jpg"></a><br><sub>1983|16 · IMG_3265</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYTJES2lsT2tVZTQ/view?resourcekey=0-V4EJUcWpQ81GKZ_sZx9xeA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYTJES2lsT2tVZTQ&resourcekey=0-V4EJUcWpQ81GKZ_sZx9xeA" width="240" alt="1983 - M612A - IMG_3266.jpg"></a><br><sub>1983|16 · IMG_3266</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUDEtMHhKekZKWWs/view?resourcekey=0-UJ9mzjxIP6irptxY71SLXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUDEtMHhKekZKWWs&resourcekey=0-UJ9mzjxIP6irptxY71SLXw" width="240" alt="1983 - M612A - IMG_3267.jpg"></a><br><sub>1983|16 · IMG_3267</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOG9ORVVqeUJLTlk/view?resourcekey=0-2V6keBYgFiz64-BUE0tU1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOG9ORVVqeUJLTlk&resourcekey=0-2V6keBYgFiz64-BUE0tU1w" width="240" alt="1983 - M612A - IMG_3268.jpg"></a><br><sub>1983|16 · IMG_3268</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdnlxMHBJNEtUcUU/view?resourcekey=0-EOu1troAZAU_Q6APb9Y2xg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdnlxMHBJNEtUcUU&resourcekey=0-EOu1troAZAU_Q6APb9Y2xg" width="240" alt="1983 - M612A - IMG_3269.jpg"></a><br><sub>1983|16 · IMG_3269</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOXA4OGU3OWpzZDA/view?resourcekey=0-ULwxX7xCp5CHk2X_l_iB1g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOXA4OGU3OWpzZDA&resourcekey=0-ULwxX7xCp5CHk2X_l_iB1g" width="240" alt="1983 - M612A - IMG_3270.jpg"></a><br><sub>1983|16 · IMG_3270</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSWJvYl9sU3NTaVk/view?resourcekey=0-aRP5O8gfBT7YAxBAGrIv0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSWJvYl9sU3NTaVk&resourcekey=0-aRP5O8gfBT7YAxBAGrIv0Q" width="240" alt="1983 - M612A - IMG_3271.jpg"></a><br><sub>1983|16 · IMG_3271</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFNhQWJQZGZRbUU/view?resourcekey=0-Dup_PTvmsiM-wUu0yPPe2Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFNhQWJQZGZRbUU&resourcekey=0-Dup_PTvmsiM-wUu0yPPe2Q" width="240" alt="1983 - M612A - IMG_3272.jpg"></a><br><sub>1983|16 · IMG_3272</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNnVocTdITXh0ems/view?resourcekey=0-dhq0syAggzUPZgOVkfHgVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNnVocTdITXh0ems&resourcekey=0-dhq0syAggzUPZgOVkfHgVw" width="240" alt="1983 - M612A - IMG_3273.jpg"></a><br><sub>1983|16 · IMG_3273</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQUp3bmJYNlpSZE0/view?resourcekey=0-IESjv35OyQgw5ShMDryLkw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQUp3bmJYNlpSZE0&resourcekey=0-IESjv35OyQgw5ShMDryLkw" width="240" alt="1983 - M612A - IMG_3274.jpg"></a><br><sub>1983|16 · IMG_3274</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0RlTG5uRDFsOU0/view?resourcekey=0-tdzYXW_8bgDJ-szcbsXqwg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0RlTG5uRDFsOU0&resourcekey=0-tdzYXW_8bgDJ-szcbsXqwg" width="240" alt="1983 - M612A - IMG_3275.jpg"></a><br><sub>1983|16 · IMG_3275</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV242N2stMmtnYlE/view?resourcekey=0-nQK5gLlwG4Ro6CVysVAJMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV242N2stMmtnYlE&resourcekey=0-nQK5gLlwG4Ro6CVysVAJMA" width="240" alt="1983 - M612A - IMG_3276.jpg"></a><br><sub>1983|16 · IMG_3276</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSVhZbDBBS3p2dlk/view?resourcekey=0-YnnGM5--eNxFpbjgY2ccvw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSVhZbDBBS3p2dlk&resourcekey=0-YnnGM5--eNxFpbjgY2ccvw" width="240" alt="1983 - M612A - IMG_3277.jpg"></a><br><sub>1983|16 · IMG_3277</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV2ppNUtTc0JZc2M/view?resourcekey=0-_w9fAYgKDZdmw6U8mq9yzw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV2ppNUtTc0JZc2M&resourcekey=0-_w9fAYgKDZdmw6U8mq9yzw" width="240" alt="1983 - M612A - IMG_3278.jpg"></a><br><sub>1983|16 · IMG_3278</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV1ZhMV85bmprTGM/view?resourcekey=0-Dq1m7czy2zQGI3d_VIqTVg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV1ZhMV85bmprTGM&resourcekey=0-Dq1m7czy2zQGI3d_VIqTVg" width="240" alt="1983 - M612A - IMG_3279.jpg"></a><br><sub>1983|16 · IMG_3279</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGFVcTBySnhraTg/view?resourcekey=0-CoOWQlmTH87VvP1nmk67FQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGFVcTBySnhraTg&resourcekey=0-CoOWQlmTH87VvP1nmk67FQ" width="240" alt="1983 - M612A - IMG_3280.jpg"></a><br><sub>1983|16 · IMG_3280</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmJwUE8zX3pyUDA/view?resourcekey=0-jUKkV2T0A9FA45e7vshcaw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmJwUE8zX3pyUDA&resourcekey=0-jUKkV2T0A9FA45e7vshcaw" width="240" alt="1983 - M612A - IMG_3281.jpg"></a><br><sub>1983|16 · IMG_3281</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbGxqTDV0VjQ0eWc/view?resourcekey=0-fLXtaaQ_ZHOe9rWjIV9aPw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbGxqTDV0VjQ0eWc&resourcekey=0-fLXtaaQ_ZHOe9rWjIV9aPw" width="240" alt="1983 - M612A - IMG_3282.jpg"></a><br><sub>1983|16 · IMG_3282</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNm82M3dyY0VCUjA/view?resourcekey=0-eFGoCw5r74mF29Or_c9P9A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNm82M3dyY0VCUjA&resourcekey=0-eFGoCw5r74mF29Or_c9P9A" width="240" alt="1983 - M612A - IMG_3283.jpg"></a><br><sub>1983|16 · IMG_3283</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmJrMTAyQjVtVDg/view?resourcekey=0-e0lEdbRqsobxu_kRkTb9gA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmJrMTAyQjVtVDg&resourcekey=0-e0lEdbRqsobxu_kRkTb9gA" width="240" alt="1983 - M612A - IMG_3284.jpg"></a><br><sub>1983|16 · IMG_3284</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeDJBejVLV3NqSmc/view?resourcekey=0-0hM4lIjvLizIWErvzPx8FQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeDJBejVLV3NqSmc&resourcekey=0-0hM4lIjvLizIWErvzPx8FQ" width="240" alt="1983 - M612A - IMG_3285.jpg"></a><br><sub>1983|16 · IMG_3285</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0J0cFlPTnE1MGc/view?resourcekey=0-WYk2tt6REOyEZb-dU4kf-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0J0cFlPTnE1MGc&resourcekey=0-WYk2tt6REOyEZb-dU4kf-g" width="240" alt="1983 - M612A - IMG_3286.jpg"></a><br><sub>1983|16 · IMG_3286</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNWk5cTlaMmVDWFU/view?resourcekey=0-yb5gynLWqiiDAUoJ93IxeA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNWk5cTlaMmVDWFU&resourcekey=0-yb5gynLWqiiDAUoJ93IxeA" width="240" alt="1983 - M612A - IMG_3287.jpg"></a><br><sub>1983|16 · IMG_3287</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1BGQXNBOFNoQzA/view?resourcekey=0-bxT0iioNJ6wZNBvTv_2oXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1BGQXNBOFNoQzA&resourcekey=0-bxT0iioNJ6wZNBvTv_2oXQ" width="240" alt="1983 - M612A - IMG_3288.jpg"></a><br><sub>1983|16 · IMG_3288</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUlxN3VTU0FYM3c/view?resourcekey=0-sPEWPJpJNKCt-LJpxE8h3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUlxN3VTU0FYM3c&resourcekey=0-sPEWPJpJNKCt-LJpxE8h3w" width="240" alt="1983 - M612A - IMG_3289.jpg"></a><br><sub>1983|16 · IMG_3289</sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdzM3QTZrNVM0QVU/view?resourcekey=0-b3FlehiyTEep32NVPk0U2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdzM3QTZrNVM0QVU&resourcekey=0-b3FlehiyTEep32NVPk0U2g" width="240" alt="1983 - M612A - 12-01-001 - AUDIO DISTRIBUTION AMPLIFIER FUNCTIONAL DIAGRAM.jpg"></a><br><sub>1983|16 · 12-01-001 - AUDIO DISTRIBUTION AMPLIFIER FUNCTIONAL DIAGRAM · <a href="SCHEMATICS/1983%20-%20M612A%20-%2012-01-001%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20FUNCTIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNEk1ZzQzWmFRUk0/view?resourcekey=0-x7tfv-WRLMl8PG27CZY_1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNEk1ZzQzWmFRUk0&resourcekey=0-x7tfv-WRLMl8PG27CZY_1w" width="240" alt="1983 - M612A - 12-02-002 - AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1983|16 · 12-02-002 - AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC · <a href="SCHEMATICS/1983%20-%20M612A%20-%2012-02-002%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWHozcmZ3Y3Jfa1E/view?resourcekey=0-RmgWaNuZi6quuUKjbb0k4Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWHozcmZ3Y3Jfa1E&resourcekey=0-RmgWaNuZi6quuUKjbb0k4Q" width="240" alt="1983 - M612A - 12-02-003 - BYBTEMD TECHNICAL GROUND.jpg"></a><br><sub>1983|16 · 12-02-003 - BYBTEMD TECHNICAL GROUND · <a href="SCHEMATICS/1983%20-%20M612A%20-%2012-02-003%20-%20BYBTEMD%20TECHNICAL%20GROUND%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbG9DSlFKcjdWRlk/view?resourcekey=0-ZxNjZBcT9WKdTz30jD8D3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbG9DSlFKcjdWRlk&resourcekey=0-ZxNjZBcT9WKdTz30jD8D3w" width="240" alt="1983 - M612A - 12-06-003 - AUDIO DISTRIBUTION AMPLIFIER PERSPECTIVE LAYOUT.jpg"></a><br><sub>1983|16 · 12-06-003 - AUDIO DISTRIBUTION AMPLIFIER PERSPECTIVE LAYOUT · <a href="SCHEMATICS/1983%20-%20M612A%20-%2012-06-003%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20PERSPECTIVE%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWlcxQjZrWDF3ZWM/view?resourcekey=0-JjClDJ8T8OWqibh8S0XR_w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWlcxQjZrWDF3ZWM&resourcekey=0-JjClDJ8T8OWqibh8S0XR_w" width="240" alt="1983 - M612A - 612-01-001 - OVERLOAD REF NORMAL REF.jpg"></a><br><sub>1983|16 · 612-01-001 - OVERLOAD REF NORMAL REF · <a href="SCHEMATICS/1983%20-%20M612A%20-%20612-01-001%20-%20OVERLOAD%20REF%20NORMAL%20REF%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVVRVUkYzVWhjSzg/view?resourcekey=0-5jj6Oy7zzJBLu5CQSLFrLQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVVRVUkYzVWhjSzg&resourcekey=0-5jj6Oy7zzJBLu5CQSLFrLQ" width="240" alt="1983 - M612A - 612-02-002 - INDICATOR DRIVER.jpg"></a><br><sub>1983|16 · 612-02-002 - INDICATOR DRIVER · <a href="SCHEMATICS/1983%20-%20M612A%20-%20612-02-002%20-%20INDICATOR%20DRIVER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKemhfbGtSVUR0Wjg/view?resourcekey=0-L2BJHPEAlbaocy9oGHO3Bg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKemhfbGtSVUR0Wjg&resourcekey=0-L2BJHPEAlbaocy9oGHO3Bg" width="240" alt="1983 - M612A - 612-02-003 - STAT ION TECHNICAL GROUND INSULATED GROUND BAR TIPLE.jpg"></a><br><sub>1983|16 · 612-02-003 - STAT ION TECHNICAL GROUND INSULATED GROUND BAR TIPLE · <a href="SCHEMATICS/1983%20-%20M612A%20-%20612-02-003%20-%20STAT%20ION%20TECHNICAL%20GROUND%20INSULATED%20GROUND%20BAR%20TIPLE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT1ViRFgxVEZfUm8/view?resourcekey=0-ztJ9ZaOqfzmZGEiK31htgw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT1ViRFgxVEZfUm8&resourcekey=0-ztJ9ZaOqfzmZGEiK31htgw" width="240" alt="1983 - M612A - 612-06-003.jpg"></a><br><sub>1983|16 · 612-06-003 · <a href="SCHEMATICS/1983%20-%20M612A%20-%20612-06-003%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWFZDWEZCUDdFX3c/view?resourcekey=0-F-W-1xqNP-5g9f2t5A_wYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWFZDWEZCUDdFX3c&resourcekey=0-F-W-1xqNP-5g9f2t5A_wYA" width="240" alt="1983 - M612A - 8-117-02-001 - INDICATOR DRIVER ASSEMBLY SCHEMATIC.jpg"></a><br><sub>1983|16 · 8-117-02-001 - INDICATOR DRIVER ASSEMBLY SCHEMATIC · <a href="SCHEMATICS/1983%20-%20M612A%20-%208-117-02-001%20-%20INDICATOR%20DRIVER%20ASSEMBLY%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2NFYi11VjI2REE/view?resourcekey=0-Vi9xjx4F4A4bf773T6wWRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2NFYi11VjI2REE&resourcekey=0-Vi9xjx4F4A4bf773T6wWRQ" width="240" alt="1983 - M612A - 8-117-02-001.jpg"></a><br><sub>1983|16 · 8-117-02-001 · <a href="SCHEMATICS/1983%20-%20M612A%20-%208-117-02-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdXlqNVRqVmVQdXM/view?resourcekey=0-7_B-txNNEHIZdjiC5daBNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdXlqNVRqVmVQdXM&resourcekey=0-7_B-txNNEHIZdjiC5daBNA" width="240" alt="1983 - M612A - 8-117-06-001 - INDICATOR DRIVER ASSEMBLY COMPONENT LAYOUT.jpg"></a><br><sub>1983|16 · 8-117-06-001 - INDICATOR DRIVER ASSEMBLY COMPONENT LAYOUT · <a href="SCHEMATICS/1983%20-%20M612A%20-%208-117-06-001%20-%20INDICATOR%20DRIVER%20ASSEMBLY%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYy16QnpwbkxHUGs/view?resourcekey=0-yhelx1V9L3ifEBZ9PYHjXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYy16QnpwbkxHUGs&resourcekey=0-yhelx1V9L3ifEBZ9PYHjXw" width="240" alt="1983 - M612A - 8-117-06-001 - NOTES TRANSISTORS.jpg"></a><br><sub>1983|16 · 8-117-06-001 - NOTES TRANSISTORS · <a href="SCHEMATICS/1983%20-%20M612A%20-%208-117-06-001%20-%20NOTES%20TRANSISTORS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQTRwQzZoY0pwM2c/view?resourcekey=0-e63F0zgJikij3olYEK-2Qw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQTRwQzZoY0pwM2c&resourcekey=0-e63F0zgJikij3olYEK-2Qw" width="240" alt="1983 - M612A - Audio DA (2).pdf"></a><br><sub>1983|16 · Audio DA (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNFRYX2FlX1FrNE0/view?resourcekey=0-0D7dW7xocaXZScPmNYztKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNFRYX2FlX1FrNE0&resourcekey=0-0D7dW7xocaXZScPmNYztKg" width="240" alt="1983 - M612A - Audio DA.pdf"></a><br><sub>1983|16 · Audio DA</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaDY4UklqcURoQVk/view?resourcekey=0-_xHUtkjqeesl6tKwFthA5w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaDY4UklqcURoQVk&resourcekey=0-_xHUtkjqeesl6tKwFthA5w" width="240" alt="1983 - M612A - P001 - Title Page.jpg"></a><br><sub>1983|16 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTmZzcGtNRTFYS3M/view?resourcekey=0-eqEeSBYw_LMgNi_TZc_o2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTmZzcGtNRTFYS3M&resourcekey=0-eqEeSBYw_LMgNi_TZc_o2g" width="240" alt="1983 - M612A - P002.jpg"></a><br><sub>1983|16 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaFFDZUxBOHVxT1k/view?resourcekey=0-V9B9yC1uHLBEuJ65raWRfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaFFDZUxBOHVxT1k&resourcekey=0-V9B9yC1uHLBEuJ65raWRfQ" width="240" alt="1983 - M612A - P003.jpg"></a><br><sub>1983|16 · P003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGtzc0Vpb1N1QXM/view?resourcekey=0-fH-pibYEDGEGoxatefjQsA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGtzc0Vpb1N1QXM&resourcekey=0-fH-pibYEDGEGoxatefjQsA" width="240" alt="1983 - M612A - P004 - 1-1.jpg"></a><br><sub>1983|16 · P004 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0ZmcFd2NVZIS0U/view?resourcekey=0-P5Vzoet2U3yXeqBnCVysOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0ZmcFd2NVZIS0U&resourcekey=0-P5Vzoet2U3yXeqBnCVysOQ" width="240" alt="1983 - M612A - P005 - 1-2.jpg"></a><br><sub>1983|16 · P005 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRC1DSkF3ZEFNelU/view?resourcekey=0-sPOoXSd-FN75xcMNHoD1nA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRC1DSkF3ZEFNelU&resourcekey=0-sPOoXSd-FN75xcMNHoD1nA" width="240" alt="1983 - M612A - P006 - 2-1.jpg"></a><br><sub>1983|16 · P006 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNTZiVjhIYmJzc2s/view?resourcekey=0-kW-dafQBtqFoPfGQcFc--A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNTZiVjhIYmJzc2s&resourcekey=0-kW-dafQBtqFoPfGQcFc--A" width="240" alt="1983 - M612A - P007 - 2-2.jpg"></a><br><sub>1983|16 · P007 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNlJQMl9DTGRlbGM/view?resourcekey=0-KUneOIWQl95_BUXOoYAwnA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNlJQMl9DTGRlbGM&resourcekey=0-KUneOIWQl95_BUXOoYAwnA" width="240" alt="1983 - M612A - P008 - 3-1.jpg"></a><br><sub>1983|16 · P008 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKamhodXduSUdvTDQ/view?resourcekey=0-12ZdGtpVLKXmMqRYZaguwA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKamhodXduSUdvTDQ&resourcekey=0-12ZdGtpVLKXmMqRYZaguwA" width="240" alt="1983 - M612A - P009 - 4-1.jpg"></a><br><sub>1983|16 · P009 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRmNMd2Q1MWdabk0/view?resourcekey=0-_Avh_YdwdsxNa0Nyd8q83A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRmNMd2Q1MWdabk0&resourcekey=0-_Avh_YdwdsxNa0Nyd8q83A" width="240" alt="1983 - M612A - P010 - 5-1.jpg"></a><br><sub>1983|16 · P010 - 5-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSTZnUS1iWFdzanM/view?resourcekey=0-O-2LorpH7wP2KagH2HRKhA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSTZnUS1iWFdzanM&resourcekey=0-O-2LorpH7wP2KagH2HRKhA" width="240" alt="1983 - M612A - P015.jpg"></a><br><sub>1983|16 · P015</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVVfQkJZRHhxZ3c/view?resourcekey=0-LefrgUxuX5qFr3zQbnFAEw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVVfQkJZRHhxZ3c&resourcekey=0-LefrgUxuX5qFr3zQbnFAEw" width="240" alt="1983 - M612A - P016 - SA14-065.jpg"></a><br><sub>1983|16 · P016 - SA14-065</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEtJTTNvb0h0RDg/view?resourcekey=0-1UWcmbZ2Pd0omEmjt1Jzkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEtJTTNvb0h0RDg&resourcekey=0-1UWcmbZ2Pd0omEmjt1Jzkg" width="240" alt="1983 - M612A - P017 - SA14-065 - 1-1.jpg"></a><br><sub>1983|16 · P017 - SA14-065 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUEY5X3A2bS03aE0/view?resourcekey=0-l38HVOHU-NsVo-3TOHJMLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUEY5X3A2bS03aE0&resourcekey=0-l38HVOHU-NsVo-3TOHJMLg" width="240" alt="1983 - M612A - P018 - SA14-065 - 1-2.jpg"></a><br><sub>1983|16 · P018 - SA14-065 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR3M3VXBsWUxOQnM/view?resourcekey=0-4W37jQc-dbqngV2QVIwwUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR3M3VXBsWUxOQnM&resourcekey=0-4W37jQc-dbqngV2QVIwwUg" width="240" alt="1983 - M612A - P019 - SA14-065 - 2-1.jpg"></a><br><sub>1983|16 · P019 - SA14-065 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0hwSU5FcW9DbHM/view?resourcekey=0-o-z20QXcS26H7XMSwAu50Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0hwSU5FcW9DbHM&resourcekey=0-o-z20QXcS26H7XMSwAu50Q" width="240" alt="1983 - M612A - P020 - SA14-065 - 2-2.jpg"></a><br><sub>1983|16 · P020 - SA14-065 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa1RwWDYxeGlVRlk/view?resourcekey=0-Tn_nM97tT-nxMfKfBa_i8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa1RwWDYxeGlVRlk&resourcekey=0-Tn_nM97tT-nxMfKfBa_i8w" width="240" alt="1983 - M612A - P021 - SA14-065 - 2-3.jpg"></a><br><sub>1983|16 · P021 - SA14-065 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMzRCUlJ6cVY2dTg/view?resourcekey=0-Im8SJnNcJwDTHUZKnDVokg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMzRCUlJ6cVY2dTg&resourcekey=0-Im8SJnNcJwDTHUZKnDVokg" width="240" alt="1983 - M612A - P022 - SA14-065 - 2-4.jpg"></a><br><sub>1983|16 · P022 - SA14-065 - 2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVEZleC13TnM3Rlk/view?resourcekey=0-3J3PyHbs-oMFx9WYYNh9HQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVEZleC13TnM3Rlk&resourcekey=0-3J3PyHbs-oMFx9WYYNh9HQ" width="240" alt="1983 - M612A - P025 - SA8-117.jpg"></a><br><sub>1983|16 · P025 - SA8-117</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNjg1UkdocVdHZzg/view?resourcekey=0-DIQz4uEvEn_T3JO4ugkJNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNjg1UkdocVdHZzg&resourcekey=0-DIQz4uEvEn_T3JO4ugkJNA" width="240" alt="1983 - M612A - P026 - SA8-117 - 1-1.jpg"></a><br><sub>1983|16 · P026 - SA8-117 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkFtT1JWUllqVEE/view?resourcekey=0-D60xBRLWoWxp4TN51YnGog" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkFtT1JWUllqVEE&resourcekey=0-D60xBRLWoWxp4TN51YnGog" width="240" alt="1983 - M612A - P027 - SA8-117 - 2-1.jpg"></a><br><sub>1983|16 · P027 - SA8-117 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGVKaENRa0dfaDQ/view?resourcekey=0-QNgFNp2MDWy6KMtQRKLkmA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGVKaENRa0dfaDQ&resourcekey=0-QNgFNp2MDWy6KMtQRKLkmA" width="240" alt="1983 - M612A - P030 - SA14-066.jpg"></a><br><sub>1983|16 · P030 - SA14-066</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0ljTWEzYUk1THM/view?resourcekey=0-nxHrRi2WVnjTdiIcTQtJJQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0ljTWEzYUk1THM&resourcekey=0-nxHrRi2WVnjTdiIcTQtJJQ" width="240" alt="1983 - M612A - P031 - SA14-066 - 1-1.jpg"></a><br><sub>1983|16 · P031 - SA14-066 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTi1QQlhyRGw2XzA/view?resourcekey=0-urNxOrgjwQFRDjpVU-OGPg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTi1QQlhyRGw2XzA&resourcekey=0-urNxOrgjwQFRDjpVU-OGPg" width="240" alt="19xx - M612A - AD - WBSPS - AD - for the engineer who has everything.jpg"></a><br><sub>19xx - M612A - AD - WBSPS - AD - for the engineer who has everything</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKellsWlkwZ1g0RzQ/view?resourcekey=0-ZyV1qWNnrGYTDxlOhvfMNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKellsWlkwZ1g0RzQ&resourcekey=0-ZyV1qWNnrGYTDxlOhvfMNQ" width="240" alt="19xx - M612A - DOC - NS-10 005.jpg"></a><br><sub>19xx - M612A - DOC - NS-10 005</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbjlva3VxcUJxc0k/view?resourcekey=0-O5GHF58-ThJOVOQr42-bNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbjlva3VxcUJxc0k&resourcekey=0-O5GHF58-ThJOVOQr42-bNw" width="240" alt="19xx - M612A - DOC - NS-10 007.jpg"></a><br><sub>19xx - M612A - DOC - NS-10 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQWV5QmItYjdBc0E/view?resourcekey=0-tj5snfLmX_NXcydk2zZK5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQWV5QmItYjdBc0E&resourcekey=0-tj5snfLmX_NXcydk2zZK5g" width="240" alt="19xx - M612A - DOC - NS-10 008.jpg"></a><br><sub>19xx - M612A - DOC - NS-10 008</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M612A - DOC - WBSPS - AD - for the engineer who has everything](https://drive.google.com/file/d/0B0yR0b5T78SKbGlUcFh6b0hqcVE/view?resourcekey=0-ciA_tsM-sD9I8DGfjlKSwA)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1983 - M612A - 12-01-001 - AUDIO DISTRIBUTION AMPLIFIER FUNCTIONAL DIAGRAM.kicad_sch](KICAD/1983%20-%20M612A%20-%2012-01-001%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20FUNCTIONAL%20DIAGRAM.kicad_sch)
- [1983 - M612A - 12-02-002 - AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC.kicad_sch](KICAD/1983%20-%20M612A%20-%2012-02-002%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20SCHEMATIC.kicad_sch)
- [1983 - M612A - 12-02-003 - BYBTEMD TECHNICAL GROUND.kicad_sch](KICAD/1983%20-%20M612A%20-%2012-02-003%20-%20BYBTEMD%20TECHNICAL%20GROUND.kicad_sch)
- [1983 - M612A - 612-01-001 - OVERLOAD REF NORMAL REF.kicad_sch](KICAD/1983%20-%20M612A%20-%20612-01-001%20-%20OVERLOAD%20REF%20NORMAL%20REF.kicad_sch)
- [1983 - M612A - 612-02-002 - INDICATOR DRIVER.kicad_sch](KICAD/1983%20-%20M612A%20-%20612-02-002%20-%20INDICATOR%20DRIVER.kicad_sch)
- [1983 - M612A - 612-02-003 - STAT ION TECHNICAL GROUND INSULATED GROUND BAR TIPLE.kicad_sch](KICAD/1983%20-%20M612A%20-%20612-02-003%20-%20STAT%20ION%20TECHNICAL%20GROUND%20INSULATED%20GROUND%20BAR%20TIPLE.kicad_sch)
- [1983 - M612A - 8-117-02-001 - INDICATOR DRIVER ASSEMBLY SCHEMATIC.kicad_sch](KICAD/1983%20-%20M612A%20-%208-117-02-001%20-%20INDICATOR%20DRIVER%20ASSEMBLY%20SCHEMATIC.kicad_sch)
- [1983 - M612A - 8-117-02-001.kicad_sch](KICAD/1983%20-%20M612A%20-%208-117-02-001.kicad_sch)
- [1983 - M612A - Audio DA (2) p14.kicad_sch](KICAD/1983%20-%20M612A%20-%20Audio%20DA%20(2)%20p14.kicad_sch)
- [1983 - M612A - Audio DA (2) p18.kicad_sch](KICAD/1983%20-%20M612A%20-%20Audio%20DA%20(2)%20p18.kicad_sch)
- [1983 - M612A - Audio DA (2) p35.kicad_sch](KICAD/1983%20-%20M612A%20-%20Audio%20DA%20(2)%20p35.kicad_sch)
- [1983 - M612A - Audio DA p12.kicad_sch](KICAD/1983%20-%20M612A%20-%20Audio%20DA%20p12.kicad_sch)
- [1983 - M612A - Audio DA p14.kicad_sch](KICAD/1983%20-%20M612A%20-%20Audio%20DA%20p14.kicad_sch)
- [1983 - M612A - Audio DA p18.kicad_sch](KICAD/1983%20-%20M612A%20-%20Audio%20DA%20p18.kicad_sch)
- [1983 - M612A - Audio DA p35.kicad_sch](KICAD/1983%20-%20M612A%20-%20Audio%20DA%20p35.kicad_sch)
- [1983 - M612A - [DWG 14-065-02-001] - ASE NOLEH.kicad_sch](KICAD/1983%20-%20M612A%20-%20%5BDWG%2014-065-02-001%5D%20-%20ASE%20NOLEH.kicad_sch)
- [1983 - M612A - [DWG 14-065-02-001] - UNLCS OTHERWISE SPECIFIEO LAST COMPOVENT DESICNATIONS.kicad_sch](KICAD/1983%20-%20M612A%20-%20%5BDWG%2014-065-02-001%5D%20-%20UNLCS%20OTHERWISE%20SPECIFIEO%20LAST%20COMPOVENT%20DESICNATIONS.kicad_sch)
- [1983 - M612A - [DWG 14-066-02-001] - OUTPUT SPLITTER NETWORK SCHEMATIC.kicad_sch](KICAD/1983%20-%20M612A%20-%20%5BDWG%2014-066-02-001%5D%20-%20OUTPUT%20SPLITTER%20NETWORK%20SCHEMATIC.kicad_sch)
- [1983 - M612A - [DWG 14-066-02-001].kicad_sch](KICAD/1983%20-%20M612A%20-%20%5BDWG%2014-066-02-001%5D.kicad_sch)
- [19xx - 8-117-02-001.kicad_sch](KICAD/19xx%20-%208-117-02-001.kicad_sch)
- [19xx - [DWG 14-065-02-001] (2).kicad_sch](KICAD/19xx%20-%20%5BDWG%2014-065-02-001%5D%20(2).kicad_sch)
- [19xx - [DWG 14-065-02-001].kicad_sch](KICAD/19xx%20-%20%5BDWG%2014-065-02-001%5D.kicad_sch)
- [19xx - [DWG 14-066-02-001] (2).kicad_sch](KICAD/19xx%20-%20%5BDWG%2014-066-02-001%5D%20(2).kicad_sch)
- [19xx - [DWG 14-066-02-001].kicad_sch](KICAD/19xx%20-%20%5BDWG%2014-066-02-001%5D.kicad_sch)
- [M612A.kicad_sym](KICAD/M612A.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
