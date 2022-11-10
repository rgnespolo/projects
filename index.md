## Research interests
---
My work has been dedicated to develop and train machine learning/deep learning models to be employed in real time in the operating room, building computer vision tools upon it and providing surgical decision-making information.


## Portfolio
---
### A Platform for Tracking Surgeon⁠- and Observer⁠-Gaze as a Surrogate for Attention in Ophthalmic Surgery
Published paper: 
<a href="https://doi.org/10.1016/j.xops.2022.100246">A Platform for Tracking Surgeon⁠- and Observer⁠-Gaze as a Surrogate for Attention in Ophthalmic Surgery</a>

Also presented at the American Academy of Ophthalmology annual meeting 2022 
<p>
</p>
- Instance segmentation model (YOLACT-based) to track multiple instruments (vitrector, endolaser) and retinal features (retinal tear, detachment, optic disc, fovea) in real time.
- Extraction of gaze coordinates from off-the-shelf eye trackers via computer vision
- Assessment of gaze behavior among surgeons from different levels of experience
- <a href="https://github.com/rgnespolo/Gaze-Tracking-Platform-for-Surgical-Behavior-Analysis">Source code</a>
<hr>


### Real-time instance segmentation during vitreoretinal microsurgery
Published paper: 
<a href="https://doi.org/10.1016/j.oret.2022.10.002">Feature Tracking and Segmentation in Real Time via Deep Learning in Vitreoretinal Surgery – A platform for AI-Mediated Surgical Guidance</a>

Also presented at the Retina Society 54th Annual Scientific Meeting
<p>
<video width="512" height="288" autoplay muted loop src="videos/RETINA_SOC.mp4" type="video/mp4"/>
</p>
- Instance segmentation model (YOLACT-based) to track multiple instruments (vitrector, endolaser) and retinal features (retinal tear, detachment, optic disc, fovea) in real time.
- Compatible with commercially available microscopes and visualization systems.
- Tools and tissues movement coordinates can be extracted in real time or post-hoc: data generated for future ML models.
- <a href="https://github.com/rgnespolo/YOLACT_Retina_Public">Source code</a>
<hr>

### Turbulence & harmful movement detection during phacoemulsification cataract procedures
Part of the following paper: 
<a href="https://doi.org/10.1001/jamaophthalmol.2021.5742">Evaluation of Artificial Intelligence–Based Intraoperative Guidance Tools for Phacoemulsification Cataract Surgery</a>
Also presented at the 2021 ARVO Imaging in The Eye
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
Part of the following paper: 
<a href="https://doi.org/10.1001/jamaophthalmol.2021.5742">Evaluation of Artificial Intelligence–Based Intraoperative Guidance Tools for Phacoemulsification Cataract Surgery</a>
[Also presented at the 2021 ARVO Annual Meeting - PDF here](/pdf/Nespolo_ARVO_POSTER.pdf)
<br>
<a href="https://iovs.arvojournals.org/article.aspx?articleid=2774153">Abstract here</a>
<br>
<p align="center">
<img src="images/rcnn.png?raw=true" width="300px"/>
</p>
- R-CNN model trained on custom annotated dataset by experts, performing phase identification and pupil tracking (Python, Pytorch + TorchVision).
<br>

