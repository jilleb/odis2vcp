# odis2vcp
Converter for ODIS XML Datasets to VCP XML format.

Usage: 
`odis2vcp.py [-h] -i IN [-f FMT] -d DESC`

Arguments:
  -h, --help            show this help message and exit
  -i IN, --in IN        Input file path
  -f FMT, --fmt FMT     Output format: vcp (default) or raw.
  -d DESC, --desc DESC  Output file description. E.g. "Seat Leon 2016"

Example: 
`python odis2vcp.py -i ODIS_dataset.xml -d "Seat Leon 2016"`

Result:
```Module: 19
 Start_Address: 0x000A80
 ZDC Name: V1234567ZJ
 ZDC version: 0001
 Login: 20103
 Extracting VCP data to "19 VCP 0x000A80 V1234567ZJ 0001 - Seat Leon 2016.xml"

 Module: 19
 Start_Address: 0x0002388
 ZDC Name: V1234567ZJ
 ZDC version: 0001
 Login: 20103
 Extracting VCP data to "19 VCP 0x0002388 V1234567ZJ 0001 - Seat Leon 2016.xml"

 Module: 19
 Start_Address: 0x1B80
 ZDC Name: V1234567ZJ
 ZDC version: 0001
 Login: 20103
 Extracting VCP data to "19 VCP 0x1B80 V1234567ZJ 0001 - Seat Leon 2016.xml"
