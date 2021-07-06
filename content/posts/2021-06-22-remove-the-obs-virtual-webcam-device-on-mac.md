---
title: Remove the OBS virtual webcam device on Mac
summary: Steps to remove the OBS virtual device on Mac.
author: Danesh Manoharan
type: post
date: 2021-06-23T02:44:23+00:00
url: /posts/remove-the-obs-virtual-webcam-device-on-mac/

---
The OBS virtual webcam device doesn&#8217;t always get removed properly when OBS studion is removed on Mac. Here&#8217;s how to manually remove the device.

1. Using finder navigate to &#8220;/Library/CoreMediaIO/ Plug-Ins/DAL/&#8221;.  
   `Command + Shift + g` will bring up the goto dialog.  
<img loading="lazy" width="497" height="214" class="wp-image-8427" style="width: 400px;" src="https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img3.png" alt="goto dialog" srcset="https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img3.png 497w, https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img3-450x194.png 450w" sizes="(max-width: 497px) 100vw, 497px" />

2. Delete the &#8220;obs-mac-virtualcam.plugin&#8221; file.  
<img loading="lazy" width="859" height="248" class="wp-image-8428" style="width: 450px;" src="https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img2.png" alt="remove file" srcset="https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img2.png 859w, https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img2-450x130.png 450w, https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img2-768x222.png 768w" sizes="(max-width: 859px) 100vw, 859px" />

3. Verify if the &#8220;obs-virtual-camera&#8221; device has been removed.  
    The screenshot below is from MS Teams.  
<img loading="lazy" width="455" height="186" class="wp-image-8429" style="width: 450px;" src="https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img1.png" alt="webcam list in MS Teams" srcset="https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img1.png 455w, https://thedaneshproject.com/wp-content/uploads/2021/06/remove-the-obs-virtual-webcam-device-on-mac-img1-450x184.png 450w" sizes="(max-width: 455px) 100vw, 455px" />