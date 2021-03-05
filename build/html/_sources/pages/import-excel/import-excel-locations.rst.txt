This tutorial explains how to prepare the Excel file for Import.

Before you begin:

#. Go to the tender invitation page
#. Click on Export and select Export Tender Information
   JetFuelTenders will generate a customised template with tender
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
   Input any related fees and taxes for each specific locaiton. One fee
   or tax per row
#. Go to the Per Usage Base Fees & Taxes
   Input any related fees and taxes for each specific locaiton. One fee
   or tax per row
#. When ready, save the Excel document and upload it to
   JetFuelTenders.com by clickin on the Import button on the tender page
   or send this document to the airline via emails.

The first 10 columns display the tender requirements for specified
locations (do not edit columns A - J)

This document is based on IATA XML Tender / Bid Fuel Data Standard.

NOTE: The bid importer is not case sensitive, so values can be input in
lowercase or uppercase.

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

=== ========================================================
USD United States of America, Dollars
AED United Arab Emirates, Dirhams
AFN Afghanistan, Afghani
ALL Albania, Leke
AMD Armenia, Drams
ANG Netherlands Antilles, Guilders
AOA Angola, Kwanza
ARS Argentina, Pesos
AUD Australian dollar
AWG Aruba, Guilders
AZN Azerbaijan, New Manats
BAM Bosnia and Herzegovina, Convertible Marka
BBD Barbados, Dollars
BDT Bangladesh, Taka
BGN Bulgaria, Leva
BHD Bahrain, Dinars
BIF Burundi, Francs
BMD Bermuda, Dollars
BND Brunei Darussalam, Dollars
BOB Bolivia, Bolívianos
BRL Brazil, Brazil Real
BSD Bahamas, Dollars
BTN Bhutan, Ngultrum
BWP Botswana, Pulas
BZD Belize, Dollars
CAD Canada, Dollars
CDF Congo/Kinshasa, Congolese Francs
CHF Switzerland, Francs
CLP Chile, Pesos
CNY China, Yuan Renminbi
COP Colombia, Pesos
CRC Costa Rica, Colones
CUC Cuba Convertible Peso
CUP Cuba, Pesos
CVE Cape Verde, Escudos
CZK Czech Republic, Koruny
DJF Djibouti, Francs
DKK Denmark, Kroner
DOP Dominican Republic, Pesos
DZD Algeria, Algeria Dinars
EGP Egypt, Pounds
ERN Eritrea, Nakfa
ETB Ethiopia, Birr
EUR Euro Member Countries, Euro
FJD Fiji, Dollars
FKP Falkland Islands (Malvinas), Pounds
GBP United Kingdom, Pounds
GEL Georgia, Lari
GGP Guernsey, Pounds
GHS Ghana, Cedis
GIP Gibraltar, Pounds
GMD Gambia, Dalasi
GNF Guinean franc
GTQ Guatemala, Quetzales
GYD Guyana, Dollars
HKD Hong Kong, Dollars
HNL Honduras, Lempiras
HRK Croatia, Kuna
HTG Haiti, Gourdes
HUF Hungary, Forint
IDR Indonesia, Rupiahs
ILS Israel, New Shekels
IMP Isle of Man, Pounds
INR India, Rupees
IQD Iraq, Dinars
IRR Iran, Rials
ISK Iceland, Kronur
JMD Jamaica, Dollars
JOD Jordan, Dinars
JPY Japan, Yen
KES Kenya, Shillings
KGS Kyrgyzstan, Soms
KHR Cambodia, Riels
KMF Comoros, Francs
KRW Korea (South), Won
KWD Kuwait, Dinars
KYD Cayman Islands, Dollars
KZT Kazakhstan, Tenge
LAK Laos, Kips
LBP Lebanon, Pounds
LKR Sri Lanka, Rupees
LRD Liberia, Dollars
LSL Lesotho, Maloti
LYD Libya, Dinars
MAD Morocco, Dirhams
MDL Moldova, Lei
MGA Madagascar, Ariary
MKD Macedonian denar
MMK Myanmar (Burma), Kyats
MNT Mongolia, Tugriks
MOP Macau, Patacas
MUR Mauritius, Rupees
MVR Maldives (Maldive Islands), Rufiyaa
MWK Malawi, Kwachas
MXN Mexico, Pesos
MYR Malaysia, Ringgits
MZN Mozambique, Meticais
NAD Namibia, Dollars
NGN Nigeria, Nairas
NIO Nicaragua, Cordobas
NOK Norway, Krone
NPR Nepal, Nepal Rupees
NZD New Zealand, Dollars
OMR Oman, Rials
PAB Panama, Balboa
PEN Peru, Nuevos Soles
PGK Papua New Guinea, Kina
PHP Philippines, Pesos
PKR Pakistan, Rupees
PLN Poland, Zlotych
PYG Paraguay Guarani
QAR Qatar, Rials
RON Romania, New Lei
RSD Serbia, Dinars
RUB Russia, Rubles
RWF Rwanda, Rwanda Francs
SAR Saudi Arabia, Riyals
SBD Solomon Islands, Dollars
SCR Seychelles, Rupees
SDG Sudan, Pounds
SEK Sweden, Kronor
SGD Singapore, Dollars
SHP Saint Helena, Pounds
SLL Sierra Leone, Leones
SOS Somalia, Shillings
SRD Suriname, Dollars
SYP Syria, Pounds
SZL Swaziland, Emalangeni
THB Thailand, Baht
TJS Tajikistan, Somoni
TND Tunisia, Dinars
TOP Tonga, Pa"anga
TRY Turkey, New Lira
TTD Trinidad and Tobago, Dollars
TVD Tuvalu, Tuvalu Dollars
TWD Taiwan, New Dollars
TZS Tanzania, Shillings
UAH Ukraine, Hryvnia
UGX Uganda, Shillings
UYU Uruguay, Pesos
UZS Uzbekistan, Sums
VND Viet Nam, Dong
VUV Vanuatu, Vatu
WST Samoa, Tala
XAF Communauté Financière Africaine BEAC, Francs
XCD East Caribbean Dollars
XDR International Monetary Fund (IMF) Special Drawing Rights
XOF Communauté Financière Africaine BCEAO, Francs
XPF Comptoirs Français du Pacifique Francs
YER Yemen, Rials
ZAR South Africa, Rand
=== ========================================================

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
the code. There are 2 options available h for high and l for low. This
field should be populated with one of the following codes.

