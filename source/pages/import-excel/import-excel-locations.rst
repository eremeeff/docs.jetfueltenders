This tutorial explains how to prepare the Excel file for Import.

Before you begin:

#. Go to the tender invitation page
#. Click on Export and select Export Tender Information
   JetFuelTenders will generate a customized template with tender
   information
#. Open the downloaded Excel file
   This file contains multiple sheets. Bids are entered in the following
   three sheets:

   -  Locations
   -  Volume Base Fees & Taxes
   -  Per Usage Base Fees & Taxes

#. Go to the Locations sheet
   Complete all mandatory fields in this sheet. Use the below
   information to reference the input format.
#. Go to the Volume Base Fees & Taxes
   Input any related fees and taxes for each specific location. One fee
   or tax per row
#. Go to the Per Usage Base Fees & Taxes
   Input any related fees and taxes for each specific location. One fee
   or tax per row
#. When ready, save the Excel document and upload it to
   JetFuelTenders.com by clicking on the Import button on the tender page
   or send this document to the airline via emails.

.. warning::
    Please use the exported Excel file named "Tender Information" for importing bids. Not the "Tender Bids" file, as this file is used to export the bids which have already been input, this document serves are a report after the tender has been completed.

The first 10 columns display the tender requirements for specified
locations (do not edit columns A - J)

This document is based on IATA XML Tender / Bid Fuel Data Standard.

Here is a `sample Excel document <https://www.jetfueltenders.com/documents/4/Test_Import-tender-information.xlsx>`_ which you can use as reference.

.. note::
    The bid importer is not case sensitive, so values can be input in
    lowercase or uppercase.

    You can delete row with the locations which you will not be submitting and only leave the row with the bids. Do not remove any row headers.

Location Sheet - Field Details
==============================

Bid Round\*
-----------

Example value: 1

Description: Numerical identifier of the bid round

--------------

Open Invoice - Payment Terms
----------------------------

Conditional field: Only applicable and mandatory for "Open Invoice"
payments, leave empty if prepayment is required.

Example value: 3

Description: Number of days between payment reference date and payment

--------------

Open Invoice - Payment Reference Date
-------------------------------------

Conditional field: Only applicable and mandatory for "Open Invoice"
payments, leave empty if prepayment is required.

Example value: LD

Description: this field should be populated with one of the following
codes

==== ======================
Code Description
==== ======================
FD   First Delivery Date
ID   Invoice Date
LD   Last Delivery Date
MD   Midpoint Delivery Date
IR   Invoice receiving date
==== ======================

--------------

Open Invoice - Invoice Frequency
--------------------------------

Conditional field: Only applicable and mandatory for "Open Invoice"
payments, leave empty if prepayment is required.

Example value: D/1

Description: this field should be populated with one of the following
codes

==== ==================
Code Description
==== ==================
B/0  Per delivery (B/L)
D/1  Daily
D/3  Every 3 days
M30  Monthly
S/15 Semimonthly
T/10 Every 10 days
W/7  Weekly
Q/4  Quarterly
Q/2  Semiannually
A/1  Annually
==== ==================

--------------

Invoice Type
------------

Example value: PDF

| Description: What format is used for sending invoices?
| This field should be populated with one of the following codes.

========= ===========
Code      Description
========= ===========
XML_3_2_1 XML_3_2_1
XML_3_2_0 XML_3_2_0
XML_3_1_0 XML_3_1_0
XML_3_0_1 XML_3_0_1
XML_3_0_0 XML_3_0_0
XML_2_0_2 XML_2_0_2
EDI       EDI
PPR       Paper
PDF       PDF Format
EXC       Excel
========= ===========

--------------

Prepayment - Number Of Days Prepaid
-----------------------------------

Conditional field: Only applicable and mandatory for "Prepayment", leave
empty if "Open Invoice" is used.

Example value: 3

Description: How many days of deliveries must prepayment cover?

--------------

Prepayment - Payment First Delivery Date
----------------------------------------

Conditional field: Only applicable and mandatory for "Prepayment", leave
empty if "Open Invoice" is used.

Example value: 3

Description: Number of days prior to first delivery that payment is due

--------------

Prepayment - Payment Frequency
------------------------------

Conditional field: Only applicable and mandatory for "Prepayment", leave
empty if "Open Invoice" is used.

Example value: D/1

Description: How often is the prepayment required. This field should be
populated with one of the following codes.

==== ==================
Code Description
==== ==================
B/0  Per delivery (B/L)
D/1  Daily
D/3  Every 3 days
M30  Monthly
S/15 Semimonthly
T/10 Every 10 days
W/7  Weekly
Q/4  Quarterly
Q/2  Semiannually
A/1  Annually
==== ==================

--------------

Prepayment - Amount
-------------------

Conditional field: Only applicable and mandatory for "Prepayment", leave
empty if "Open Invoice" is used.

Example value: 500

Description: Specify the prepayment amount due in payment currency

--------------

Payment Currency\*
------------------

Example value: USD

Description: This field should be populated with one of the following
codes.

==== ========================================================
Code Description
==== ========================================================
USD  United States of America, Dollars
AED  United Arab Emirates, Dirhams
AFN  Afghanistan, Afghani
ALL  Albania, Leke
AMD  Armenia, Drams
ANG  Netherlands Antilles, Guilders
AOA  Angola, Kwanza
ARS  Argentina, Pesos
AUD  Australian dollar
AWG  Aruba, Guilders
AZN  Azerbaijan, New Manats
BAM  Bosnia and Herzegovina, Convertible Marka
BBD  Barbados, Dollars
BDT  Bangladesh, Taka
BGN  Bulgaria, Leva
BHD  Bahrain, Dinars
BIF  Burundi, Francs
BMD  Bermuda, Dollars
BND  Brunei Darussalam, Dollars
BOB  Bolivia, Bolívianos
BRL  Brazil, Brazil Real
BSD  Bahamas, Dollars
BTN  Bhutan, Ngultrum
BWP  Botswana, Pulas
BZD  Belize, Dollars
CAD  Canada, Dollars
CDF  Congo/Kinshasa, Congolese Francs
CHF  Switzerland, Francs
CLP  Chile, Pesos
CNY  China, Yuan Renminbi
COP  Colombia, Pesos
CRC  Costa Rica, Colones
CUC  Cuba Convertible Peso
CUP  Cuba, Pesos
CVE  Cape Verde, Escudos
CZK  Czech Republic, Koruny
DJF  Djibouti, Francs
DKK  Denmark, Kroner
DOP  Dominican Republic, Pesos
DZD  Algeria, Algeria Dinars
EGP  Egypt, Pounds
ERN  Eritrea, Nakfa
ETB  Ethiopia, Birr
EUR  Euro Member Countries, Euro
FJD  Fiji, Dollars
FKP  Falkland Islands (Malvinas), Pounds
GBP  United Kingdom, Pounds
GEL  Georgia, Lari
GGP  Guernsey, Pounds
GHS  Ghana, Cedis
GIP  Gibraltar, Pounds
GMD  Gambia, Dalasi
GNF  Guinean franc
GTQ  Guatemala, Quetzales
GYD  Guyana, Dollars
HKD  Hong Kong, Dollars
HNL  Honduras, Lempiras
HRK  Croatia, Kuna
HTG  Haiti, Gourdes
HUF  Hungary, Forint
IDR  Indonesia, Rupiahs
ILS  Israel, New Shekels
IMP  Isle of Man, Pounds
INR  India, Rupees
IQD  Iraq, Dinars
IRR  Iran, Rials
ISK  Iceland, Kronur
JMD  Jamaica, Dollars
JOD  Jordan, Dinars
JPY  Japan, Yen
KES  Kenya, Shillings
KGS  Kyrgyzstan, Soms
KHR  Cambodia, Riels
KMF  Comoros, Francs
KRW  Korea (South), Won
KWD  Kuwait, Dinars
KYD  Cayman Islands, Dollars
KZT  Kazakhstan, Tenge
LAK  Laos, Kips
LBP  Lebanon, Pounds
LKR  Sri Lanka, Rupees
LRD  Liberia, Dollars
LSL  Lesotho, Maloti
LYD  Libya, Dinars
MAD  Morocco, Dirhams
MDL  Moldova, Lei
MGA  Madagascar, Ariary
MKD  Macedonian denar
MMK  Myanmar (Burma), Kyats
MNT  Mongolia, Tugriks
MOP  Macau, Patacas
MUR  Mauritius, Rupees
MVR  Maldives (Maldive Islands), Rufiyaa
MWK  Malawi, Kwachas
MXN  Mexico, Pesos
MYR  Malaysia, Ringgits
MZN  Mozambique, Meticais
NAD  Namibia, Dollars
NGN  Nigeria, Nairas
NIO  Nicaragua, Cordobas
NOK  Norway, Krone
NPR  Nepal, Nepal Rupees
NZD  New Zealand, Dollars
OMR  Oman, Rials
PAB  Panama, Balboa
PEN  Peru, Nuevos Soles
PGK  Papua New Guinea, Kina
PHP  Philippines, Pesos
PKR  Pakistan, Rupees
PLN  Poland, Zlotych
PYG  Paraguay Guarani
QAR  Qatar, Rials
RON  Romania, New Lei
RSD  Serbia, Dinars
RUB  Russia, Rubles
RWF  Rwanda, Rwanda Francs
SAR  Saudi Arabia, Riyals
SBD  Solomon Islands, Dollars
SCR  Seychelles, Rupees
SDG  Sudan, Pounds
SEK  Sweden, Kronor
SGD  Singapore, Dollars
SHP  Saint Helena, Pounds
SLL  Sierra Leone, Leones
SOS  Somalia, Shillings
SRD  Suriname, Dollars
SYP  Syria, Pounds
SZL  Swaziland, Emalangeni
THB  Thailand, Baht
TJS  Tajikistan, Somoni
TND  Tunisia, Dinars
TOP  Tonga, Pa"anga
TRY  Turkey, New Lira
TTD  Trinidad and Tobago, Dollars
TVD  Tuvalu, Tuvalu Dollars
TWD  Taiwan, New Dollars
TZS  Tanzania, Shillings
UAH  Ukraine, Hryvnia
UGX  Uganda, Shillings
UYU  Uruguay, Pesos
UZS  Uzbekistan, Sums
VND  Viet Nam, Dong
VUV  Vanuatu, Vatu
WST  Samoa, Tala
XAF  Communauté Financière Africaine BEAC, Francs
XCD  East Caribbean Dollars
XDR  International Monetary Fund (IMF) Special Drawing Rights
XOF  Communauté Financière Africaine BCEAO, Francs
XPF  Comptoirs Français du Pacifique Francs
YER  Yemen, Rials
ZAR  South Africa, Rand
==== ========================================================


