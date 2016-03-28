# common data augmentation methods in caffe-based deep learning framework.
Data augmentation has shown great vitalness in boosting image based deep learning approach. I implemented more than 7 data augmentation methods based on caffe deep learning framework, including light correlation, rotation, random crop, blurring, color casting, vignetting, fish eye distortion. etc. Note that my implemetation is just an online data augmentation process, which means that, given an input image, I randomly choose to apply none/one/multiple transfomation listed above. See <code>jitter_image_total( cv::Mat& cv_img_, const int crop_size )</code> function to detailed illustration.

#example images after data augmentation
<table>
<tr>
<td><a href="http://7xrja7.com1.z0.glb.clouddn.com/test_img_github.jpg"><img src="http://7xrja7.com1.z0.glb.clouddn.com/test_img_github.jpg" alt="" /></a></td>
<td><a href="http://7xrja7.com1.z0.glb.clouddn.com/img_with_fish_distortion.jpg"><img src="http://7xrja7.com1.z0.glb.clouddn.com/img_with_fish_distortion.jpg" alt="" /></a></td>
<td><a href="http://7xrja7.com1.z0.glb.clouddn.com/img_with_vignetting.jpg"><img src="http://7xrja7.com1.z0.glb.clouddn.com/img_with_vignetting.jpg" alt="" /></a></td>
<td><a href="http://7xrja7.com1.z0.glb.clouddn.com/img_with_vignetting.jpg"><img src="http://7xrja7.com1.z0.glb.clouddn.com/img_with_vignetting.jpg" alt="" /></a></td>
</tr>
</table>
