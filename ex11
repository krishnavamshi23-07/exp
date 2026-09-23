Ex. No 1: Evidence Acquisition Using Access Data FTK Imager 

Date: 

# Description 

Forensic Toolkit or FTK is a computer forensics software product made by Access Data. This is a Windows based commercial product. For forensic investigations, the same development team has created a free version of the commercial product with fewer functionalities. This FTK Imager tool is capable of both acquiring and analyzing computer forensic evidence. 

The evidence FTK Imager can acquire can be split into two main parts. They are: 

- Acquiring volatile memory 

- Acquiring non-volatile memory (Hard disk) 

There are two possible ways this tool can be used in forensics image acquisitions: 

- Using FTK Imager portable version in a USB pen drive or HDD and opening it directly from the evidence machine. This option is most frequently used in live data acquisition where the evidence PC/laptop is switched on. 

- Installing FTK Imager on the investigator’s laptop. 

In this case the source disk should be mounted into the investigator’s laptop via write blocker. The write blocker prevents data being modified in the evidence source disk while providing read-only access to the investigator’s laptop. This helps to maintain the integrity of the source disk. 

Acquiring volatile memory using FTK Imager 

The FTK Imager tool helps investigators to collect the complete volatile memory (RAM) of a computer. The following steps will show you how to do this. 

Open FTK Imager and navigate to the volatile memory icon (capture memory). 



<!-- Start of picture text -->
———_<br>feeavesew Bede teeGOs. yas mmr.<br>a ‘nose sls Sa eas<br>"Navigate to the destination location where you need to save the captured volatile memory and create a file name.<br>‘Memory Capture Be<br>Destination path:<br>DestnatonC:\Users\koush\Downloads\Phonememdump.mem flename: Link C erowse —)<br>Grouse pagetie<br>posetie.srs<br>create<br>401 fie<br>smemcapture.adt<br>Capture Memory ‘cancel<br><!-- End of picture text -->

NOTE: This tool provides options to include pagefile and AD1 files when acquiring the volatile memory. 

Pagefile: The pagefile (pagefile.sys) is used in Windows operating systems as volatile memory due to limitation of physical random-access memory (RAM). It is located under the “C” partition ready to use as volatile memory when the existing RAM capacity is exceeded. 

So this file can have quite a bit of valuable data when considering the volatile memory. Therefore, it is recommended to capture and collect this file in the acquisition. 

AD1 file: AD1 is the FTK imager image file. The investigator has the option to create an AD1 file for later use. 

Clicking the “capture memory” button will start acquiring the volatile memory. 



<!-- Start of picture text -->
Memory Progress<br>Destination: _C:\Ysers\koush\Dowmloads\Phone Link\memdump.mem<br>Status: Dumping RAM: 368/19¢8 [18%]<br><!-- End of picture text -->

NOTE: Once the acquisition has completed, the destination folder will have the acquired memory with the file extension of “.mem”. 

Acquiring non-volatile memory (Disk Image) using FTK Imager 

As previously stated, this same tool can be used to collect a disk image as well. Open FTK Imager and navigate to “Create Disk Image”. 



<!-- Start of picture text -->
| Ble View Mode Heb<br>eeaeceGROesc-m es Dea mmae.<br>Evidence Tree File List<br>Name |_____site| type ___| Date Modifies_|<br><!-- End of picture text -->

Now select the source that you need to acquire. 



<!-- Start of picture text -->
‘Select Source 3B<br>‘Please Select the Source Evidence Type<br>© Physical Dive<br>© Loge Ove<br>© tageFle<br>© Conterts<br>fogea feofdevel aFolder anatyas only exciudes deleted unatocated etc )<br>© Femico Device (mutiple CD/DVD)<br>cok | Net> | Corea Hee<br><!-- End of picture text -->

NOTE: FTK Imager is capable of acquiring physical drives (physical hard drives), logical drives (partitions), image files, contents of a folder, or CDs/DVDs. Investigators can connect external HDDs into the collection computer 

via write blocker and use the “logical drive” option to select the mounted HDD as a partition. Collecting Physical Drives 

Select the “Physical Drive” option. 

Select the drive you need to acquire and click “Finish”. 