--------------

Payment Unit\*
--------------

Example value: USG

Description: This field should be populated with one of the following
codes.

==== ===========
Code Description
==== ===========
USG  US Gallons
KG   Kilograms
LBS  Pounds
LTR   Liters
MT   Metric Ton
BBL  Barrels
CBM  Cubic Metre
==== ===========

--------------

Method Of Payment
-----------------

Example value: bank_wire

Description: This field should be populated with one of the following
codes.

=========== ===========
Code        Description
=========== ===========
ach         ACH
bank_wire   Bankwire
check       Check
credit_card Credit Card
=========== ===========

--------------

Guarantees Deposits Required
----------------------------

Example value: Y

Description: Indicate if any bank guarantees or money deposits are
reqired. This field should be populated with one of the following codes.

==== ===========
Code Description
==== ===========
Y    Yes
N    No
==== ===========

--------------

Payment - Exchange Financial Source
-----------------------------------

Example: ARGUS

Description: This field should be populated with one of the following
codes.

============ ===========================================
Code         Description
============ ===========================================
ARGUS        ARGUS
BOCD         Royal Bank of Canada
BOCN         Bank of China
BOJPN        Bank of Japan
BOKO         Bank of Korea
BONG         Central Bank of Nigeria
BORUS        Central Bank of the Russian Federation
BOSA         Bank of South Africa
BOSAR        South African Reserve Bank
BOTOK        Bank of Tokyo
BOTRK        Central Bank of the Republic of Turkey
CSH          CS Holding
BODN         Danish National Bank
DLH          Deutsch Lufthansa
ECB          European Central Bank
EGPC         EGPC
FEOP         Far East Oil Price
FT           Financial Times
GER CB       Deutsche Bundesbank
GLS          Global Insight, Daily Press
INDIAREFBANK Reserve Bank of India
INT          Internal Department
IPE          International Petroleum Exchange
MSCI         Morgan Stanley Capital International
NATREF       National Petroleum Refiners of SA (Pty) Ltd
NYMEX        New York Mercantile Exchange
OPIS         Oil Price Information Service
PLATTS       PLATTS
SAP/IATA     SAP/IATA (internal)
BAMAG        Bank Al Maghreb
BOA          Bank of Africa Group
BOEN         Bank of England
BOPH         Bank of Philippine
BOPOL        Bank of Poland
BOTHA        Bank of Thailand
BLOOMBERG    Bloomberg
BOGIN        Central Bank of Guinea
BOJOR        Central Bank of Jordan
BOMYS        Central Bank of Malaysia
BOSAU        Central Bank of Saudi Arabia
BOTUN        Central Bank of Tunesia
CITI         Citi Bank
BOETH        Comercial Bank of Ethiopia
BOSSD        Comercial Bank of South Sudan
FMDQ         Financial Markets Dealers Association
FT           Financial Times
GLS          Global Insight
MORNINGSTAR  Morningstar
RCAA         RCAA
REUTERS      Reuters
WACFA        West African CFA franc
============ ===========================================

--------------

Payment - Exchange Averaging Method
-----------------------------------

Example value: WT

Description: This field should be populated with one of the following
codes.

==== ================================================
Code Description
==== ================================================
Code Description
WC   Weekly calendar days
WT   Weekly trading days
SC   Semimonthly calendar days
ST   Semimonthly trading days
MC   Monthly calendar days
MT   Monthly trading days
DC   Daily calendar days
IR   Irregular
NC   1st-25th calendar days
NT   1st-25th traded days
FC   Fortnight (11th-25th)/(26th-10th) calendar days
FT   Fortnight (11th-25th)/(26th-10th) traded days
XC   Semimonthly calendar days with deviating average
XT   Semimonthly trading days with deviating average
QC   Quarterly calendar days
QT   Quarterly traded days
M20C Monthly [20] calendar
M20T Monthly [20] traded
==== ================================================

--------------

Payment - Exchange Averaging Offset
-----------------------------------

Example value: N-1

Description: This field should be populated with one of the following
codes.

==== =============================
Code Description
==== =============================
N+0  Current period
N-1  Previous period
N-2  Period before previous period
N+1  Next period
==== =============================

--------------

Supply Conditions Comments
--------------------------

Description: Provide any comments related to the supply conditions

--------------

Delivery Point\*
----------------

Example value: Ex-hydrant

Description: This field should be populated with one of the following
codes.

============= =============
Code          Description
============= =============
Ex-hydrant    EX-hydrant
Ex-Rack       Ex-Rack
Into wing     Into wing
Into storage  Into storage
Into pipeline Into pipeline
============= =============

--------------

Index - Provider
----------------

Conditional field: Only applicable and mandatory for Index based prices,
leave empty if this location uses market price base.

Example value: Platts

Description: This field should be populated with one of the following
codes.

====== ===========
Code   Description
====== ===========
Platts Platts
Argus  Argus
Opis   Opis
DDS    DDS
Other  Other
====== ===========

--------------

Index - Code
------------

Example value: AAFIY00h

Description: None that the index bate is specified as the last later of
the code. There are 3 options available `c` for close `h` for high and `l` for low. This
field should be populated with one of the following codes.

