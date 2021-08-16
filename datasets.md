---
layout: page
title: Datasets
permalink: /datasets/
---

#### Datasets

<!-- saved from url=(0036)http://cvrg.iyte.edu.tr/datasets.htm -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1254">
<title>Yalin Bastanlar - Datasets</title>
<meta http-equiv="Content-Type" content="text/html; charset=">
</head>

<body bgcolor="#FFFFFF" text="#333399" data-new-gr-c-s-check-loaded="14.1018.0" data-gr-ext-installed="">

<p><br><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b> 
0) Outdoor panoramic image dataset for semantic segmentation</b></font></p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
<table width="800" border="0">
<tbody><tr>
<td width="793"><img src="/assets/img/cameratrap.png"></td>
</tr>
</tbody></table>
<b>*</b> The dataset consists of 4005 images and can be downloaded via <a href="https://github.com/semihorhan/semseg-outdoor-pano" target="blank">project's github repo</a>.
    
<br>
    
<p><br><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b> 
1) Camera-trap dataset for animal detection or animal/non-animal image classification </b></font></p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
<table width="800" border="0">
<tbody><tr>
<td width="793"><img src="/assets/img/cameratrap.png"></td>
</tr>
</tbody></table>
<b>*</b> The dataset consists of 4005 images and can be downloaded as zip files (randomly split 8 files, ~300 MB each) using the link given <a href="https://drive.google.com/drive/folders/18BkGQTLB2lgNlXfw__cvMd9P-Fvyk5Wi?usp=sharing" target="blank">here</a>.

<br>
<b>*</b> The dataset belongs to and is shared with the permission of Republic of Turkey, Ministry of Forest and Water Affairs. It contains various species and sizes of animals. 2585 images contain animals (some contain multiple animals) and 1420 images do not contain any animal. Image size varies from 1024x1280 to 2448x3264. 
About half of the images are captured at night while the other half is captured at daytime.


<br>
<b>*</b> Image annotations are in the form of PASCAL VOC annotation (.xml) files. More information on PASCAL VOC Challenge is <a href="http://host.robots.ox.ac.uk/pascal/VOC/" target="blank">here</a>. Annotation is made only for animals - without defining species. In other words, if no object tag exists in the .xml file, that means no animal exists in that image. 
<br>
<b>*</b> Images are grouped according to their associated camera-traps. File name format is {DatasetAbbreviation}_{Field}_{Camera}_{Image Number}. For example, OB_A1_K1_0183.JPG denotes it is the 183th image from the first camera (K1) of the A1 field. OB is fixed for this dataset.<br>

<b>*</b> This is the annotated part of the dataset. Original dataset (all images from all cameras) also available upon request.
<br>
<br>
Related publication: <a href="/assets/docs/Publications/Tekeli_Bastanlar_TJEECS_AAM.pdf" target="blank">Tekeli, U., Bastanlar, Y. Elimination of Useless Images from Raw Camera-Trap Data, TJEECS, 2019, Volume 27, pp 2395-2411, DOI:10.3906/elk-1808-130</a>


<p><br><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b> 
2) Fisheye video dataset for vehicle classification </b></font></p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">

The dataset consists of more than 100 .avi files and can be downloaded as rar files (~200 MB each) using the link given
<a href="https://drive.google.com/folderview?id=0B-WJ94ZX9H02TGlIZFNFNHBOV2c&amp;usp=sharing" target="blank">here</a>.<br>
Videos containing cars, vans, motorcycles or pedestrians. Some videos contain more than one object (some with occlusions), they are mentioned in the spreadsheet provided. <br>

<br>

Related publication: <a href="/assets/docs/Publications/Baris_Bastanlar_ITSC2017.pdf" target="blank">Baris, I. and Bastanlar, Y., Classification and Tracking of Traffic Scene Objects with Hybrid Camera Systems, IEEE International Transportation Systems Conference (ITSC 2017), 16-19 October 2017, Yokohama, Japan.</a>
copyright:IEEE  https://ieeexplore.ieee.org/document/8317588/


<p><br><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>
3) Catadioptric camera video dataset for vehicle classification </b></font></p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">

The dataset can be downloaded via three different zip files using the links given below.<br>

<a href="https://drive.google.com/folderview?id=0B-WJ94ZX9H02OFF5VzZ3bE5URHc&amp;usp=sharing" target="blank"> Set 1: contains 124 videos for cars (in 5 parts, ~270 MB each).</a> <br>

<a href="https://drive.google.com/folderview?id=0B-WJ94ZX9H02dkNWVlJyNXhnVVE&amp;usp=sharing" target="blank"> Set 2: contains 104 videos for vans (minibus) (in 4 parts, ~290 MB each).</a><br>

<a href="https://drive.google.com/folderview?id=0B-WJ94ZX9H02X1p4cnlmeUJPdm8&amp;usp=sharing" target="blank"> Set 3: contains 49 videos for motorcycles (in 2 parts, ~270 MB each).</a><br>

<br>

For each video the following data is included in the zip files: i) the video itself (avi format), ii) the foreground mask of each frame obtained with background subtraction, iii) the foreground mask of each frame containing the vehicle, iv) annotated area covered by the vehicle (to be used as groundtruth) while vehicle is at the closest point to the camera.<br>
<br>
Related publication: <a href="/assets/docs/Publications/Karaimer_Bastanlar_visapp15.pdf" target="blank">Karaimer, H.C. and Bastanlar, Y., Detection and Classification of Vehicles from Omnidirectional Videos using Temporal Average of Silhouettes, Int. Conference on Computer Vision Theory and Applications (2015).</a>



<p><br><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>
4) Omnidirectional and panoramic image dataset (with annotations) to be used for human and car detection </b></font></p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">

