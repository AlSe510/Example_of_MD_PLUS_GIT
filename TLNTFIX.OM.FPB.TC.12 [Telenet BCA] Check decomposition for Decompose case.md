# TLNTFIX.OM.FPB.TC.12 [Telenet BCA] Check decomposition for Decompose case
TLNTFIX_OM_FPB_TC_12

https://bass.netcracker.com/pages/viewpage.action?spaceKey=TELN&title=%5BR2.1%5DFPB+Specifications

BSSTRIBE-23136
CTDCLUS3TM-607

Anastasiia V. Kiseleva
Mariia Barsukova

Changes to discuss

## Env:

## RCA
 []
 []

## BCA
 []
 []

*  TLNTFIX.OM.FPB.TC.12

## Prerequisites
 Two New location copied from Belgium du, 3002 Antwerp du, Kleinebeerstraat du, h. 3 with different unique externalId = 1110xxx, where xxx - random letters or digits
 How to: https://bass.netcracker.com/pages/viewpage.action?pageId=1378864199
 
 Telenet BCA with: 
 1. Basic Voice Pro 2 Go with 2 Landlines on Location1
 2. Smart Voice Pro Multi on Location2
 
 user with (A) NetCracker - BSS CC TBO

*  Prerequisites

### 0.Login as user from Prerequisites
### 1.Go to BCA1 from prerequisites
### 2.Go to <Order Entry> tab ? click [New Sales Order] ? select Distribution Channel = Telesales ? Location = Location1  ? click [Create]
*ER:* 2.SO is created



### 3.Go to Basic Voice Pro 2 Go and click [Decompose Bundle]
### 4.Decompose Basic Voice Pro 2 Go to 2 new Telenet Freephone B2B Products
### 5.Fill required characteristics
### 6.Go to review tab and submit SO
*ER:* 6.SO is processed 

ER depends on checking deviation:



### 7.Go to Composite Order-> Orders tab
### 8.Check tasks and dependencies for orders from step 7
*ER:* 8.[CTDCLUS3TM-607]
New Fixed Line Products (https://bass.netcracker.com/display/TELN/%5BR2.1%5DFixed+Line+Product+New)
'FF: Allow In-flight Modifications' task dependency is removed on'TBAPI: Wait "Activation Start" notification' task
'FF: Allow In-flight Modifications' task dependency is added on 'FF: Set PONR'
[/CTDCLUS3TM-607]

[should not be checked for CTDCLUS3TM-607]
Next orders are presented:
Disconnect Free Phone Business Product (https://bass.netcracker.com/display/TELN/%5BR2.1%5DFree+Phone+Business+Product+Disconnect)
Disconnect FPB Line Product  (https://bass.netcracker.com/display/TELN/%5BR2.1%5DFPB+Line+Product+Disconnect)
Disconnect Phone Number BSS CFS (https://bass.netcracker.com/display/TELN/%5BR2.1%5DPhone+Number+BSS+CFS+Disconnect)
[/should not be checked for CTDCLUS3TM-607]



### 9.Go to <Order Entry> tab ? click [New Sales Order] ? select Distribution Channel = Telesales ? Location = Location2  ? click [Create]
*ER:* 9.SO is created



### 10.Go to Smart Voice Pro Multi and click [Decompose Bundle]
*ER:* 10.SO is processed 

ER depends on checking deviation:



### 11.Decompose Smart Voice Pro Multi to new Telenet Freephone B2B
### 12.Fill required characteristics
### 13.Go to review tab and submit SO
### 14.Go to Composite Order-> Orders tab
### 15.Check tasks and dependencies for orders from step 15
*ER:* 15.[CTDCLUS3TM-607]
New Fixed Line Product (https://bass.netcracker.com/display/TELN/%5BR2.1%5DFixed+Line+Product+New)
'FF: Allow In-flight Modifications' task dependency is removed on'TBAPI: Wait "Activation Start" notification' task
'FF: Allow In-flight Modifications' task dependency is added on 'FF: Set PONR'
[/CTDCLUS3TM-607]

[should not be checked for CTDCLUS3TM-607]
Next orders are presented:
Disconnect Free Phone Business Product (https://bass.netcracker.com/display/TELN/%5BR2.1%5DFree+Phone+Business+Product+Disconnect)
Disconnect FPB Line Product  (https://bass.netcracker.com/display/TELN/%5BR2.1%5DFPB+Line+Product+Disconnect)
Disconnect Phone Number BSS CFS (https://bass.netcracker.com/display/TELN/%5BR2.1%5DPhone+Number+BSS+CFS+Disconnect)
[/should not be checked for CTDCLUS3TM-607]


![image](https://github.com/AlSe510/Example_of_MD_PLUS_GIT/assets/92928832/2d26214b-9a3d-4705-9f00-76b30e6675fc)