+----------+----------------+----------------------------------------+
| Provider | Provider code  | Description                            |
+----------+----------------+----------------------------------------+
| Platts   | AAFIY00c       | Jet Kero C+F Australia Cargo Close     |
+----------+----------------+----------------------------------------+
| Platts   | AAIDL00c       | Jet FOB Med Cargo Close                |
+----------+----------------+----------------------------------------+
| Platts   | AAIDN00c       | Jet FOB Med Premium Cargo Close        |
+----------+----------------+----------------------------------------+
| Platts   | AAJNL00c       | Jet Kero New Jersey Buckeye Pipeline   |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | AAKNZ00c       | Jet Kero LR2 FOB Arab Gulf Cargo Close |
+----------+----------------+----------------------------------------+
| Platts   | AAQWL00c       | Jet Kero MOP West India $/bbl Close    |
+----------+----------------+----------------------------------------+
| Platts   | AAQWM00c       | Jet Kero MOP West India $/mt Close     |
+----------+----------------+----------------------------------------+
| Platts   | AAVTH00c       | Jet Kero ULS New York Harbor Cargo     |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | AAVTI00c       | Jet Kero ULS New York Harbor Barge     |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | AAVTJ00c       | Jet Kero ULS Boston Cargo Close        |
+----------+----------------+----------------------------------------+
| Platts   | AAVTK00c       | Jet Kero ULS USGC Waterborne Close     |
+----------+----------------+----------------------------------------+
| Platts   | AAVTL00c       | Jet Kero ULS USGC Prompt Pipeline      |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | AAXPV00c       | Jet Kero 54 USAC Linden Pipeline       |
|          |                | prompt cycle assessment Close          |
+----------+----------------+----------------------------------------+
| Platts   | AAZBN00c       | Jet CIF Med Cargo Close                |
+----------+----------------+----------------------------------------+
| Platts   | PJAAA00c       | Jet Kero FOB Arab Gulf Cargo Close     |
+----------+----------------+----------------------------------------+
| Platts   | PJAAD00c       | Jet Kero Caribbean Cargo $/mt Close    |
+----------+----------------+----------------------------------------+
| Platts   | PJAAD10c       | Jet Kero Caribbean Cargo cts/gal Close |
+----------+----------------+----------------------------------------+
| Platts   | PJAAF00c       | Jet Kero FOB Chicago Pipe Close        |
+----------+----------------+----------------------------------------+
| Platts   | PJAAI00c       | Jet Kero Group 3 Pipeline Close        |
+----------+----------------+----------------------------------------+
| Platts   | PJAAN00c       | Jet Kero C+F Japan Cargo Close         |
+----------+----------------+----------------------------------------+
| Platts   | PJAAP00c       | Jet Kero Los Angeles CA Pipeline Close |
+----------+----------------+----------------------------------------+
| Platts   | PJAAU00c       | Jet CIF NWE Cargo Close                |
+----------+----------------+----------------------------------------+
| Platts   | PJAAV00c       | Jet FOB NWE Cargo Close                |
+----------+----------------+----------------------------------------+
| Platts   | PJAAW00c       | Jet Kero New York Harbor Barge Close   |
+----------+----------------+----------------------------------------+
| Platts   | PJAAX00c       | Jet Kero New York Harbor Cargo Close   |
+----------+----------------+----------------------------------------+
| Platts   | PJABA00c       | Jet FOB Rdam Barge Close               |
+----------+----------------+----------------------------------------+
| Platts   | PJABC00c       | Jet Kero San Francisco CA Pipeline     |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | PJABF00c       | Jet Kero FOB Spore Cargo Close         |
+----------+----------------+----------------------------------------+
| Platts   | PJABI00c       | Jet Kero USWC Waterborne Close         |
+----------+----------------+----------------------------------------+
| Platts   | PJABJ00c       | Jet Kero LS New York Harbor Barge      |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | PJABK00c       | Jet Kero LS New York Harbor Cargo      |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | PJABL00c       | Jet Kero LS Boston Cargo Close         |
+----------+----------------+----------------------------------------+
| Platts   | PJABM00c       | Jet Kero 54 USGC Waterborne Close      |
+----------+----------------+----------------------------------------+
| Platts   | PJABN00c       | Jet Kero 55 USGC Waterborne Close      |
+----------+----------------+----------------------------------------+
| Platts   | PJABO00c       | Jet Kero 54 USGC Prompt Pipeline Close |
+----------+----------------+----------------------------------------+
| Platts   | PJABP00c       | Jet Kero 55 USGC Prompt Pipeline Close |
+----------+----------------+----------------------------------------+
| Platts   | PJABQ00c       | Jet Kero C+F South China Cargo Close   |
+----------+----------------+----------------------------------------+
| Platts   | PJACB00c       | Jet Kero ULS No1 Group 3 Pipeline      |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | PJACD00c       | Jet Kero ULS No1 FOB Chicago Pipe      |
|          |                | Close                                  |
+----------+----------------+----------------------------------------+
| Platts   | PJADG00c       | Jet Kero FOB Korea Cargo Close         |
+----------+----------------+----------------------------------------+
| Platts   | PTAEO09c       | Jet Carib Shell W Close                |
+----------+----------------+----------------------------------------+
| Platts   | AAFIY00h       | Jet Kero C+F Australia Cargo High      |
+----------+----------------+----------------------------------------+
| Platts   | AAIDL00h       | Jet FOB Med Cargo High                 |
+----------+----------------+----------------------------------------+
| Platts   | AAIDN00h       | Jet FOB Med Premium Cargo High         |
+----------+----------------+----------------------------------------+
| Platts   | AAJNL00h       | Jet Kero New Jersey Buckeye Pipeline   |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Platts   | AAKNZ00h       | Jet Kero LR2 FOB Arab Gulf Cargo High  |
+----------+----------------+----------------------------------------+
| Platts   | AAQWL00h       | Jet Kero MOP West India $/bbl High     |
+----------+----------------+----------------------------------------+
| Platts   | AAQWM00h       | Jet Kero MOP West India $/mt High      |
+----------+----------------+----------------------------------------+
| Platts   | AAVTH00h       | Jet Kero ULS New York Harbor Cargo     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Platts   | AAVTI00h       | Jet Kero ULS New York Harbor Barge     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Platts   | AAVTJ00h       | Jet Kero ULS Boston Cargo High         |
+----------+----------------+----------------------------------------+
| Platts   | AAVTK00h       | Jet Kero ULS USGC Waterborne High      |
+----------+----------------+----------------------------------------+
| Platts   | AAVTL00h       | Jet Kero ULS USGC Prompt Pipeline High |
+----------+----------------+----------------------------------------+
| Platts   | AAXPV00h       | Jet Kero 54 USAC Linden Pipeline       |
|          |                | prompt cycle assessment High           |
+----------+----------------+----------------------------------------+
| Platts   | AAZBN00h       | Jet CIF Med Cargo High                 |
+----------+----------------+----------------------------------------+
| Platts   | PJAAA00h       | Jet Kero FOB Arab Gulf Cargo High      |
+----------+----------------+----------------------------------------+
| Platts   | PJAAD00h       | Jet Kero Caribbean Cargo $/mt High     |
+----------+----------------+----------------------------------------+
| Platts   | PJAAD10h       | Jet Kero Caribbean Cargo cts/gal High  |
+----------+----------------+----------------------------------------+
| Platts   | PJAAF00h       | Jet Kero FOB Chicago Pipe High         |
+----------+----------------+----------------------------------------+
| Platts   | PJAAI00h       | Jet Kero Group 3 Pipeline High         |
+----------+----------------+----------------------------------------+
| Platts   | PJAAN00h       | Jet Kero C+F Japan Cargo High          |
+----------+----------------+----------------------------------------+
| Platts   | PJAAP00h       | Jet Kero Los Angeles CA Pipeline High  |
+----------+----------------+----------------------------------------+
| Platts   | PJAAU00h       | Jet CIF NWE Cargo High                 |
+----------+----------------+----------------------------------------+
| Platts   | PJAAV00h       | Jet FOB NWE Cargo High                 |
+----------+----------------+----------------------------------------+
| Platts   | PJAAW00h       | Jet Kero New York Harbor Barge High    |
+----------+----------------+----------------------------------------+
| Platts   | PJAAX00h       | Jet Kero New York Harbor Cargo High    |
+----------+----------------+----------------------------------------+
| Platts   | PJABA00h       | Jet FOB Rdam Barge High                |
+----------+----------------+----------------------------------------+
| Platts   | PJABC00h       | Jet Kero San Francisco CA Pipeline     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Platts   | PJABF00h       | Jet Kero FOB Spore Cargo High          |
+----------+----------------+----------------------------------------+
| Platts   | PJABI00h       | Jet Kero USWC Waterborne High          |
+----------+----------------+----------------------------------------+
| Platts   | PJABJ00h       | Jet Kero LS New York Harbor Barge High |
+----------+----------------+----------------------------------------+
| Platts   | PJABK00h       | Jet Kero LS New York Harbor Cargo High |
+----------+----------------+----------------------------------------+
| Platts   | PJABL00h       | Jet Kero LS Boston Cargo High          |
+----------+----------------+----------------------------------------+
| Platts   | PJABM00h       | Jet Kero 54 USGC Waterborne High       |
+----------+----------------+----------------------------------------+
| Platts   | PJABN00h       | Jet Kero 55 USGC Waterborne High       |
+----------+----------------+----------------------------------------+
| Platts   | PJABO00h       | Jet Kero 54 USGC Prompt Pipeline High  |
+----------+----------------+----------------------------------------+
| Platts   | PJABP00h       | Jet Kero 55 USGC Prompt Pipeline High  |
+----------+----------------+----------------------------------------+
| Platts   | PJABQ00h       | Jet Kero C+F South China Cargo High    |
+----------+----------------+----------------------------------------+
| Platts   | PJACB00h       | Jet Kero ULS No1 Group 3 Pipeline High |
+----------+----------------+----------------------------------------+
| Platts   | PJACD00h       | Jet Kero ULS No1 FOB Chicago Pipe High |
+----------+----------------+----------------------------------------+
| Platts   | PJADG00h       | Jet Kero FOB Korea Cargo High          |
+----------+----------------+----------------------------------------+
| Platts   | PTAEO09h       | Jet Carib Shell W High                 |
+----------+----------------+----------------------------------------+
| Platts   | AAFIY00l       | Jet Kero C+F Australia Cargo Low       |
+----------+----------------+----------------------------------------+
| Platts   | AAIDL00l       | Jet FOB Med Cargo Low                  |
+----------+----------------+----------------------------------------+
| Platts   | AAIDN00l       | Jet FOB Med Premium Cargo Low          |
+----------+----------------+----------------------------------------+
| Platts   | AAJNL00l       | Jet Kero New Jersey Buckeye Pipeline   |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Platts   | AAKNZ00l       | Jet Kero LR2 FOB Arab Gulf Cargo Low   |
+----------+----------------+----------------------------------------+
| Platts   | AAQWL00l       | Jet Kero MOP West India $/bbl Low      |
+----------+----------------+----------------------------------------+
| Platts   | AAQWM00l       | Jet Kero MOP West India $/mt Low       |
+----------+----------------+----------------------------------------+
| Platts   | AAVTH00l       | Jet Kero ULS New York Harbor Cargo Low |
+----------+----------------+----------------------------------------+
| Platts   | AAVTI00l       | Jet Kero ULS New York Harbor Barge Low |
+----------+----------------+----------------------------------------+
| Platts   | AAVTJ00l       | Jet Kero ULS Boston Cargo Low          |
+----------+----------------+----------------------------------------+
| Platts   | AAVTK00l       | Jet Kero ULS USGC Waterborne Low       |
+----------+----------------+----------------------------------------+
| Platts   | AAVTL00l       | Jet Kero ULS USGC Prompt Pipeline Low  |
+----------+----------------+----------------------------------------+
| Platts   | AAXPV00l       | Jet Kero 54 USAC Linden Pipeline       |
|          |                | prompt cycle assessment Low            |
+----------+----------------+----------------------------------------+
| Platts   | AAZBN00l       | Jet CIF Med Cargo Low                  |
+----------+----------------+----------------------------------------+
| Platts   | PJAAA00l       | Jet Kero FOB Arab Gulf Cargo Low       |
+----------+----------------+----------------------------------------+
| Platts   | PJAAD00l       | Jet Kero Caribbean Cargo $/mt Low      |
+----------+----------------+----------------------------------------+
| Platts   | PJAAD10l       | Jet Kero Caribbean Cargo cts/gal Low   |
+----------+----------------+----------------------------------------+
| Platts   | PJAAF00l       | Jet Kero FOB Chicago Pipe Low          |
+----------+----------------+----------------------------------------+
| Platts   | PJAAI00l       | Jet Kero Group 3 Pipeline Low          |
+----------+----------------+----------------------------------------+
| Platts   | PJAAN00l       | Jet Kero C+F Japan Cargo Low           |
+----------+----------------+----------------------------------------+
| Platts   | PJAAP00l       | Jet Kero Los Angeles CA Pipeline Low   |
+----------+----------------+----------------------------------------+
| Platts   | PJAAU00l       | Jet CIF NWE Cargo Low                  |
+----------+----------------+----------------------------------------+
| Platts   | PJAAV00l       | Jet FOB NWE Cargo Low                  |
+----------+----------------+----------------------------------------+
| Platts   | PJAAW00l       | Jet Kero New York Harbor Barge Low     |
+----------+----------------+----------------------------------------+
| Platts   | PJAAX00l       | Jet Kero New York Harbor Cargo Low     |
+----------+----------------+----------------------------------------+
| Platts   | PJABA00l       | Jet FOB Rdam Barge Low                 |
+----------+----------------+----------------------------------------+
| Platts   | PJABC00l       | Jet Kero San Francisco CA Pipeline Low |
+----------+----------------+----------------------------------------+
| Platts   | PJABF00l       | Jet Kero FOB Spore Cargo Low           |
+----------+----------------+----------------------------------------+
| Platts   | PJABI00l       | Jet Kero USWC Waterborne Low           |
+----------+----------------+----------------------------------------+
| Platts   | PJABJ00l       | Jet Kero LS New York Harbor Barge Low  |
+----------+----------------+----------------------------------------+
| Platts   | PJABK00l       | Jet Kero LS New York Harbor Cargo Low  |
+----------+----------------+----------------------------------------+
| Platts   | PJABL00l       | Jet Kero LS Boston Cargo Low           |
+----------+----------------+----------------------------------------+
| Platts   | PJABM00l       | Jet Kero 54 USGC Waterborne Low        |
+----------+----------------+----------------------------------------+
| Platts   | PJABN00l       | Jet Kero 55 USGC Waterborne Low        |
+----------+----------------+----------------------------------------+
| Platts   | PJABO00l       | Jet Kero 54 USGC Prompt Pipeline Low   |
+----------+----------------+----------------------------------------+
| Platts   | PJABP00l       | Jet Kero 55 USGC Prompt Pipeline Low   |
+----------+----------------+----------------------------------------+
| Platts   | PJABQ00l       | Jet Kero C+F South China Cargo Low     |
+----------+----------------+----------------------------------------+
| Platts   | PJACB00l       | Jet Kero ULS No1 Group 3 Pipeline Low  |
+----------+----------------+----------------------------------------+
| Platts   | PJACD00l       | Jet Kero ULS No1 FOB Chicago Pipe Low  |
+----------+----------------+----------------------------------------+
| Platts   | PJADG00l       | Jet Kero FOB Korea Cargo Low           |
+----------+----------------+----------------------------------------+
| Platts   | PTAEO09l       | Jet Carib Shell W Low                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0003951-2    | Jet fuel Buckeye pipe fob High         |
+----------+----------------+----------------------------------------+
| Argus    | PA0002901-2    | Jet fuel Chicago pipe fob cycle High   |
+----------+----------------+----------------------------------------+
| Argus    | PA0002760-2    | Jet fuel Colonial 54 pipe fob cycle    |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0004245-2    | Jet fuel Colonial 54 pipe fob wtd avg  |
|          |                | cycle High                             |
+----------+----------------+----------------------------------------+
| Argus    | PA0003948-2    | Jet fuel Group 3 Magellan Q pipe fob   |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001024-2    | Jet fuel LA pipe fob month High        |
+----------+----------------+----------------------------------------+
| Argus    | PA0018544-2    | Jet fuel LA pipe fob wtd avg month     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0003953-2    | Jet fuel Laurel pipe fob High          |
+----------+----------------+----------------------------------------+
| Argus    | PA0001011-2    | Jet fuel NYH barge fob 10 days fwd     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001012-2    | Jet fuel NYH barge fob 15 days fwd     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0002147-2    | Jet fuel NYH barge fob 20 days fwd     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001010-2    | Jet fuel NYH barge fob prompt High     |
+----------+----------------+----------------------------------------+
| Argus    | PA0005171-2    | Jet fuel NYH cargo del High            |
+----------+----------------+----------------------------------------+
| Argus    | PA0014711-2    | Jet fuel NYH offline Colonial 54 pipe  |
|          |                | del cycle                              |
+----------+----------------+----------------------------------------+
| Argus    | PA0001027-2    | Jet fuel SF pipe fob month             |
+----------+----------------+----------------------------------------+
| Argus    | PA0003945-2    | Jet fuel USGC waterborne fob           |
+----------+----------------+----------------------------------------+
| Argus    | PA0015003-2    | Jet Orsk - Kazakhstan (Aktobe) del     |
|          |                | price index High                       |
+----------+----------------+----------------------------------------+
| Argus    | PA0015002-2    | Jet Orsk - Kazakhstan (Alma-Ata) del   |
|          |                | price index High                       |
+----------+----------------+----------------------------------------+
| Argus    | PA0015001-2    | Jet Orsk - Kazakhstan (Astana) del     |
|          |                | price index High                       |
+----------+----------------+----------------------------------------+
| Argus    | PA0015004-2    | Jet Orsk - Kazakhstan (Atyrau) del     |
|          |                | price index High                       |
+----------+----------------+----------------------------------------+
| Argus    | PA0015005-2    | Jet Orsk - Kazakhstan (Karaganda) del  |
|          |                | price index High                       |
+----------+----------------+----------------------------------------+
| Argus    | PA0015006-2    | Jet Orsk - Kazakhstan (Uralsk) del     |
|          |                | price index High                       |
+----------+----------------+----------------------------------------+
| Argus    | PA0015007-2    | Jet Orsk - Kazakhstan                  |
|          |                | (Ust-Kamenogorsk) del price index High |
+----------+----------------+----------------------------------------+
| Argus    | PA0018005-2    | Jet/kerosine c+f Durban High           |
+----------+----------------+----------------------------------------+
| Argus    | PA0005630-2    | Jet/Kerosine Chimkent High             |
+----------+----------------+----------------------------------------+
| Argus    | PA0018507-2    | Jet/kerosine delivered west Africa $/t |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0015000-2    | Jet/Kerosine fca Orsk High             |
+----------+----------------+----------------------------------------+
| Argus    | PA0009049-2    | Jet/Kerosine fit Moscow spot ex. VAT   |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0009048-2    | Jet/Kerosine fit Moscow spot incl. VAT |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001016-2    | Jet/kerosine Japan c+f High            |
+----------+----------------+----------------------------------------+
| Argus    | PA0001017-2    | Jet/kerosine Mideast Gulf fob High     |
+----------+----------------+----------------------------------------+
| Argus    | PA0007734-2    | Jet/Kerosine Moscow formula ex. VAT    |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0007733-2    | Jet/Kerosine Moscow formula incl. VAT  |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001025-2    | Jet/kerosine NWE barge High            |
+----------+----------------+----------------------------------------+
| Argus    | PA0001018-2    | Jet/kerosine NWE cif High              |
+----------+----------------+----------------------------------------+
| Argus    | PA0001026-2    | Jet/kerosine NWE fob High              |
+----------+----------------+----------------------------------------+
| Argus    | PA0005631-2    | Jet/Kerosine Pavlodar High             |
+----------+----------------+----------------------------------------+
| Argus    | PA0005336-2    | Jet/kerosine S Korea High              |
+----------+----------------+----------------------------------------+
| Argus    | PA0001019-2    | Jet/kerosine Singapore High            |
+----------+----------------+----------------------------------------+
| Argus    | PA0010050-2    | Jet/Kerosine SPIMEX Index High         |
+----------+----------------+----------------------------------------+
| Argus    | PA0009545-2    | Jet/kerosine W Med cif High            |
+----------+----------------+----------------------------------------+
| Argus    | PA0009549-2    | Jet/kerosine W Med cif diff to Jet fob |
|          |                | W Med High                             |
+----------+----------------+----------------------------------------+
| Argus    | PA0001021-2    | Jet/kerosine W Med fob High            |
+----------+----------------+----------------------------------------+
| Argus    | PA0003952-2    | Kerosine Buckeye pipe fob High         |
+----------+----------------+----------------------------------------+
| Argus    | PA0016541-2    | Kerosine Buckeye pipe fob (AST) High   |
+----------+----------------+----------------------------------------+
| Argus    | PA0016533-2    | Kerosine Colonial 55 pipe fob (AST)    |
|          |                | cycle High                             |
+----------+----------------+----------------------------------------+
| Argus    | PA0002762-2    | Kerosine Colonial 55 pipe fob cycle    |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001014-2    | Kerosine NYH barge fob 10 days fwd     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0002148-2    | Kerosine NYH barge fob 15 days fwd     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0002149-2    | Kerosine NYH barge fob 20 days fwd     |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001015-2    | Kerosine NYH barge fob prompt High     |
+----------+----------------+----------------------------------------+
| Argus    | PA0016523-2    | Kerosine NYH barge fob prompt (AST)    |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001022-2    | Kerosine NYH cargo del High            |
+----------+----------------+----------------------------------------+
| Argus    | PA0016567-2    | Kerosine ULSK Chicago pipe fob (AST)   |
|          |                | cycle High                             |
+----------+----------------+----------------------------------------+
| Argus    | PA0004980-2    | Kerosine ULSK Chicago pipe fob cycle   |
|          |                | High                                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0004979-2    | Kerosine ULSK Group 3 Magellan Y pipe  |
|          |                | fob prompt High                        |
+----------+----------------+----------------------------------------+
| Argus    | PA0016566-2    | Kerosine ULSK Group 3 Magellan Y pipe  |
|          |                | fob prompt (AST) High                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0004977-2    | Kerosine ULSK NYH barge fob High       |
+----------+----------------+----------------------------------------+
| Argus    | PA0016565-2    | Kerosine ULSK NYH barge fob (AST) High |
+----------+----------------+----------------------------------------+
| Argus    | PA0004978-2    | Kerosine ULSK NYH cargo del High       |
+----------+----------------+----------------------------------------+
| Argus    | PA0001020-2    | Kerosine USGC waterborne fob High      |
+----------+----------------+----------------------------------------+
| Argus    | PA0003951-1    | Jet fuel Buckeye pipe fob Low          |
+----------+----------------+----------------------------------------+
| Argus    | PA0002901-1    | Jet fuel Chicago pipe fob cycle Low    |
+----------+----------------+----------------------------------------+
| Argus    | PA0002760-1    | Jet fuel Colonial 54 pipe fob cycle    |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0004245-1    | Jet fuel Colonial 54 pipe fob wtd avg  |
|          |                | cycle Low                              |
+----------+----------------+----------------------------------------+
| Argus    | PA0003948-1    | Jet fuel Group 3 Magellan Q pipe fob   |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0001024-1    | Jet fuel LA pipe fob month Low         |
+----------+----------------+----------------------------------------+
| Argus    | PA0018544-1    | Jet fuel LA pipe fob wtd avg month Low |
+----------+----------------+----------------------------------------+
| Argus    | PA0003953-1    | Jet fuel Laurel pipe fob Low           |
+----------+----------------+----------------------------------------+
| Argus    | PA0001011-1    | Jet fuel NYH barge fob 10 days fwd Low |
+----------+----------------+----------------------------------------+
| Argus    | PA0001012-1    | Jet fuel NYH barge fob 15 days fwd Low |
+----------+----------------+----------------------------------------+
| Argus    | PA0002147-1    | Jet fuel NYH barge fob 20 days fwd Low |
+----------+----------------+----------------------------------------+
| Argus    | PA0001010-1    | Jet fuel NYH barge fob prompt Low      |
+----------+----------------+----------------------------------------+
| Argus    | PA0005171-1    | Jet fuel NYH cargo del Low             |
+----------+----------------+----------------------------------------+
| Argus    | PA0014711-1    | Jet fuel NYH offline Colonial 54 pipe  |
|          |                | del cycle Low                          |
+----------+----------------+----------------------------------------+
| Argus    | PA0001027-1    | Jet fuel SF pipe fob month Low         |
+----------+----------------+----------------------------------------+
| Argus    | PA0003945-1    | Jet fuel USGC waterborne fob Low       |
+----------+----------------+----------------------------------------+
| Argus    | PA0015003-1    | Jet Orsk - Kazakhstan (Aktobe) del     |
|          |                | price index Low                        |
+----------+----------------+----------------------------------------+
| Argus    | PA0015002-1    | Jet Orsk - Kazakhstan (Alma-Ata) del   |
|          |                | price index Low                        |
+----------+----------------+----------------------------------------+
| Argus    | PA0015001-1    | Jet Orsk - Kazakhstan (Astana) del     |
|          |                | price index Low                        |
+----------+----------------+----------------------------------------+
| Argus    | PA0015004-1    | Jet Orsk - Kazakhstan (Atyrau) del     |
|          |                | price index Low                        |
+----------+----------------+----------------------------------------+
| Argus    | PA0015005-1    | Jet Orsk - Kazakhstan (Karaganda) del  |
|          |                | price index Low                        |
+----------+----------------+----------------------------------------+
| Argus    | PA0015006-1    | Jet Orsk - Kazakhstan (Uralsk) del     |
|          |                | price index Low                        |
+----------+----------------+----------------------------------------+
| Argus    | PA0015007-1    | Jet Orsk - Kazakhstan                  |
|          |                | (Ust-Kamenogorsk) del price index Low  |
+----------+----------------+----------------------------------------+
| Argus    | PA0018005-1    | Jet/kerosine c+f Durban Low            |
+----------+----------------+----------------------------------------+
| Argus    | PA0005630-1    | Jet/Kerosine Chimkent Low              |
+----------+----------------+----------------------------------------+
| Argus    | PA0018507-1    | Jet/kerosine delivered west Africa $/t |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0015000-1    | Jet/Kerosine fca Orsk Low              |
+----------+----------------+----------------------------------------+
| Argus    | PA0009049-1    | Jet/Kerosine fit Moscow spot ex. VAT   |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0009048-1    | Jet/Kerosine fit Moscow spot incl. VAT |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0001016-1    | Jet/kerosine Japan c+f Low             |
+----------+----------------+----------------------------------------+
| Argus    | PA0001017-1    | Jet/kerosine Mideast Gulf fob Low      |
+----------+----------------+----------------------------------------+
| Argus    | PA0007734-1    | Jet/Kerosine Moscow formula ex. VAT    |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0007733-1    | Jet/Kerosine Moscow formula incl. VAT  |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0001025-1    | Jet/kerosine NWE barge Low             |
+----------+----------------+----------------------------------------+
| Argus    | PA0001018-1    | Jet/kerosine NWE cif Low               |
+----------+----------------+----------------------------------------+
| Argus    | PA0001026-1    | Jet/kerosine NWE fob Low               |
+----------+----------------+----------------------------------------+
| Argus    | PA0005631-1    | Jet/Kerosine Pavlodar Low              |
+----------+----------------+----------------------------------------+
| Argus    | PA0005336-1    | Jet/kerosine S Korea Low               |
+----------+----------------+----------------------------------------+
| Argus    | PA0001019-1    | Jet/kerosine Singapore Low             |
+----------+----------------+----------------------------------------+
| Argus    | PA0010050-1    | Jet/Kerosine SPIMEX Index Low          |
+----------+----------------+----------------------------------------+
| Argus    | PA0009545-1    | Jet/kerosine W Med cif Low             |
+----------+----------------+----------------------------------------+
| Argus    | PA0009549-1    | Jet/kerosine W Med cif diff to Jet fob |
|          |                | W Med Low                              |
+----------+----------------+----------------------------------------+
| Argus    | PA0001021-1    | Jet/kerosine W Med fob Low             |
+----------+----------------+----------------------------------------+
| Argus    | PA0003952-1    | Kerosine Buckeye pipe fob Low          |
+----------+----------------+----------------------------------------+
| Argus    | PA0016541-1    | Kerosine Buckeye pipe fob (AST) Low    |
+----------+----------------+----------------------------------------+
| Argus    | PA0016533-1    | Kerosine Colonial 55 pipe fob (AST)    |
|          |                | cycle Low                              |
+----------+----------------+----------------------------------------+
| Argus    | PA0002762-1    | Kerosine Colonial 55 pipe fob cycle    |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0001014-1    | Kerosine NYH barge fob 10 days fwd Low |
+----------+----------------+----------------------------------------+
| Argus    | PA0002148-1    | Kerosine NYH barge fob 15 days fwd Low |
+----------+----------------+----------------------------------------+
| Argus    | PA0002149-1    | Kerosine NYH barge fob 20 days fwd Low |
+----------+----------------+----------------------------------------+
| Argus    | PA0001015-1    | Kerosine NYH barge fob prompt Low      |
+----------+----------------+----------------------------------------+
| Argus    | PA0016523-1    | Kerosine NYH barge fob prompt (AST)    |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0001022-1    | Kerosine NYH cargo del Low             |
+----------+----------------+----------------------------------------+
| Argus    | PA0016567-1    | Kerosine ULSK Chicago pipe fob (AST)   |
|          |                | cycle Low                              |
+----------+----------------+----------------------------------------+
| Argus    | PA0004980-1    | Kerosine ULSK Chicago pipe fob cycle   |
|          |                | Low                                    |
+----------+----------------+----------------------------------------+
| Argus    | PA0004979-1    | Kerosine ULSK Group 3 Magellan Y pipe  |
|          |                | fob prompt Low                         |
+----------+----------------+----------------------------------------+
| Argus    | PA0016566-1    | Kerosine ULSK Group 3 Magellan Y pipe  |
|          |                | fob prompt (AST) Low                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0004977-1    | Kerosine ULSK NYH barge fob Low        |
+----------+----------------+----------------------------------------+
| Argus    | PA0016565-1    | Kerosine ULSK NYH barge fob (AST) Low  |
+----------+----------------+----------------------------------------+
| Argus    | PA0004978-1    | Kerosine ULSK NYH cargo del Low        |
+----------+----------------+----------------------------------------+
| Argus    | PA0001020-1    | Kerosine USGC waterborne fob Low       |
+----------+----------------+----------------------------------------+
| Opis     | JETKEROAGLR1   | Jet Kerosene FOB Arab Gulf LR1         |
+----------+----------------+----------------------------------------+
| Opis     | JETKEROAGLR2   | Jet Kerosene FOB Arab Gulf LR2         |
+----------+----------------+----------------------------------------+
| Opis     | JETKEROKOR     | Jet Kerosene FOB Korea                 |
+----------+----------------+----------------------------------------+
| Opis     | JETTAIW        | Jet Kerosene FOB Taiwan                |
+----------+----------------+----------------------------------------+
| Opis     | JETKEROSING    | Jet Kerosene Singapore                 |
+----------+----------------+----------------------------------------+
| Opis     | JETNWECGCIF    | Jet Fuel Northwest Europe Cargo Cif    |
+----------+----------------+----------------------------------------+
| Opis     | JETNWECGFOB    | Jet Fuel Northwest Europe Cargo FOB    |
+----------+----------------+----------------------------------------+
| Opis     | JETRTDBG       | Jet Fuel Rotterdam Barge FOB           |
+----------+----------------+----------------------------------------+
| Opis     | JETMEDCG       | Jet Fuel Mediterranean Cargo FOB       |
+----------+----------------+----------------------------------------+
| Opis     | JET450RTDBG    | Jet Fuel OPIS450 Rdam Barge            |
+----------+----------------+----------------------------------------+
| Opis     | JET450DFSRTDBG | Jet Fuel OPIS450 Rdam Barge            |
|          |                | Diff+Settle                            |
+----------+----------------+----------------------------------------+
| Opis     | KEROBUCPL      | 55 Grade Kerosene Buckeye Pipeline     |
|          |                | (NY)                                   |
+----------+----------------+----------------------------------------+
| Opis     | JETBUCPL       | Jet 54 Grade Buckeye Pipeline (NY)     |
+----------+----------------+----------------------------------------+
| Opis     | JETCHIPL       | Jet 54 Grade Chicago                   |
+----------+----------------+----------------------------------------+
| Opis     | JETGR3PL       | Jet 54 Grade Group 3                   |
+----------+----------------+----------------------------------------+
| Opis     | KEROUSGPL      | 55 Grade Kerosene Gulf Coast           |
+----------+----------------+----------------------------------------+
| Opis     | JETUSGPL       | Jet 54 Grade Gulf Coast                |
+----------+----------------+----------------------------------------+
| Opis     | ULSKUSGPL      | Ultra Low Sulfur Kerosene Gulf Coast   |
+----------+----------------+----------------------------------------+
| Opis     | KEROUSGBG      | 55 Grade Kerosene Gulf Coast           |
|          |                | Waterborne                             |
+----------+----------------+----------------------------------------+
| Opis     | JETUSGBG       | Jet 54 Grade Gulf Coast Waterborne     |
+----------+----------------+----------------------------------------+
| Opis     | JETLAUPL       | Jet 54 Grade Laurel Pipeline           |
+----------+----------------+----------------------------------------+
| Opis     | JETLINPL       | Jet 54 Grade Linden Junction           |
+----------+----------------+----------------------------------------+
| Opis     | JETLAXPL       | Jet LAX Los Angeles                    |
+----------+----------------+----------------------------------------+
| Opis     | JETNYBG        | Jet 54 Grade NY Harbor Barge           |
+----------+----------------+----------------------------------------+
| Opis     | KERONYBG       | 55 Grade Kerosene NY Harbor Barge      |
+----------+----------------+----------------------------------------+
| Opis     | ULSKNYBG       | Ultra Low Sulfur Kerosene NY Harbor    |
|          |                | Barge                                  |
+----------+----------------+----------------------------------------+
| Opis     | JETNYCG        | Jet 54 Grade NY Harbor Cargo           |
+----------+----------------+----------------------------------------+
| Opis     | JETPNWBG       | Jet 54 Grade Pacific Northwest         |
+----------+----------------+----------------------------------------+
| Opis     | JETSFPL        | Jet 54 Grade San Francisco             |
+----------+----------------+----------------------------------------+


