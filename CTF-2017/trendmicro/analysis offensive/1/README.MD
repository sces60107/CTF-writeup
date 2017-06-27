# CodeGate: TrendMicro: Analysis Offsensive 100


**Category:** Analysis Offsensive 
**Points:** 100 
**Solves:** 
**Description:** 

## Write-up

Unzip file1.zip then you will get a file named [Forensic_Encyption](./Forensic_Encyption). (As you see, here is a typo)

Encounter this kind of question. The first thing I do is use foremost or binwalk to check whether there are some secret files hidden inside.

After doing this, we can extract two files,[file_1](./file_1) and [file_2](./file_1).

file\_1 is a jpg file and file\_2 is a zip file which is protected by password

Using hexedit or xxd command you can see a weird base64-encode string in the jpg header.




 
