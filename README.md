# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
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
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
![alt text](<Screenshot 2025-04-21 200528.png>)

![alt text](<Screenshot 2025-04-21 200801.png>)

![alt text](<Screenshot 2025-04-21 200808.png>)

![alt text](<Screenshot 2025-04-21 200838.png>)

![alt text](<Screenshot 2025-04-21 200921.png>)
## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