--------------

Index - Averaging Method
------------------------

Conditional field: Only applicable and mandatory for Index based prices,
leave empty if this location uses market price base.

Example value: WT

Description: This field should be populated with one of the following
codes.

==== ================================================
Code Description
==== ================================================
WC   Weekly calendar days
WT   Weekly trading days
SC   Semimonthly calendar days
ST   Semimonthly trading days
MC   Monthly calendar days
MT   Monthly trading days
DC   Daily calendar days
IR   Irregular
NC   1st-25th calendar days
NT   1st-25th traded days
FC   Fortnight (11th-25th)/(26th-10th) calendar days
FT   Fortnight (11th-25th)/(26th-10th) traded days
XC   Semimonthly calendar days with deviating average
XT   Semimonthly trading days with deviating average
QC   Quarterly calendar days
QT   Quarterly traded days
M20C Monthly [20] calendar
M20T Monthly [20] traded
==== ================================================

--------------

Index - Averaging Offset
------------------------

Conditional field: Only applicable and mandatory for Index based prices,
leave empty if this location uses market price base.

Example value: N-1

Description: This field should be populated with one of the following
codes.

==== =============================
Code Description
==== =============================
N+0  Current period
N-1  Previous period
N-2  Period before previous period
N+1  Next period
==== =============================

