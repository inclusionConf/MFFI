# MFFI: Multi-Dimensional Face Forgery Image Dataset for Real-World Scenarios
Dataset link: https://www.modelscope.cn/datasets/DDLteam/MFFI/files

## Supplementary
### Statistics of Real Face

| **Types** | **Train** | **Valid** | **Test** |
| :----: | :----: | :----: | :----: |
| CelebA | 100,0000 | -- | -- |
| RFW | -- |  60,000 | 25,000 |
| CASIA-Webface | -- | -- | 25,000 |
| Chinese Celeb | -- | -- | 30,000 |

### Statistics of Fake Face

<table>
    <tr>
        <th colspan="2">Types</th>
        <th>Train</th>
        <th>Valid</th>
        <th>Test</th>
    </tr>
    <tr>
        <td rowspan="15">Face-swapping (FS)</td>
        <td>SimSwap</td>
        <td>15000</td>
        <td>5000</td>
        <td>400</td>
    </tr>
    <tr>
        <td>FaceShifter</td>
        <td>15000</td>
        <td>5000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>InfoSwap</td>
        <td>15000</td>
        <td>5000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>HiFiface</td>
        <td>15000</td>
        <td>5000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>MegaFS</td>
        <td>15000</td>
        <td>5000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>FSGAN</td>
        <td>6000</td>
        <td>2000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>I2G</td>
        <td>15000</td>
        <td>--</td>
        <td>3600</td>
    </tr>
    <tr>
        <td>MobileFaceSwap</td>
        <td>--</td>
        <td>20000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>RAFSwap</td>
        <td>--</td>
        <td>5000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>e4s</td>
        <td>--</td>
        <td>5000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>SBI</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>AIM</td>
        <td>--</td>
        <td>--</td>
        <td>2000</td>
    </tr>
    <tr>
        <td>Facefusion</td>
        <td>--</td>
        <td>--</td>
        <td>2000</td>
    </tr>
    <tr>
        <td>FaceMerge</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>IPAdapter</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td rowspan="8">Face-reenactment (FR)</td>
        <td>FOMM</td>
        <td>30000</td>
        <td>--</td>
        <td>600</td>
    </tr>
    <tr>
        <td>ArticulatedAnimation</td>
        <td>30000</td>
        <td>--</td>
        <td>600</td>
    </tr>
    <tr>
        <td>Wav2Lip</td>
        <td>30000</td>
        <td>--</td>
        <td>600</td>
    </tr>
    <tr>
        <td>MCNet</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>DaGAN</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>HyperReenact</td>
        <td>--</td>
        <td>--</td>
        <td>2700</td>
    </tr>
    <tr>
        <td>MonkeyNet</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>AniPortrait</td>
        <td>--</td>
        <td>--</td>
        <td>5000</td>
    </tr>
    <tr>
        <td rowspan="13">Entire Face Synthesis (EFS)</td>
        <td>StyleGAN2</td>
        <td>4900</td>
        <td>--</td>
        <td>--</td>
    </tr>
    <tr>
        <td>StyleGAN3</td>
        <td>4900</td>
        <td>--</td>
        <td>--</td>
    </tr>
    <tr>
        <td>SDXL</td>
        <td>--</td>
        <td>2000</td>
        <td>600</td>
    </tr>
    <tr>
        <td>InstantID</td>
        <td>--</td>
        <td>--</td>
        <td>4300</td>
    </tr>
    <tr>
        <td>Hailuoai</td>
        <td>--</td>
        <td>--</td>
        <td>870</td>
    </tr>
    <tr>
        <td>Jimeng2.0</td>
        <td>--</td>
        <td>--</td>
        <td>1440</td>
    </tr>
    <tr>
        <td>Jimeng3.0</td>
        <td>--</td>
        <td>--</td>
        <td>450</td>
    </tr>
    <tr>
        <td>Kling1.6</td>
        <td>--</td>
        <td>--</td>
        <td>270</td>
    </tr>
    <tr>
        <td>Pika1.5</td>
        <td>--</td>
        <td>--</td>
        <td>300</td>
    </tr>
    <tr>
        <td>Pixverse</td>
        <td>--</td>
        <td>--</td>
        <td>480</td>
    </tr>
    <tr>
        <td>Vidu2.0</td>
        <td>--</td>
        <td>--</td>
        <td>1920</td>
    </tr>
    <tr>
        <td>Vivago</td>
        <td>--</td>
        <td>--</td>
        <td>450</td>
    </tr>
    <tr>
        <td>Wan2.1</td>
        <td>--</td>
        <td>--</td>
        <td>1470</td>
    </tr>
    <tr>
        <td rowspan="7">Face Editing (FE)</td>
        <td>DualStyleGAN</td>
        <td>6000</td>
        <td>--</td>
        <td>600</td>
    </tr>
    <tr>
        <td>SD_inpainting</td>
        <td>10000</td>
        <td>--</td>
        <td>--</td>
    </tr>
    <tr>
        <td>SDxl_0.1_inpainting</td>
        <td>--</td>
        <td>2200</td>
        <td>--</td>
    </tr>
    <tr>
        <td>HFGI</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>pSp</td>
        <td>--</td>
        <td>--</td>
        <td>6000</td>
    </tr>
    <tr>
        <td>FaceInpainting</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>ImageFiltering</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>Face Super-Resolution (FSR)</td>
        <td>GPEN</td>
        <td>198000</td>
        <td>27000</td>
        <td>13950</td>
    </tr>
    <tr>
        <td rowspan="6">Manual Face PhotoShop (MFPS)</td>
        <td>Random Facial Component Swapping</td>
        <td>15000</td>
        <td>--</td>
        <td>600</td>
    </tr>
    <tr>
        <td>Random Facial Component Excision</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>Full Face Swapping</td>
        <td>--</td>
        <td>--</td>
        <td>6000</td>
    </tr>
    <tr>
        <td>Facial Artifact Injection</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>Random Region Erasure</td>
        <td>--</td>
        <td>--</td>
        <td>3000</td>
    </tr>
    <tr>
        <td>Background Replacement</td>
        <td>--</td>
        <td>--</td>
        <td>6000</td>
    </tr>
    <tr>
        <td>Total</td>
        <td>50</td>
        <td>424800</td>
        <td>88200</td>
        <td>104000</td>
    </tr>
</table>

#### Notes:
1. For sample counts in the table, we adopted a rounding strategy (either ceiling or floor rounding) for statistical convenience, which may cause minor discrepancies from actual values.
2. **Random Facial Component Swapping:** First segments facial component regions (eyes, nose, mouth) from two faces, then performs random cross-swapping of corresponding components.
3. **Random Facial Component Excision:** Segments facial component regions first, followed by random excision of precisely localized component areas.
4. **Full Face Swapping:** Exchanges entire facial regions between different face images.
5. **Facial Artifact Injection:** Generates synthetic artifacts within facial component regions.
6. **Random Region Erasure:** Performs content removal on arbitrary spatial regions within the image.
7. **Background Replacement:** Substitutes the background region of a facial image with alternative scene content while preserving facial integrity.

#### Visualization of Multi-level Degradation Operations
