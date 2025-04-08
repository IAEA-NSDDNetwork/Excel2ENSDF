# Excel2ENSDF  
Creates ENSDF formatted file from Excel. 

Excel2ENSDF  is part of the [ENSDF Analysis and Utility Programs](https://nds.iaea.org/public/ensdf_pgm/).

Please address any feedback to Jun Chen chenj@frib.msu.edu

## Change history

#### 2025-04
Add an option in the "Operation on ENSDF" tool window (in the popup menu from a right-click on a blank area) to 
estimate and assign uncertainties for gamma-ray intensities without uncertainties using a smoothly-varing function 
of gamma-ray intensity, based on an authors' general statement, like "uncertainty ranges from 5% to 20% depending on intensity".
For example, %(dIg/Ig)=A/(Ig+B), with parameter A and B determined from %5 at Ig(max)=100 and %20 at Ig(min)=0.

#### 2025-03
Add feature for making operations on ENSDF data records using regular arithmetic expressions, like
an example input expression='1.23(5)*(R+3.45(12))*(1+CC)/2.5(2)', where 'R' is used to represent the record
to be made operation on, 'CC' is the reserved ENSDF name of CC record, '1.23(5)' is a standard value(uncertainty) 
pair in the ENSDF-style uncertainty format. In the operations, 'R' will be replaced with the actual value of specified
record (selected from a dropdown list) and 'CC' will be replaced with the actual value of the CC record, in 
each record line of specified type (e.g., gamma).

#### 2023-05
Bug fix

#### 2023-04
Bug fix

#### 2022-11
Add new features for making operations on ENSDF data records, like adding, multiplying

#### 2022-09
Bug fixes

#### 2022-06
* Version 2022-06

#### 2022-04
* New Version

## Disclaimer

Neither the author nor anybody else makes any warranty, express or implied, or assumes any legal liability or responsibility for the accuracy, completeness or usefulness of any information disclosed, or represents that its use would not infringe privately owned rights.