--------------

Market Price - Amount
---------------------

Conditional field: Only applicable and mandatory for market based
prices, leave empty if this location uses index price base.

Example value: 3.1234

Description: Value of the market price.

--------------

Market Price - Currency
-----------------------

Example value: USD

Description: This field should be populated with one of the following
codes.

==== ========================================================
Code Description
==== ========================================================
USD  United States of America, Dollars
AED  United Arab Emirates, Dirhams
AFN  Afghanistan, Afghani
ALL  Albania, Leke
AMD  Armenia, Drams
ANG  Netherlands Antilles, Guilders
AOA  Angola, Kwanza
ARS  Argentina, Pesos
AUD  Australian dollar
AWG  Aruba, Guilders
AZN  Azerbaijan, New Manats
BAM  Bosnia and Herzegovina, Convertible Marka
BBD  Barbados, Dollars
BDT  Bangladesh, Taka
BGN  Bulgaria, Leva
BHD  Bahrain, Dinars
BIF  Burundi, Francs
BMD  Bermuda, Dollars
BND  Brunei Darussalam, Dollars
BOB  Bolivia, Bolívianos
BRL  Brazil, Brazil Real
BSD  Bahamas, Dollars
BTN  Bhutan, Ngultrum
BWP  Botswana, Pulas
BZD  Belize, Dollars
CAD  Canada, Dollars
CDF  Congo/Kinshasa, Congolese Francs
CHF  Switzerland, Francs
CLP  Chile, Pesos
CNY  China, Yuan Renminbi
COP  Colombia, Pesos
CRC  Costa Rica, Colones
CUC  Cuba Convertible Peso
CUP  Cuba, Pesos
CVE  Cape Verde, Escudos
CZK  Czech Republic, Koruny
DJF  Djibouti, Francs
DKK  Denmark, Kroner
DOP  Dominican Republic, Pesos
DZD  Algeria, Algeria Dinars
EGP  Egypt, Pounds
ERN  Eritrea, Nakfa
ETB  Ethiopia, Birr
EUR  Euro Member Countries, Euro
FJD  Fiji, Dollars
FKP  Falkland Islands (Malvinas), Pounds
GBP  United Kingdom, Pounds
GEL  Georgia, Lari
GGP  Guernsey, Pounds
GHS  Ghana, Cedis
GIP  Gibraltar, Pounds
GMD  Gambia, Dalasi
GNF  Guinean franc
GTQ  Guatemala, Quetzales
GYD  Guyana, Dollars
HKD  Hong Kong, Dollars
HNL  Honduras, Lempiras
HRK  Croatia, Kuna
HTG  Haiti, Gourdes
HUF  Hungary, Forint
IDR  Indonesia, Rupiahs
ILS  Israel, New Shekels
IMP  Isle of Man, Pounds
INR  India, Rupees
IQD  Iraq, Dinars
IRR  Iran, Rials
ISK  Iceland, Kronur
JMD  Jamaica, Dollars
JOD  Jordan, Dinars
JPY  Japan, Yen
KES  Kenya, Shillings
KGS  Kyrgyzstan, Soms
KHR  Cambodia, Riels
KMF  Comoros, Francs
KRW  Korea (South), Won
KWD  Kuwait, Dinars
KYD  Cayman Islands, Dollars
KZT  Kazakhstan, Tenge
LAK  Laos, Kips
LBP  Lebanon, Pounds
LKR  Sri Lanka, Rupees
LRD  Liberia, Dollars
LSL  Lesotho, Maloti
LYD  Libya, Dinars
MAD  Morocco, Dirhams
MDL  Moldova, Lei
MGA  Madagascar, Ariary
MKD  Macedonian denar
MMK  Myanmar (Burma), Kyats
MNT  Mongolia, Tugriks
MOP  Macau, Patacas
MUR  Mauritius, Rupees
MVR  Maldives (Maldive Islands), Rufiyaa
MWK  Malawi, Kwachas
MXN  Mexico, Pesos
MYR  Malaysia, Ringgits
MZN  Mozambique, Meticais
NAD  Namibia, Dollars
NGN  Nigeria, Nairas
NIO  Nicaragua, Cordobas
NOK  Norway, Krone
NPR  Nepal, Nepal Rupees
NZD  New Zealand, Dollars
OMR  Oman, Rials
PAB  Panama, Balboa
PEN  Peru, Nuevos Soles
PGK  Papua New Guinea, Kina
PHP  Philippines, Pesos
PKR  Pakistan, Rupees
PLN  Poland, Zlotych
PYG  Paraguay Guarani
QAR  Qatar, Rials
RON  Romania, New Lei
RSD  Serbia, Dinars
RUB  Russia, Rubles
RWF  Rwanda, Rwanda Francs
SAR  Saudi Arabia, Riyals
SBD  Solomon Islands, Dollars
SCR  Seychelles, Rupees
SDG  Sudan, Pounds
SEK  Sweden, Kronor
SGD  Singapore, Dollars
SHP  Saint Helena, Pounds
SLL  Sierra Leone, Leones
SOS  Somalia, Shillings
SRD  Suriname, Dollars
SYP  Syria, Pounds
SZL  Swaziland, Emalangeni
THB  Thailand, Baht
TJS  Tajikistan, Somoni
TND  Tunisia, Dinars
TOP  Tonga, Pa"anga
TRY  Turkey, New Lira
TTD  Trinidad and Tobago, Dollars
TVD  Tuvalu, Tuvalu Dollars
TWD  Taiwan, New Dollars
TZS  Tanzania, Shillings
UAH  Ukraine, Hryvnia
UGX  Uganda, Shillings
UYU  Uruguay, Pesos
UZS  Uzbekistan, Sums
VND  Viet Nam, Dong
VUV  Vanuatu, Vatu
WST  Samoa, Tala
XAF  Communauté Financière Africaine BEAC, Francs
XCD  East Caribbean Dollars
XDR  International Monetary Fund (IMF) Special Drawing Rights
XOF  Communauté Financière Africaine BCEAO, Francs
XPF  Comptoirs Français du Pacifique Francs
YER  Yemen, Rials
ZAR  South Africa, Rand
==== ========================================================


