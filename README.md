# **Hyperspectral imaging dataset**


![Hyperspectral imaging dataset](fig/Dataset.png)

<p style="text-align: justify;">
    We present the databases of hyperspectral images (HSIs) that were used to support our research. The images are of a wide variety of real-world materials and objects. We are making these databases available to the research community. Details of the database can be found in our manuscript.
    <p>

## **1. Data Information**

| Database  ID               | D1              | D2             |
| :------------------------- |:--------------- |:-------------- |
| range of wavelength        | 400-1000 nm     | 400-1700 nm    |
| spectral sampling interval | 10 nm           | 10 nm          |
| Number of bands            | 61              | 131            |
| Spatial resolution         | 960×1230 pixels | 640×660 pixels |
| Image format               | h5              | h5             |






## **2. Database Organization**

<p style="text-align: justify;">
    We have a total of 1000 scenes, comprising 500 outdoor scenes depicting various landscapes such as roads, buildings, flowers, vehicles and others, alongside 500 indoor scenes showcasing items like food, cloth, toys and models. Two distinct databases are provided, denoted as Database 1 (D1) and Database 2 (D2), each corresponding to these scenes. The D1 database contains hyperspectral data with a spectral response range of 400-1000 nm (at 10 nm intervals), and each h5 file consists of 61 channels of images measuring 960×1230 pixels. Simultaneously, the D2 database contains hyperspectral data with a spectral response range of 400-1700 nm (at 10 nm intervals), and each h5 file comprises 131 channels of images measuring 640×660 pixels.
</p>

The Databases are available in this repository https://www.scidb.cn/s/6V3qMn

D1 is composed of “HSI_400_1000_0001_0200.zip”, “HSI_400_1000_0201_0400.zip”, “HSI_400_1000_0401_0600.zip”, “HSI_400_1000_0601_0800.zip”, and “HSI_400_1000_0801_1000.zip”. Each package contains 200 hyperspectral images, a total of 1000. The corresponding RGB references are deposited in the “Synthesized_RGB_Image_400_1000.zip”.

D2 is composed of “HSI_400_1700_0001_0200.zip”, “HSI_400_1700_0201_0400.zip”, “HSI_400_1700_0401_0600.zip”, “HSI_400_1700_0601_0800.zip”, and “HSI_400_1700_0801_1000.zip”. Each package contains 200 hyperspectral images, a total of 1000. The corresponding RGB references are deposited in the “Synthesized_RGB_Image_400_1700.zip”.




## 3. Data availability statement
<p style="text-align: justify;">
The database is public to editor and reviewers during the review period.  If other individuals/institutions require access to download or utilize the dataset, they are kindly requested to contact the data owner via email for assistance. This will ensure proper coordination and facilitation of the data access process. 
</p>

## 4. Contact Information
If you have any questions, please feel free to contact us (bian@bit.edu.cn).


