# Amazon OCR results for STVQA and TextVQA dataset

This repo contains small code snippet to get the OCR of STVQA and TextVQA.
All the json files are the RAW format obtained from Amazon's OCR pipeline.

## Download the OCR results

All the OCR can be found in [ link ](https://cvcuab-my.sharepoint.com/:f:/g/personal/abiten_cvc_uab_cat/Eju4_yZ7xGNHssTIa-DXomsBALTz_H3bDS6u-2MBBzDoCg?e=ATRchW).

### STVQA OCR

The links to download the raw jsons for OCR.

- [ train set OCR ](https://cvcuab-my.sharepoint.com/:u:/g/personal/abiten_cvc_uab_cat/Edt1_NqILSJDnQIpDVA2HUwBUoaCWbLfLRmBMem-itPu1w?e=oslxYg)

- [ test set OCR ](https://cvcuab-my.sharepoint.com/:u:/g/personal/abiten_cvc_uab_cat/EcM_pcapGJdHkctMuUtiwocBfPLWorkplghgPeONtDL2Hw?e=jbeEzz)

### TextVQA OCR

The links to download the raw jsons for OCR.

- [ train set OCR ](https://cvcuab-my.sharepoint.com/:u:/g/personal/abiten_cvc_uab_cat/EVH3VguqPD5Phc61Y3bEI_4BMbooDm00npz2fwkdsrVfFw?e=H2WjUF)

- [ val set OCR ](https://cvcuab-my.sharepoint.com/:u:/g/personal/abiten_cvc_uab_cat/ETmSGqNHHYBEqWFV2JJAbKUB-ayU4ntwaKyfAX0nzJ-RaQ?e=VbhAK7)

- [test set OCR](https://cvcuab-my.sharepoint.com/:u:/g/personal/abiten_cvc_uab_cat/Edu6tryabOxNlrORabNZxKYBUNaVvqQvv8H404euJNchIw?e=zS1z0M)

## The Code

You can find the code in the `get_data.ipynb` on how to obtain the OCR from Amazon.

You need an AWS account. Also, you need to put the data to the S3 bucket.

You can also upload the images to OCR pipeline, however, that resulted in a lot of error.
