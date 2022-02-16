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
    Please use the exported Excel file named "Tender Information" for importing bids.

    The "Tender Bids" file should not be used for importing bids, as this file is used to export bids which have already been input, this document serves are a report after the tender has been completed.

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

Example value: CO

Description: This field should be populated with one of the following
codes.

=========== ===========
Code        Description
=========== ===========
CA          Cash
CC          Credit Card
CN          Carnet
CO          Contract
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
FCB  Fortnight (1st-15th)/(16th-31st) calendar days
FTB  Fortnight (1st-15th)/(16th-31st) traded days
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
====== ===========

--------------

Index - Code
------------

Example value: AAFIY00

Description: Note that the index bate is specified as a separate field.
This field should be populated with one of the following codes.

+----------+----------------+----------------------------------------+
| Provider | Provider code  | Description                            |
+----------+----------------+----------------------------------------+
| Platts   | AAFIY00        | Jet Kero C+F Australia Cargo           |
+----------+----------------+----------------------------------------+
| Platts   | AAIDL00        | Jet FOB Med Cargo                      |
+----------+----------------+----------------------------------------+
| Platts   | AAIDN00        | Jet FOB Med Premium Cargo              |
+----------+----------------+----------------------------------------+
| Platts   | AAJNL00        | Jet Kero New Jersey Buckeye Pipeline   |
+----------+----------------+----------------------------------------+
| Platts   | AAKNZ00        | Jet Kero LR2 FOB Arab Gulf Cargo       |
+----------+----------------+----------------------------------------+
| Platts   | AAQWL00        | Jet Kero MOP West India $/bbl          |
+----------+----------------+----------------------------------------+
| Platts   | AAQWM00        | Jet Kero MOP West India $/mt           |
+----------+----------------+----------------------------------------+
| Platts   | AAVTH00        | Jet Kero ULS New York Harbor Cargo     |
+----------+----------------+----------------------------------------+
| Platts   | AAVTI00        | Jet Kero ULS New York Harbor Barge     |
+----------+----------------+----------------------------------------+
| Platts   | AAVTJ00        | Jet Kero ULS Boston Cargo              |
+----------+----------------+----------------------------------------+
| Platts   | AAVTK00        | Jet Kero ULS USGC Waterborne           |
+----------+----------------+----------------------------------------+
| Platts   | AAVTL00        | Jet Kero ULS USGC Prompt Pipeline      |
+----------+----------------+----------------------------------------+
| Platts   | AAXPV00        | Jet Kero 54 USAC Linden Pipeline       |
|          |                | prompt cycle assessment                |
+----------+----------------+----------------------------------------+
| Platts   | AAZBN00        | Jet CIF Med Cargo                      |
+----------+----------------+----------------------------------------+
| Platts   | PJAAA00        | Jet Kero FOB Arab Gulf Cargo           |
+----------+----------------+----------------------------------------+
| Platts   | PJAAD00        | Jet Kero Caribbean Cargo $/mt          |
+----------+----------------+----------------------------------------+
| Platts   | PJAAD10        | Jet Kero Caribbean Cargo cts/gal       |
+----------+----------------+----------------------------------------+
| Platts   | PJAAF00        | Jet Kero FOB Chicago Pipe              |
+----------+----------------+----------------------------------------+
| Platts   | PJAAI00        | Jet Kero Group 3 Pipeline              |
+----------+----------------+----------------------------------------+
| Platts   | PJAAN00        | Jet Kero C+F Japan Cargo               |
+----------+----------------+----------------------------------------+
| Platts   | PJAAP00        | Jet Kero Los Angeles CA Pipeline       |
+----------+----------------+----------------------------------------+
| Platts   | PJAAU00        | Jet CIF NWE Cargo                      |
+----------+----------------+----------------------------------------+
| Platts   | PJAAV00        | Jet FOB NWE Cargo                      |
+----------+----------------+----------------------------------------+
| Platts   | PJAAW00        | Jet Kero New York Harbor Barge         |
+----------+----------------+----------------------------------------+
| Platts   | PJAAX00        | Jet Kero New York Harbor Cargo         |
+----------+----------------+----------------------------------------+
| Platts   | PJABA00        | Jet FOB Rdam Barge                     |
+----------+----------------+----------------------------------------+
| Platts   | PJABC00        | Jet Kero San Francisco CA Pipeline     |
+----------+----------------+----------------------------------------+
| Platts   | PJABF00        | Jet Kero FOB Spore Cargo               |
+----------+----------------+----------------------------------------+
| Platts   | PJABI00        | Jet Kero USWC Waterborne               |
+----------+----------------+----------------------------------------+
| Platts   | PJABJ00        | Jet Kero LS New York Harbor Barge      |
+----------+----------------+----------------------------------------+
| Platts   | PJABK00        | Jet Kero LS New York Harbor Cargo      |
+----------+----------------+----------------------------------------+
| Platts   | PJABL00        | Jet Kero LS Boston Cargo               |
+----------+----------------+----------------------------------------+
| Platts   | PJABM00        | Jet Kero 54 USGC Waterborne            |
+----------+----------------+----------------------------------------+
| Platts   | PJABN00        | Jet Kero 55 USGC Waterborne            |
+----------+----------------+----------------------------------------+
| Platts   | PJABO00        | Jet Kero 54 USGC Prompt Pipeline       |
+----------+----------------+----------------------------------------+
| Platts   | PJABP00        | Jet Kero 55 USGC Prompt Pipeline       |
+----------+----------------+----------------------------------------+
| Platts   | PJABQ00        | Jet Kero C+F South China Cargo         |
+----------+----------------+----------------------------------------+
| Platts   | PJACB00        | Jet Kero ULS No1 Group 3 Pipeline      |
+----------+----------------+----------------------------------------+
| Platts   | PJACD00        | Jet Kero ULS No1 FOB Chicago Pipe      |
+----------+----------------+----------------------------------------+
| Platts   | PJADG00        | Jet Kero FOB Korea Cargo               |
+----------+----------------+----------------------------------------+
| Platts   | PTAEO09        | Jet Carib Shell W                      |
+----------+----------------+----------------------------------------+
| Argus    | PA0003951      | Jet fuel Buckeye pipe fob              |
+----------+----------------+----------------------------------------+
| Argus    | PA0002901      | Jet fuel Chicago pipe fob cycle        |
+----------+----------------+----------------------------------------+
| Argus    | PA0002760      | Jet fuel Colonial 54 pipe fob cycle    |
+----------+----------------+----------------------------------------+
| Argus    | PA0004245      | Jet fuel Colonial 54 pipe fob wtd avg  |
|          |                | cycle                                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0003948      | Jet fuel Group 3 Magellan Q pipe fob   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001024      | Jet fuel LA pipe fob month             |
+----------+----------------+----------------------------------------+
| Argus    | PA0018544      | Jet fuel LA pipe fob wtd avg month     |
+----------+----------------+----------------------------------------+
| Argus    | PA0003953      | Jet fuel Laurel pipe fob               |
+----------+----------------+----------------------------------------+
| Argus    | PA0001011      | Jet fuel NYH barge fob 10 days fwd     |
+----------+----------------+----------------------------------------+
| Argus    | PA0001012      | Jet fuel NYH barge fob 15 days fwd     |
+----------+----------------+----------------------------------------+
| Argus    | PA0002147      | Jet fuel NYH barge fob 20 days fwd     |
+----------+----------------+----------------------------------------+
| Argus    | PA0001010      | Jet fuel NYH barge fob prompt          |
+----------+----------------+----------------------------------------+
| Argus    | PA0005171      | Jet fuel NYH cargo del                 |
+----------+----------------+----------------------------------------+
| Argus    | PA0014711      | Jet fuel NYH offline Colonial 54 pipe  |
|          |                | del cycle                              |
+----------+----------------+----------------------------------------+
| Argus    | PA0001027      | Jet fuel SF pipe fob month             |
+----------+----------------+----------------------------------------+
| Argus    | PA0003945      | Jet fuel USGC waterborne fob           |
+----------+----------------+----------------------------------------+
| Argus    | PA0015003      | Jet Orsk - Kazakhstan (Aktobe) del     |
|          |                | price index                            |
+----------+----------------+----------------------------------------+
| Argus    | PA0015002      | Jet Orsk - Kazakhstan (Alma-Ata) del   |
|          |                | price index                            |
+----------+----------------+----------------------------------------+
| Argus    | PA0015001      | Jet Orsk - Kazakhstan (Astana) del     |
|          |                | price index                            |
+----------+----------------+----------------------------------------+
| Argus    | PA0015004      | Jet Orsk - Kazakhstan (Atyrau) del     |
|          |                | price index                            |
+----------+----------------+----------------------------------------+
| Argus    | PA0015005      | Jet Orsk - Kazakhstan (Karaganda) del  |
|          |                | price index                            |
+----------+----------------+----------------------------------------+
| Argus    | PA0015006      | Jet Orsk - Kazakhstan (Uralsk) del     |
|          |                | price index                            |
+----------+----------------+----------------------------------------+
| Argus    | PA0015007      | Jet Orsk - Kazakhstan                  |
|          |                | (Ust-Kamenogorsk) del price index      |
+----------+----------------+----------------------------------------+
| Argus    | PA0018005      | Jet/kerosine c+f Durban                |
+----------+----------------+----------------------------------------+
| Argus    | PA0005630      | Jet/Kerosine Chimkent                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0018507      | Jet/kerosine delivered west Africa $/t |
+----------+----------------+----------------------------------------+
| Argus    | PA0015000      | Jet/Kerosine fca Orsk                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0009049      | Jet/Kerosine fit Moscow spot ex. VAT   |
+----------+----------------+----------------------------------------+
| Argus    | PA0009048      | Jet/Kerosine fit Moscow spot incl. VAT |
+----------+----------------+----------------------------------------+
| Argus    | PA0001016      | Jet/kerosine Japan c+f                 |
+----------+----------------+----------------------------------------+
| Argus    | PA0001017      | Jet/kerosine Mideast Gulf fob          |
+----------+----------------+----------------------------------------+
| Argus    | PA0007734      | Jet/Kerosine Moscow formula ex. VAT    |
+----------+----------------+----------------------------------------+
| Argus    | PA0007733      | Jet/Kerosine Moscow formula incl. VAT  |
+----------+----------------+----------------------------------------+
| Argus    | PA0001025      | Jet/kerosine NWE barge                 |
+----------+----------------+----------------------------------------+
| Argus    | PA0001018      | Jet/kerosine NWE cif                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001026      | Jet/kerosine NWE fob                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0005631      | Jet/Kerosine Pavlodar                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0005336      | Jet/kerosine S Korea                   |
+----------+----------------+----------------------------------------+
| Argus    | PA0001019      | Jet/kerosine Singapore                 |
+----------+----------------+----------------------------------------+
| Argus    | PA0010050      | Jet/Kerosine SPIMEX Index              |
+----------+----------------+----------------------------------------+
| Argus    | PA0009545      | Jet/kerosine W Med cif                 |
+----------+----------------+----------------------------------------+
| Argus    | PA0009549      | Jet/kerosine W Med cif diff to Jet fob |
|          |                | W Med                                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0001021      | Jet/kerosine W Med fob                 |
+----------+----------------+----------------------------------------+
| Argus    | PA0003952      | Kerosine Buckeye pipe fob              |
+----------+----------------+----------------------------------------+
| Argus    | PA0016541      | Kerosine Buckeye pipe fob (AST)        |
+----------+----------------+----------------------------------------+
| Argus    | PA0016533      | Kerosine Colonial 55 pipe fob (AST)    |
|          |                | cycle                                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0002762      | Kerosine Colonial 55 pipe fob cycle    |
+----------+----------------+----------------------------------------+
| Argus    | PA0001014      | Kerosine NYH barge fob 10 days fwd     |
+----------+----------------+----------------------------------------+
| Argus    | PA0002148      | Kerosine NYH barge fob 15 days fwd     |
+----------+----------------+----------------------------------------+
| Argus    | PA0002149      | Kerosine NYH barge fob 20 days fwd     |
+----------+----------------+----------------------------------------+
| Argus    | PA0001015      | Kerosine NYH barge fob prompt          |
+----------+----------------+----------------------------------------+
| Argus    | PA0016523      | Kerosine NYH barge fob prompt (AST)    |
+----------+----------------+----------------------------------------+
| Argus    | PA0001022      | Kerosine NYH cargo del                 |
+----------+----------------+----------------------------------------+
| Argus    | PA0016567      | Kerosine ULSK Chicago pipe fob (AST)   |
|          |                | cycle                                  |
+----------+----------------+----------------------------------------+
| Argus    | PA0004980      | Kerosine ULSK Chicago pipe fob cycle   |
+----------+----------------+----------------------------------------+
| Argus    | PA0004979      | Kerosine ULSK Group 3 Magellan Y pipe  |
|          |                | fob prompt                             |
+----------+----------------+----------------------------------------+
| Argus    | PA0016566      | Kerosine ULSK Group 3 Magellan Y pipe  |
|          |                | fob prompt (AST)                       |
+----------+----------------+----------------------------------------+
| Argus    | PA0004977      | Kerosine ULSK NYH barge fob            |
+----------+----------------+----------------------------------------+
| Argus    | PA0016565      | Kerosine ULSK NYH barge fob (AST)      |
+----------+----------------+----------------------------------------+
| Argus    | PA0004978      | Kerosine ULSK NYH cargo del            |
+----------+----------------+----------------------------------------+
| Argus    | PA0001020      | Kerosine USGC waterborne fob           |
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

Index - Bate
------------------------
Conditional field: Only applicable and mandatory for Index based prices,
leave empty if this location uses market price base.

Example value: h

Description: This field should be populated with one of the following
codes.

==== ============
Code Description
==== ============
l    Low
c    Close / Mean
h    High
==== ============


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
WT   Weekly trading days
MT   Monthly trading days
DC   Daily calendar days
FT   Fortnight (11th-25th)/(26th-10th) traded days
FCB  Fortnight (1st-15th)/(16th-31st) calendar days
FTB  Fortnight (1st-15th)/(16th-31st) traded days
ST   Semimonthly trading days
XT   Semimonthly trading days with deviating average
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

Price Effective Date
------------------------
Conditional field: Only applicable and mandatory for Index based prices,
leave empty if this location uses market price base.

Example value: 1

Description: This field should be populated with one of the following
codes.

==== ===========
Code Description
==== ===========
1    Monday
2    Tuesday
3    Wednesday
4    Thursday
5    Friday
6    Saturday
7    Sunday
==== ===========


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
