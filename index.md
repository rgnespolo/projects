## Research interests
---
My work has been dedicated to develop and train machine learning/deep learning models to be employed in real time in the operating room, building computer vision tools upon it and providing surgical decision-making information.


## Portfolio
---
### Real-time instance segmentation during vitreoretinal microsurgery
Presented at the Retina Society 54th Annual Scientific Meeting
<br>
<a>Abstract here</a>
<br>
<p>
<video width="512" height="288" autoplay muted loop src="videos/RETINA_SOC.mp4" type="video/mp4"/>
</p>
- Instance segmentation model (YOLACT-based) to track multiple instruments (vitrector, endolaser) and retinal features (retinal tear, detachment, optic disc, fovea) in real time.
- Compatible with commercially available microscopes and visualization systems.
- Tools and tissues movement coordinates can be extracted in real time or post-hoc: data generated for future ML models.
<hr>

### Turbulence & harmful movement detection during phacoemulsification cataract procedures
Presented at the 2021 ARVO Imaging in The Eye
<br>
<a href="https://iovs.arvojournals.org/article.aspx?articleid=2776698">Abstract here</a>
<br>
<p>
<video width="512" height="288" autoplay muted loop src="videos/phaco_ppt.mp4" type="video/mp4"/>
</p>
- R-CNNs for real-time surgical phase identification and pupil tracking.
- OpenCV employed for optical flow tracking of features and visual feedback.
- Contrast Limited Adaptive Histogram Equalization applied in the pupil area for better visualization of tissues.
- Tools and tissues movement coordinates extracted: data generated for future ML models.
<hr>


### Surgical phase identification using R-CNN's during cataract procedures
[Presented at the 2021 ARVO Annual Meeting - PDF here](/pdf/Nespolo_ARVO_POSTER.pdf)
<br>
<a href="https://iovs.arvojournals.org/article.aspx?articleid=2774153">Abstract here</a>
<br>
<p align="center">
<img src="images/rcnn.png?raw=true" width="300px"/>
</p>
- R-CNN model trained on custom annotated dataset by experts, performing phase identification and pupil tracking (Python, Pytorch + TorchVision).
<br>