======== ==============
Provider Code
======== ==============
Platts   AAFIY00h
Platts   AAIDL00h
Platts   AAIDN00h
Platts   AAJNL00h
Platts   AAKNZ00h
Platts   AAQWL00h
Platts   AAQWM00h
Platts   AAVTH00h
Platts   AAVTI00h
Platts   AAVTJ00h
Platts   AAVTK00h
Platts   AAVTL00h
Platts   AAXPV00h
Platts   AAZBN00h
Platts   PJAAA00h
Platts   PJAAD00h
Platts   PJAAD10h
Platts   PJAAF00h
Platts   PJAAI00h
Platts   PJAAN00h
Platts   PJAAP00h
Platts   PJAAU00h
Platts   PJAAV00h
Platts   PJAAW00h
Platts   PJAAX00h
Platts   PJABA00h
Platts   PJABC00h
Platts   PJABF00h
Platts   PJABI00h
Platts   PJABJ00h
Platts   PJABK00h
Platts   PJABL00h
Platts   PJABM00h
Platts   PJABN00h
Platts   PJABO00h
Platts   PJABP00h
Platts   PJABQ00h
Platts   PJACB00h
Platts   PJACD00h
Platts   PJADG00h
Platts   PTAEO09h
Platts   AAFIY00l
Platts   AAIDL00l
Platts   AAIDN00l
Platts   AAJNL00l
Platts   AAKNZ00l
Platts   AAQWL00l
Platts   AAQWM00l
Platts   AAVTH00l
Platts   AAVTI00l
Platts   AAVTJ00l
Platts   AAVTK00l
Platts   AAVTL00l
Platts   AAXPV00l
Platts   AAZBN00l
Platts   PJAAA00l
Platts   PJAAD00l
Platts   PJAAD10l
Platts   PJAAF00l
Platts   PJAAI00l
Platts   PJAAN00l
Platts   PJAAP00l
Platts   PJAAU00l
Platts   PJAAV00l
Platts   PJAAW00l
Platts   PJAAX00l
Platts   PJABA00l
Platts   PJABC00l
Platts   PJABF00l
Platts   PJABI00l
Platts   PJABJ00l
Platts   PJABK00l
Platts   PJABL00l
Platts   PJABM00l
Platts   PJABN00l
Platts   PJABO00l
Platts   PJABP00l
Platts   PJABQ00l
Platts   PJACB00l
Platts   PJACD00l
Platts   PJADG00l
Platts   PTAEO09l
Argus    PA0003951-2
Argus    PA0002901-2
Argus    PA0002760-2
Argus    PA0004245-2
Argus    PA0003948-2
Argus    PA0001024-2
Argus    PA0018544-2
Argus    PA0003953-2
Argus    PA0001011-2
Argus    PA0001012-2
Argus    PA0002147-2
Argus    PA0001010-2
Argus    PA0005171-2
Argus    PA0014711-2
Argus    PA0001027-2
Argus    PA0003945-2
Argus    PA0015003-2
Argus    PA0015002-2
Argus    PA0015001-2
Argus    PA0015004-2
Argus    PA0015005-2
Argus    PA0015006-2
Argus    PA0015007-2
Argus    PA0018005-2
Argus    PA0005630-2
Argus    PA0018507-2
Argus    PA0015000-2
Argus    PA0009049-2
Argus    PA0009048-2
Argus    PA0001016-2
Argus    PA0001017-2
Argus    PA0007734-2
Argus    PA0007733-2
Argus    PA0001025-2
Argus    PA0001018-2
Argus    PA0001026-2
Argus    PA0005631-2
Argus    PA0005336-2
Argus    PA0001019-2
Argus    PA0010050-2
Argus    PA0009545-2
Argus    PA0009549-2
Argus    PA0001021-2
Argus    PA0003952-2
Argus    PA0016541-2
Argus    PA0016533-2
Argus    PA0002762-2
Argus    PA0001014-2
Argus    PA0002148-2
Argus    PA0002149-2
Argus    PA0001015-2
Argus    PA0016523-2
Argus    PA0001022-2
Argus    PA0016567-2
Argus    PA0004980-2
Argus    PA0004979-2
Argus    PA0016566-2
Argus    PA0004977-2
Argus    PA0016565-2
Argus    PA0004978-2
Argus    PA0001020-2
Argus    PA0003951-1
Argus    PA0002901-1
Argus    PA0002760-1
Argus    PA0004245-1
Argus    PA0003948-1
Argus    PA0001024-1
Argus    PA0018544-1
Argus    PA0003953-1
Argus    PA0001011-1
Argus    PA0001012-1
Argus    PA0002147-1
Argus    PA0001010-1
Argus    PA0005171-1
Argus    PA0014711-1
Argus    PA0001027-1
Argus    PA0003945-1
Argus    PA0015003-1
Argus    PA0015002-1
Argus    PA0015001-1
Argus    PA0015004-1
Argus    PA0015005-1
Argus    PA0015006-1
Argus    PA0015007-1
Argus    PA0018005-1
Argus    PA0005630-1
Argus    PA0018507-1
Argus    PA0015000-1
Argus    PA0009049-1
Argus    PA0009048-1
Argus    PA0001016-1
Argus    PA0001017-1
Argus    PA0007734-1
Argus    PA0007733-1
Argus    PA0001025-1
Argus    PA0001018-1
Argus    PA0001026-1
Argus    PA0005631-1
Argus    PA0005336-1
Argus    PA0001019-1
Argus    PA0010050-1
Argus    PA0009545-1
Argus    PA0009549-1
Argus    PA0001021-1
Argus    PA0003952-1
Argus    PA0016541-1
Argus    PA0016533-1
Argus    PA0002762-1
Argus    PA0001014-1
Argus    PA0002148-1
Argus    PA0002149-1
Argus    PA0001015-1
Argus    PA0016523-1
Argus    PA0001022-1
Argus    PA0016567-1
Argus    PA0004980-1
Argus    PA0004979-1
Argus    PA0016566-1
Argus    PA0004977-1
Argus    PA0016565-1
Argus    PA0004978-1
Argus    PA0001020-1
Opis     JETKEROAGLR1
Opis     JETKEROAGLR2
Opis     JETKEROKOR
Opis     JETTAIW
Opis     JETKEROSING
Opis     JETNWECGCIF
Opis     JETNWECGFOB
Opis     JETRTDBG
Opis     JETMEDCG
Opis     JET450RTDBG
Opis     JET450DFSRTDBG
Opis     KEROBUCPL
Opis     JETBUCPL
Opis     JETCHIPL
Opis     JETGR3PL
Opis     KEROUSGPL
Opis     JETUSGPL
Opis     ULSKUSGPL
Opis     KEROUSGBG
Opis     JETUSGBG
Opis     JETLAUPL
Opis     JETLINPL
Opis     JETLAXPL
Opis     JETNYBG
Opis     KERONYBG
Opis     ULSKNYBG
Opis     JETNYCG
Opis     JETPNWBG
Opis     JETSFPL
======== ==============

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