--------------

Market Price - Unit
-------------------

Conditional field: Only applicable and mandatory for market based
prices, leave empty if this location uses index price base.

Example value: USG

Description: This field should be populated with one of the following
codes.

==== ===========
Code Description
==== ===========
USG  US Gallons
KG   Kilograms
LBS  Pounds
LTR   Liters
MT   Metric Ton
BBL  Barrels
CBM  Cubic Metre
==== ===========

--------------

Market Price - Source Type
--------------------------

Conditional field: Only applicable and mandatory for market based
prices, leave empty if this location uses index price base.

Example value: G

Description: This field should be populated with one of the following
codes.

==== ===========
Code Description
==== ===========
E    Ex refinery
G    Government
M    Market
==== ===========

--------------

Market Price - Source Name
--------------------------

Conditional field: Only applicable for market based prices, leave empty
if this location uses index price base.

Example value: Government of Kazakhstan

--------------

Differential Amount\*
---------------------

Example value: 0.123

Description: Value of the deffirential.

--------------

Differential Currency\*
-----------------------

Example value: USD

Description: This field should be populated with one of the following
codes.

==== ========================================================
Code Description
==== ========================================================
USD  United States of America, Dollars
AED  United Arab Emirates, Dirhams
AFN  Afghanistan, Afghani
ALL  Albania, Leke
AMD  Armenia, Drams
ANG  Netherlands Antilles, Guilders
AOA  Angola, Kwanza
ARS  Argentina, Pesos
AUD  Australian dollar
AWG  Aruba, Guilders
AZN  Azerbaijan, New Manats
BAM  Bosnia and Herzegovina, Convertible Marka
BBD  Barbados, Dollars
BDT  Bangladesh, Taka
BGN  Bulgaria, Leva
BHD  Bahrain, Dinars
BIF  Burundi, Francs
BMD  Bermuda, Dollars
BND  Brunei Darussalam, Dollars
BOB  Bolivia, Bolívianos
BRL  Brazil, Brazil Real
BSD  Bahamas, Dollars
BTN  Bhutan, Ngultrum
BWP  Botswana, Pulas
BZD  Belize, Dollars
CAD  Canada, Dollars
CDF  Congo/Kinshasa, Congolese Francs
CHF  Switzerland, Francs
CLP  Chile, Pesos
CNY  China, Yuan Renminbi
COP  Colombia, Pesos
CRC  Costa Rica, Colones
CUC  Cuba Convertible Peso
CUP  Cuba, Pesos
CVE  Cape Verde, Escudos
CZK  Czech Republic, Koruny
DJF  Djibouti, Francs
DKK  Denmark, Kroner
DOP  Dominican Republic, Pesos
DZD  Algeria, Algeria Dinars
EGP  Egypt, Pounds
ERN  Eritrea, Nakfa
ETB  Ethiopia, Birr
EUR  Euro Member Countries, Euro
FJD  Fiji, Dollars
FKP  Falkland Islands (Malvinas), Pounds
GBP  United Kingdom, Pounds
GEL  Georgia, Lari
GGP  Guernsey, Pounds
GHS  Ghana, Cedis
GIP  Gibraltar, Pounds
GMD  Gambia, Dalasi
GNF  Guinean franc
GTQ  Guatemala, Quetzales
GYD  Guyana, Dollars
HKD  Hong Kong, Dollars
HNL  Honduras, Lempiras
HRK  Croatia, Kuna
HTG  Haiti, Gourdes
HUF  Hungary, Forint
IDR  Indonesia, Rupiahs
ILS  Israel, New Shekels
IMP  Isle of Man, Pounds
INR  India, Rupees
IQD  Iraq, Dinars
IRR  Iran, Rials
ISK  Iceland, Kronur
JMD  Jamaica, Dollars
JOD  Jordan, Dinars
JPY  Japan, Yen
KES  Kenya, Shillings
KGS  Kyrgyzstan, Soms
KHR  Cambodia, Riels
KMF  Comoros, Francs
KRW  Korea (South), Won
KWD  Kuwait, Dinars
KYD  Cayman Islands, Dollars
KZT  Kazakhstan, Tenge
LAK  Laos, Kips
LBP  Lebanon, Pounds
LKR  Sri Lanka, Rupees
LRD  Liberia, Dollars
LSL  Lesotho, Maloti
LYD  Libya, Dinars
MAD  Morocco, Dirhams
MDL  Moldova, Lei
MGA  Madagascar, Ariary
MKD  Macedonian denar
MMK  Myanmar (Burma), Kyats
MNT  Mongolia, Tugriks
MOP  Macau, Patacas
MUR  Mauritius, Rupees
MVR  Maldives (Maldive Islands), Rufiyaa
MWK  Malawi, Kwachas
MXN  Mexico, Pesos
MYR  Malaysia, Ringgits
MZN  Mozambique, Meticais
NAD  Namibia, Dollars
NGN  Nigeria, Nairas
NIO  Nicaragua, Cordobas
NOK  Norway, Krone
NPR  Nepal, Nepal Rupees
NZD  New Zealand, Dollars
OMR  Oman, Rials
PAB  Panama, Balboa
PEN  Peru, Nuevos Soles
PGK  Papua New Guinea, Kina
PHP  Philippines, Pesos
PKR  Pakistan, Rupees
PLN  Poland, Zlotych
PYG  Paraguay Guarani
QAR  Qatar, Rials
RON  Romania, New Lei
RSD  Serbia, Dinars
RUB  Russia, Rubles
RWF  Rwanda, Rwanda Francs
SAR  Saudi Arabia, Riyals
SBD  Solomon Islands, Dollars
SCR  Seychelles, Rupees
SDG  Sudan, Pounds
SEK  Sweden, Kronor
SGD  Singapore, Dollars
SHP  Saint Helena, Pounds
SLL  Sierra Leone, Leones
SOS  Somalia, Shillings
SRD  Suriname, Dollars
SYP  Syria, Pounds
SZL  Swaziland, Emalangeni
THB  Thailand, Baht
TJS  Tajikistan, Somoni
TND  Tunisia, Dinars
TOP  Tonga, Pa"anga
TRY  Turkey, New Lira
TTD  Trinidad and Tobago, Dollars
TVD  Tuvalu, Tuvalu Dollars
TWD  Taiwan, New Dollars
TZS  Tanzania, Shillings
UAH  Ukraine, Hryvnia
UGX  Uganda, Shillings
UYU  Uruguay, Pesos
UZS  Uzbekistan, Sums
VND  Viet Nam, Dong
VUV  Vanuatu, Vatu
WST  Samoa, Tala
XAF  Communauté Financière Africaine BEAC, Francs
XCD  East Caribbean Dollars
XDR  International Monetary Fund (IMF) Special Drawing Rights
XOF  Communauté Financière Africaine BCEAO, Francs
XPF  Comptoirs Français du Pacifique Francs
YER  Yemen, Rials
ZAR  South Africa, Rand
==== ========================================================