<a href="https://drive.google.com/file/d/13xf5D-3Po9kZLO1LuBKnX__q0x3ceYBt/view?usp=sharing">Dataset 1</a> (37 MB) contains 30 omnidirectional images to detect (standing) humans (66 annotated instances) and 50 omnidirectional images to detect (side-view) cars (65 annotated instances).<br>
Dataset also contains panoramic images converted from the omnidirectional ones. 
Annotations are provided in three sets: i) rectangular bounding boxes sliding and rotating around image center for omnidirectional images, ii) proposed (dough-nut slice) annotations for omnidirectional images, iii) standard (up-right) bounding box annotations for panoramic images.
<br><br>

<a href="https://drive.google.com/file/d/1lqv0WGgyWoEDIt1fbqSUvwutN3iIW4Vm/view?usp=sharing">Dataset 2</a> (5 MB) contains synthetic catadioptric omnidirectional images which are formed by projecting perspective images to a 'defined' omnidirectional camera. One set projects 210 perspective images from INRIA person dataset, the other one projects 466 car side-views from UIUC and Darmstadt perspective image datasets.<br>
<br>

Related publication 1: <a href="/assets/docs/Publications/Cinaroglu_Bastanlar_SIU2014.pdf" target="blank">Cinaroglu, I. and Bastanlar, Y. (2014), A Direct Approach for Human Detection with Catadioptric Omnidirectional Cameras, IEEE Conference on Signal Processing and Communications Applications (SIU) 2014</a>.
<br>    
Related publication 2: <a href="/assets/docs/Publications/Cinaroglu_Bastanlar_SIVP_AAM.pdf" target="blank">Cinaroglu, I. and Bastanlar, Y. (2014), A Direct Approach for Object Detection with Catadioptric Omnidirectional Cameras, Signal, Image and Video Processing, Volume 10(2), February 2016, Pages 413-420. DOI:10.1007/s11760-015-0768-2</a>.


<p><br><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b>
5) Panoramic image dataset (with annotations) to be used for car detection </b></font></p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">

<a href="https://drive.google.com/file/d/1GhRv2EoWLplXbtkV0qNXQkmer5tyeTg1/view?usp=sharing">Dataset</a> (5MB) contains i) 25 para-catadioptric images, ii) 50 cylindrical panoramic images obtained from the catadioptric images (25 original and 25 mirrored), annotations for cars in those images, iii) 50 spherical panoramic images obtained from the catadioptric images, annotations for cars in those images.
<br><br>
Related publication: <a href="/assets/docs/Publications/Karaimer_Bastanlar_SIU2014.pdf" target="blank">Karaimer, H.C. and Bastanlar, Y. (2014), Car Detection with Omnidirectional Cameras Using Haar-like Features and Cascaded Boosting (in Turkish), IEEE Conference on Signal Processing and Communications Applications (SIU) 2014</a>.


<p><br><font face="Verdana, Arial, Helvetica, sans-serif" size="2"><b> 
6) Image datasets to be used in studies on hybrid structure-from-motion and omnidirectional camera calibration </b></font></p><font face="Verdana, Arial, Helvetica, sans-serif" size="2">
<table width="640" border="0">
<tbody><tr>
<td width="177"><img src="/assets/img/cata.jpg"><font size="2"> catadioptric</font></td>
<td width="220"><img src="/assets/img/fish.jpg"><font size="2"> fisheye</font></td>
<td width="243"><img src="/assets/img/pers.jpg"><font size="2"> perspective</font></td>
</tr>
</tbody></table>
<br>
<b>*</b> 
    <a href="https://drive.google.com/file/d/174aN1na6BUz_g5_ehFNzTsCi7WTUXrva/view?usp=sharing">Hybrid Set 1:</a> A perspective and a catadioptric omnidirectional camera (together with camera parameters and calibration images).
<br>

<b>*</b> 
    <a href="/assets/datasets/HybridSet2.ziphttps://drive.google.com/file/d/1BMrSPh_KrRM_CF0QnOe13Pc9EE7TnDhe/view?usp=sharing">Hybrid Set 2:</a> An omnidirectional camera and some frames (approx. 1/sec.) from a perspective footage (with camera parameters and calibration images).
<br>

<font face="Verdana, Arial, Helvetica, sans-serif" size="2"> <b>*</b> 
    <a href="https://drive.google.com/file/d/1JaNf3ZTk2fKz5UuSlspxvmttR42XCr_f/view?usp=sharing">Hybrid Set 3:</a> A perspective, a fisheye and a para-catadioptric omnidirectional camera (together with camera parameters and calibration images).
</font><br>

<font face="Verdana, Arial, Helvetica, sans-serif" size="2"> <b>*</b> 
    <a href="https://drive.google.com/file/d/1FqTcDsab90QY6zAYr-2RtZcOwKsiQKR9/view?usp=sharing">Hybrid Set 4:</a> A perspective and a catadioptric omnidirectional camera (together with camera parameters and calibration images).
</font><br>

<font face="Verdana, Arial, Helvetica, sans-serif" size="2"> <b>*</b> 
    <a href="https://drive.google.com/file/d/1r4tFtIV-wbZf0MihpLDZideLLbonvV3H/view?usp=sharing">Hyperbolic Calibration Set:</a> A set of calibration images for a catadioptric camera with an hyperbolic mirror (NeoVision H3S).
</font><br>
    <br>
Related publication: <a href="/assets/docs/Publications/multiview-IMAVIS2012.pdf" target="blank">Bastanlar et al.(2012), Multi-view Structure-from-Motion for Hybrid Camera Scenarios, Image and Vision Computing, vol.30(8), pp.557-572.</a>
<br>
<br>