=== ========================================================
USD United States of America, Dollars
AED United Arab Emirates, Dirhams
AFN Afghanistan, Afghani
ALL Albania, Leke
AMD Armenia, Drams
ANG Netherlands Antilles, Guilders
AOA Angola, Kwanza
ARS Argentina, Pesos
AUD Australian dollar
AWG Aruba, Guilders
AZN Azerbaijan, New Manats
BAM Bosnia and Herzegovina, Convertible Marka
BBD Barbados, Dollars
BDT Bangladesh, Taka
BGN Bulgaria, Leva
BHD Bahrain, Dinars
BIF Burundi, Francs
BMD Bermuda, Dollars
BND Brunei Darussalam, Dollars
BOB Bolivia, Bolívianos
BRL Brazil, Brazil Real
BSD Bahamas, Dollars
BTN Bhutan, Ngultrum
BWP Botswana, Pulas
BZD Belize, Dollars
CAD Canada, Dollars
CDF Congo/Kinshasa, Congolese Francs
CHF Switzerland, Francs
CLP Chile, Pesos
CNY China, Yuan Renminbi
COP Colombia, Pesos
CRC Costa Rica, Colones
CUC Cuba Convertible Peso
CUP Cuba, Pesos
CVE Cape Verde, Escudos
CZK Czech Republic, Koruny
DJF Djibouti, Francs
DKK Denmark, Kroner
DOP Dominican Republic, Pesos
DZD Algeria, Algeria Dinars
EGP Egypt, Pounds
ERN Eritrea, Nakfa
ETB Ethiopia, Birr
EUR Euro Member Countries, Euro
FJD Fiji, Dollars
FKP Falkland Islands (Malvinas), Pounds
GBP United Kingdom, Pounds
GEL Georgia, Lari
GGP Guernsey, Pounds
GHS Ghana, Cedis
GIP Gibraltar, Pounds
GMD Gambia, Dalasi
GNF Guinean franc
GTQ Guatemala, Quetzales
GYD Guyana, Dollars
HKD Hong Kong, Dollars
HNL Honduras, Lempiras
HRK Croatia, Kuna
HTG Haiti, Gourdes
HUF Hungary, Forint
IDR Indonesia, Rupiahs
ILS Israel, New Shekels
IMP Isle of Man, Pounds
INR India, Rupees
IQD Iraq, Dinars
IRR Iran, Rials
ISK Iceland, Kronur
JMD Jamaica, Dollars
JOD Jordan, Dinars
JPY Japan, Yen
KES Kenya, Shillings
KGS Kyrgyzstan, Soms
KHR Cambodia, Riels
KMF Comoros, Francs
KRW Korea (South), Won
KWD Kuwait, Dinars
KYD Cayman Islands, Dollars
KZT Kazakhstan, Tenge
LAK Laos, Kips
LBP Lebanon, Pounds
LKR Sri Lanka, Rupees
LRD Liberia, Dollars
LSL Lesotho, Maloti
LYD Libya, Dinars
MAD Morocco, Dirhams
MDL Moldova, Lei
MGA Madagascar, Ariary
MKD Macedonian denar
MMK Myanmar (Burma), Kyats
MNT Mongolia, Tugriks
MOP Macau, Patacas
MUR Mauritius, Rupees
MVR Maldives (Maldive Islands), Rufiyaa
MWK Malawi, Kwachas
MXN Mexico, Pesos
MYR Malaysia, Ringgits
MZN Mozambique, Meticais
NAD Namibia, Dollars
NGN Nigeria, Nairas
NIO Nicaragua, Cordobas
NOK Norway, Krone
NPR Nepal, Nepal Rupees
NZD New Zealand, Dollars
OMR Oman, Rials
PAB Panama, Balboa
PEN Peru, Nuevos Soles
PGK Papua New Guinea, Kina
PHP Philippines, Pesos
PKR Pakistan, Rupees
PLN Poland, Zlotych
PYG Paraguay Guarani
QAR Qatar, Rials
RON Romania, New Lei
RSD Serbia, Dinars
RUB Russia, Rubles
RWF Rwanda, Rwanda Francs
SAR Saudi Arabia, Riyals
SBD Solomon Islands, Dollars
SCR Seychelles, Rupees
SDG Sudan, Pounds
SEK Sweden, Kronor
SGD Singapore, Dollars
SHP Saint Helena, Pounds
SLL Sierra Leone, Leones
SOS Somalia, Shillings
SRD Suriname, Dollars
SYP Syria, Pounds
SZL Swaziland, Emalangeni
THB Thailand, Baht
TJS Tajikistan, Somoni
TND Tunisia, Dinars
TOP Tonga, Pa"anga
TRY Turkey, New Lira
TTD Trinidad and Tobago, Dollars
TVD Tuvalu, Tuvalu Dollars
TWD Taiwan, New Dollars
TZS Tanzania, Shillings
UAH Ukraine, Hryvnia
UGX Uganda, Shillings
UYU Uruguay, Pesos
UZS Uzbekistan, Sums
VND Viet Nam, Dong
VUV Vanuatu, Vatu
WST Samoa, Tala
XAF Communauté Financière Africaine BEAC, Francs
XCD East Caribbean Dollars
XDR International Monetary Fund (IMF) Special Drawing Rights
XOF Communauté Financière Africaine BCEAO, Francs
XPF Comptoirs Français du Pacifique Francs
YER Yemen, Rials
ZAR South Africa, Rand
=== ========================================================

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