<!-- Start of picture text -->
selectDrive<br>‘Source<br>Drive Selection<br>Please select from the following available drives:<br>|PHYSICALDRIVEO- NVMe PHISON EM280512GMN48-PE2ITIAS_v |<br>__<Back (Finish) |_cancet Help<br><!-- End of picture text -->

Raw (dd): This is the image format most commonly used by modern analysis tools. These raw file formatted images do not contain headers, metadata, or magic values. The raw format typically includes padding for any memory ranges that were intentionally skipped (i.e., device memory) or that could not be read by the acquisition tool, which helps maintain spatial integrity (relative offsets among data). 

SMART: This file format is designed for Linux file systems. This format keeps the disk images as pure bitstreams with optional compression. The file consists of a standard 13-byte header followed by a series of sections. Each section includes its type string, a 64-bit offset to the next section, its 64-bit size, padding, and a CRC, in addition to actual data or comments, if applicable. 

E01: this format is a proprietary format developed by Guidance Software’s EnCase. This format compresses the image file. An image with this format starts with case information in the header and footer, which contains an MD5 hash of the entire bit stream. This case information contains the date and time of acquisition, examiner’s name, special notes and an optional password. 

AFF: Advance Forensic Format (AFF) was developed by Simson Garfinkel and Basis Technology. Its latest implementation is AFF4. The goal is to create a disk image format that does not lock the user into a proprietary format that may prevent them from being able to properly analyze it. 

Now enter the case details. 



<!-- Start of picture text -->
Create Image os<br>Evidence Item Information x |<br>——<br>ee<br>fiique Bemaptiore —_—_—S 1<br>a)<br>ise<br><sok (oes) (_ oe<br>— —_<br><!-- End of picture text -->

Add an image destination (where the image file will be saved), image file name and fragment size. 



<!-- Start of picture text -->
Create Image &<br>Select Image Destination x<br>|<br>mage Destination Folder<br>D:\New folder (4) Browse<br>Image Filename (Excluding Extension)<br>ease 1<br>For Raw, E01, and AFF formats:‘mage Fragme0 = do n ott size fragment (MB) oo)TOO ___<br>Compression (0=None, 1=Fastest,.., 8=Smallest) © =]<br>Use AD Encryption(7)<br><td et) [ta<br><!-- End of picture text -->

Image Fragment Size (MB): this option will separate the image file into multiple images and save them in the same destination. If you need only one file instead of creating multiple fragmented images, you must set the image fragment size to “0”. 

Select the “verify images after they are created” option. This will verify the hash values once the image has created. In order to ensure integrity, it is recommended to use this option. However, this will increase the time taken to acquire your evidence, especially if you’re dealing with a large disk image size. 



<!-- Start of picture text -->
Create Image x<br>‘Image Source<br>EA<br>Staring Evidence Number: 1<br>Image Destination(s)<br>Ds\cased [raw/dd]<br>Add. Edit. Remove<br>|Add Overfiow Location<br>Civerifycreate imagesdirectory afterlistingsthey areof all created files in the—_{_}imagePrecalculateafter theyProgressare crea S t atisticsed<br>[itn<br><!-- End of picture text -->

Click “start” to start acquiring. 

Once acquiring is complete, it will create a text file including all the information it has acquired. 



<!-- Start of picture text -->
Creating Image x<br>Image Source: E:\<br>Destination: D:\case 1<br>Status: Image created successfully<br>Progress<br>Elapsed time: 0:00:10<br>Estimated time left:<br>Image Summary... Close<br><!-- End of picture text -->



Hash values are matched. 

**Rubrics:** 

|**Criteria & Marks Assigned**|**Mark Allotted**|**Mark Awarded**|
|---|---|---|
|**1. GitHub Activity & Submission Regularity**|**3**||
|**2. Application of Forensic Tools & Practical Execution**|**3**||
|**3. Documentation & Reporting**|**2**||
|**4. Engagement, Problem-Solving & Team**<br>**Collaboration**|**2**||
|**Total**|**10**||



# **Result:** 

The disk image was successfully acquired using FTK Imager without errors.The generated hash values matched, confirming the integrity of the acquired forensic evidence. 