--------------

Differential Unit\*
-------------------

Example value: USG

Description: This field should be populated with one of the following
codes.

==== ===========
Code Description
==== ===========
USG  US Gallons
KG   Kilograms
LBS  Pounds
LTR   Liters
MT   Metric Ton
BBL  Barrels
CBM  Cubic Metre
==== ===========

--------------

Non-mandatory Fees
------------------

Example value: Low volume fee 120 EUR for uplifts under 1500 USG

Description: List any non-mandatory fees.

--------------

Into-plane Service Provider
---------------------------

Example value: Skytanking LLC

--------------

Available Volume Percentage
---------------------------

Example value: 100

Description: Speify how many percent of the total requested volume are
you bidding for.

--------------

Gross or Net Billing
--------------------

Example value: gross

Description: This field should be populated with one of the following
codes.

===== =============
Code  Description
===== =============
gross Gross Billing
net   Net Billing
===== =============

--------------

Open Fuel Release
-----------------

Example value: Y

Description: This field should be populated with one of the following
codes.

==== ===========
Code Description
==== ===========
Y    Yes
N    No
==== ===========

--------------

Pre-flight Notification Hours
-----------------------------

Example value: 16

Description: If pre-flight notification is required, specify how many
hours advance notice should be given

--------------

Pre-flight Notification Notes
-----------------------------