=== ========================================================
USD United States of America, Dollars
AED United Arab Emirates, Dirhams
AFN Afghanistan, Afghani
ALL Albania, Leke
AMD Armenia, Drams
ANG Netherlands Antilles, Guilders
AOA Angola, Kwanza
ARS Argentina, Pesos
AUD Australian dollar
AWG Aruba, Guilders
AZN Azerbaijan, New Manats
BAM Bosnia and Herzegovina, Convertible Marka
BBD Barbados, Dollars
BDT Bangladesh, Taka
BGN Bulgaria, Leva
BHD Bahrain, Dinars
BIF Burundi, Francs
BMD Bermuda, Dollars
BND Brunei Darussalam, Dollars
BOB Bolivia, Bolívianos
BRL Brazil, Brazil Real
BSD Bahamas, Dollars
BTN Bhutan, Ngultrum
BWP Botswana, Pulas
BZD Belize, Dollars
CAD Canada, Dollars
CDF Congo/Kinshasa, Congolese Francs
CHF Switzerland, Francs
CLP Chile, Pesos
CNY China, Yuan Renminbi
COP Colombia, Pesos
CRC Costa Rica, Colones
CUC Cuba Convertible Peso
CUP Cuba, Pesos
CVE Cape Verde, Escudos
CZK Czech Republic, Koruny
DJF Djibouti, Francs
DKK Denmark, Kroner
DOP Dominican Republic, Pesos
DZD Algeria, Algeria Dinars
EGP Egypt, Pounds
ERN Eritrea, Nakfa
ETB Ethiopia, Birr
EUR Euro Member Countries, Euro
FJD Fiji, Dollars
FKP Falkland Islands (Malvinas), Pounds
GBP United Kingdom, Pounds
GEL Georgia, Lari
GGP Guernsey, Pounds
GHS Ghana, Cedis
GIP Gibraltar, Pounds
GMD Gambia, Dalasi
GNF Guinean franc
GTQ Guatemala, Quetzales
GYD Guyana, Dollars
HKD Hong Kong, Dollars
HNL Honduras, Lempiras
HRK Croatia, Kuna
HTG Haiti, Gourdes
HUF Hungary, Forint
IDR Indonesia, Rupiahs
ILS Israel, New Shekels
IMP Isle of Man, Pounds
INR India, Rupees
IQD Iraq, Dinars
IRR Iran, Rials
ISK Iceland, Kronur
JMD Jamaica, Dollars
JOD Jordan, Dinars
JPY Japan, Yen
KES Kenya, Shillings
KGS Kyrgyzstan, Soms
KHR Cambodia, Riels
KMF Comoros, Francs
KRW Korea (South), Won
KWD Kuwait, Dinars
KYD Cayman Islands, Dollars
KZT Kazakhstan, Tenge
LAK Laos, Kips
LBP Lebanon, Pounds
LKR Sri Lanka, Rupees
LRD Liberia, Dollars
LSL Lesotho, Maloti
LYD Libya, Dinars
MAD Morocco, Dirhams
MDL Moldova, Lei
MGA Madagascar, Ariary
MKD Macedonian denar
MMK Myanmar (Burma), Kyats
MNT Mongolia, Tugriks
MOP Macau, Patacas
MUR Mauritius, Rupees
MVR Maldives (Maldive Islands), Rufiyaa
MWK Malawi, Kwachas
MXN Mexico, Pesos
MYR Malaysia, Ringgits
MZN Mozambique, Meticais
NAD Namibia, Dollars
NGN Nigeria, Nairas
NIO Nicaragua, Cordobas
NOK Norway, Krone
NPR Nepal, Nepal Rupees
NZD New Zealand, Dollars
OMR Oman, Rials
PAB Panama, Balboa
PEN Peru, Nuevos Soles
PGK Papua New Guinea, Kina
PHP Philippines, Pesos
PKR Pakistan, Rupees
PLN Poland, Zlotych
PYG Paraguay Guarani
QAR Qatar, Rials
RON Romania, New Lei
RSD Serbia, Dinars
RUB Russia, Rubles
RWF Rwanda, Rwanda Francs
SAR Saudi Arabia, Riyals
SBD Solomon Islands, Dollars
SCR Seychelles, Rupees
SDG Sudan, Pounds
SEK Sweden, Kronor
SGD Singapore, Dollars
SHP Saint Helena, Pounds
SLL Sierra Leone, Leones
SOS Somalia, Shillings
SRD Suriname, Dollars
SYP Syria, Pounds
SZL Swaziland, Emalangeni
THB Thailand, Baht
TJS Tajikistan, Somoni
TND Tunisia, Dinars
TOP Tonga, Pa"anga
TRY Turkey, New Lira
TTD Trinidad and Tobago, Dollars
TVD Tuvalu, Tuvalu Dollars
TWD Taiwan, New Dollars
TZS Tanzania, Shillings
UAH Ukraine, Hryvnia
UGX Uganda, Shillings
UYU Uruguay, Pesos
UZS Uzbekistan, Sums
VND Viet Nam, Dong
VUV Vanuatu, Vatu
WST Samoa, Tala
XAF Communauté Financière Africaine BEAC, Francs
XCD East Caribbean Dollars
XDR International Monetary Fund (IMF) Special Drawing Rights
XOF Communauté Financière Africaine BCEAO, Francs
XPF Comptoirs Français du Pacifique Francs
YER Yemen, Rials
ZAR South Africa, Rand
=== ========================================================

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
