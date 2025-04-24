# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
## RITHVIK S
## 212223100045
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
lsblk
```
```
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```
```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```
## OUTPUT:
![435671756-83a427da-d372-4b72-8e54-c874c8e31f37](https://github.com/user-attachments/assets/e8319e7a-d372-4033-a785-24950889276b)
![435673271-4ed4a4a3-542d-42b8-af06-9c1eedaec949](https://github.com/user-attachments/assets/bc5dd373-1625-418e-b8e8-c95eedd49cd1)
![435672929-1fc8e81f-12c1-4927-92ca-a4a0a500950e](https://github.com/user-attachments/assets/ce60c212-8806-4cd6-bcd9-ee7ec7c1e0d3)

![435676152-d2beee48-5fee-4476-84fd-ab24954f077d](https://github.com/user-attachments/assets/47ad8ae9-5325-491f-81fc-ebcb02d31264)
![435676562-4aff8fc4-e59c-475e-bdb2-658f15c67c50](https://github.com/user-attachments/assets/de15fd73-f963-4a2e-8704-039e73de9b1b)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

