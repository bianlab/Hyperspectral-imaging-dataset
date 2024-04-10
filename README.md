# **Hyperspectral imaging dataset**


![Hyperspectral imaging dataset](fig/Dataset.png)

<p style="text-align: justify;">
    We present the databases of hyperspectral images (HSIs) that were used to support our research. The images are of a wide variety of real-world materials and objects. We are making these databases available to the research community. Details of the database can be found in our manuscript.
    <p>

## **1. Image Capture Information**

| Camera              |[FigSpec-23](https://www.figspec.com/h-col-141.html)      |[GaiaField Pro-N17E-HR](https://www.dualix.com.cn/en/Goods/desc/id/123/aid/999.html) | Data concatenation |
| :------------------ | :-------------- | :-------------------- | :----------------- |
| Database  ID        | D1              | D2                    | D3                 |
| Range of wavelength | 400-1000 nm     | 900-1700 nm           | 400-1700 nm        |
| Steps               | 2.5 nm          | 5 nm                  | -                  |
| Sampling steps      | 10 nm           | 10 nm                 | 10 nm              |
| Number of bands     | 61              | 81                    | 131                |
| Spatial resolution  | 960×1230 pixels | 640×660 pixels        | 640×660 pixels     |
| Image format        | h5              | h5                    | h5                 |

**NOTE:**

<p style="text-align: justify;">
The raw data acquired using scanning hyperspectral imaging systems contain the Quantum Efficiency (QE) of the sensor, introducing bias compared to the real spectra. We calibrated the collected HSIs to eliminate the QE influence of each camera. We provide the QE data named ‘QE_FS23.mat’ and ‘QE_GaiaField.mat’. Consequently, the calibrated data is better suited for computational spectral reconstruction tasks, as these data accurately characterize the real radiation energy distribution of target scenes.
        <p>




## **2. Database Organization**

<p style="text-align: justify;">
    We have a total of <b>1000 scenes</b>, with <b>500 outdoor scenes</b> (such as roads, buildings, flowers, vehicles, etc.) and <b>500 indoor scenes</b> (including food, cloth, toy, model, etc). We provide <b>3 databases</b> corresponding to these scenes. The original hyperspectral images captured using the Figspec-23 <b>(Database 1, D1)</b> and GaiaField Pro-N17E-HR hyperspectral cameras <b>(Database 2, D2)</b>. <b>Database 3 (D3)</b> is concatenated from Database 1 (D1) and Database 2. <br>The outdoor scenes were photographed in Beijing, China from April to June and October to December, encompassing various weather conditions including sunny, cloudy, and overcast. The indoor scenes captured under laboratory illuminant (Thorlabs SLS302, 10W output optical power, 1115lux).
</p>


The collection of image pairs is available at this repository [10.5281/zenodo.10952018](https://zenodo.org/doi/10.5281/zenodo.10952017)

## 3. Paper
Under Review.


## 4. Data availability statement
<p style="text-align: justify;">
The database is public to editor and reviewers during the review period.  If other individuals/institutions require access to download or utilize the dataset, they are kindly requested to contact the data owner via Zenodo <a href="https://help.zenodo.org/docs/share/access-requests/request-access/">Request access</a> or email for assistance. This will ensure proper coordination and facilitation of the data access process. 
</p>

## Contact Information
If you have any questions, please feel free to contact us (bian@bit.edu.cn).