Description: Provide pre-flight notification notes if available

--------------

Ramp Limitations Notes
----------------------

Description: Provide ramp limitation notes if available

--------------

Fuel Availability
-----------------

Description: Provide fuel availability notes if restrictions apply

--------------

Delivery Method to Airport 1
----------------------------

Example value: pipeline

Description: If the airline requests information on delivery methods to
the airport list them in the order of priority, where the primary method
is listed in the "Delivery Method to Airport 1" field.

This field should be populated with one of the following codes.

======== ===========
Code     Description
======== ===========
pipeline Pipeline
truck    Truck
rail     Rail
barge    Barge
======== ===========

--------------

Delivery Method to Airport 1 Percentage
---------------------------------------

Example value: 80

Description: What percentage of the total fuel delivery methods is
Delivery Method to Airport 1 covering?

--------------

Additional delivery methods can be specified in the following columns, using the same logic as above

* Delivery Method to Airport 2
* Delivery Method to Airport 2 Percentage
* Delivery Method to Airport 3
* Delivery Method to Airport 3 Percentage
* Delivery Method to Airport 4
* Delivery Method to Airport 4 Percentage

--------------

Delivery Method to Aircraft
---------------------------

Example value: both

Description: This field should be populated with one of the following
codes.

======= ====================
Code    Description
======= ====================
hydrant Hydrant
truck   Truck
both    Both hydrant & truck
======= ====================

--------------

Notes
-----

Description: Provide any notes related to this bid
