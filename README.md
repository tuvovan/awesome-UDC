# State-of-the-art of Under Display Camera Image Restoration

### LAST UPDATE: 27th July 2022

This repository provides state-of-the-art (SoTA) papers and results for Under Display Camera (UDC). We do our best to keep this repository up to date.  If you do find a problem's SoTA result is out of date or missing, please raise this as an issue (with this information: research paper name, dataset, metric, source code and year). We will fix it immediately.

Please note that this repo is the very first repo in this field, and UDC is early-merging topics so the content will not very much.
## Papers

* Image Restoration for Under-Display Camera [[Project]](https://yzhouas.github.io/projects/UDC/udc.html) [[paper]](https://arxiv.org/pdf/2003.04857v1.pdf)
* Deep Atrous Guided Filter for Image Restoration in Under Display Cameras [[paper]](https://arxiv.org/pdf/2008.06229v2.pdf) [[code]](https://github.com/varun19299/deep-atrous-guided-filter)
* Controllable Image Restoration for Under-Display Camera in Smartphones [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Kwon_Controllable_Image_Restoration_for_Under-Display_Camera_in_Smartphones_CVPR_2021_paper.pdf)]

## Challenges
* Real-world Computer Vision from Inputs with Limited Quality [[RLG]](https://rlq-tod.github.io/index.html)

## UDC Dataset
The new dataset is collected by a Monitor-Camera Imaging System (MCIS). We utilized 300 images form DIV2K dataset. For each display type: T-OLED, and P-OLED, we collected paired display-free and display-covered imaging data in the form of both 16-bit RAW sensor data, and 8-bit RGB. Images have resolution of 1024*2048. We only release the paired RGB data for training. Our RGB is linear, so users can reverse the process to generate 8-bit RAW sensor data. Please refer to our report for more details of the dataset.

* UDC Training Dataset (RGB, 2.1G) [[Microsoft OneDrive](https://1drv.ms/u/s!At4CtN8cceVdbASQv94dYsMOkSk)] [[Google Drive](https://drive.google.com/file/d/1zB1xoxKBghTTq0CKU1VghBoAoQc5YlHk/view?usp=sharing)]
* UDC Validation and Testing Dataset and evaluation codes (RGB, 1.2G) [[Microsoft OneDrive](https://1drv.ms/u/s!At4CtN8cceVdbTR1bFO708hqPLw?e=qW8uMZ)] [[Google Drive](https://drive.google.com/file/d/171_-iTN7bIhLHMZiGHV8zgXtoTG3T297/view?usp=sharing)]

Email: vovantu.hust@gmail.com
