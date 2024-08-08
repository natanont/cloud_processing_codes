# Cloud processing codes for Data platfrom
---

This repository contains the codes for:

- Retrieving the row and column of cloud images from the latitude and longitude reference of a cloud image TIFF file, then adding this information to metadata for cloud index extraction.
- Extracting customer data simultaneously while looping through all cloud images. (Note: The `ch` parameter specifies the channel to extract for overview images. If `ch=0`, it is the red channel. Use the same ch value as in the cloud mask product.)
- Providing the Datetime for UTC+7 (Asia/Bangkok) in the output CSV.