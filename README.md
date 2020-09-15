# ThreeDPoseTracker (preparing now)
使い方は下記のQiitaの記事を読んでください。</br>
（For instructions on how to use it, please read the following Qiita article in Japanese.）</br>
Ver.0.1.0 : https://qiita.com/yukihiko_a/items/43d09db5628334789fab</br>
Ver.0.2.0 : https://qiita.com/yukihiko_a/items/e5b07bd045611c73bbbe</br>
Ver.0.3.0 : https://qiita.com/yukihiko_a/items/82b1e50de8d81e554721</br>

## Source
Created with Unity ver 2019.3.13f1.</br>
We use Barracuda 1.0.2 to load onnx.</br>

Download nn File from our home page by clicking following URL in our HP.</br>
   https://digital-standard.com/threedpose/models/HighQualityTrainedModel.nn
Move the downloaded HighQualityTrainedModel.nn file to Asset/StreamingAssets in the unzipped folder(If you don't have a folder, make one).</br>
Turn off BarracudaRunner script DebugMode checkbox, which is in the Unity Editor's hierarchy</br>

### Other Packages
UniVRM 0.56.3(https://github.com/vrm-c/UniVRM></br>
BVH Tools(https://assetstore.unity.com/packages/tools/animation/bvh-tools-144728)</br>
Unity Standalone File Browser 1.2(https://github.com/gkngkc/UnityStandaloneFileBrowser)</br>
uOSC 0.0.2 (https://github.com/hecomi/uOSC)</br>
Unity Capture(https://github.com/schellingb/UnityCapture)</br>
Oculus Lipsync Unity 20.0.0(https://developer.oculus.com/downloads/package/oculus-lipsync-unity/)</br>
Final IK (https://assetstore.unity.com/packages/tools/animation/final-ik-14290)</br>
The Charterhouse Great Chamber glTF Data (https://sketchfab.com/3d-models/the-charterhouse-great-chamber-50e692c037784347b289d7bbcb318bed)
uWindowCapture v0.6.0 (https://github.com/hecomi/uWindowCapture)

## Performance Report</br>
This has been confirmed to work on Windows 10 only.</br>
### High Quality Trained Model </br>
GeForce RTX2070 SUPER ⇒ About 30 FPS </br>
GeForce GTX1070 ⇒ About 20 FPS </br>
### Low Quality Trained Model </br>
GeForce RTX2070 SUPER ⇒ About 60 FPS </br>


## License
### Non-commercial use</br>
・Please use it freely for hobbies and research. </br>
  When redistributing, it would be appreciated if you could enter a credit (Digital-  Standard Co., Ltd.).</br></br>
   
・The videos named as "Action_with_wiper.mp4"(
original video: https://www.youtube.com/watch?v=C9VtSRiEM7s) and "onegai_darling.mp4"(original video: https://www.youtube.com/watch?v=tmsK8985dyk) contained in this code are not copyright free.
  So you should not use those of files in other places without permission.</br></br></br>

・The room data used in this application is</br>
The Charterhouse Great Chamber : https://sketchfab.com/3d-models/the-charterhouse-great-chamber-50e692c037784347b289d7bbcb318bed</br>
David Fletcher (@artfletch : https://twitter.com/artfletch)</br></br>

### Unitychan</br>
We follow the Unity-Chan License Terms.</br>
https://unity-chan.com/contents/license_en/</br>
![Light_Frame.png](image/Light_Frame.png)</br></br>

### Commercial use</br>
・In the case of developping application including free application for advertising, it costs $500 per developer.
  About complicated case, please contact us.</br>
・In the case of using this on cloud server, please contact us.</br>
・In the case of creating motion or delivering the video, and the earnings surpass $500 or there is the expectation,
  it costs $500. Otherwise it is for free.</br></br>
  
## Contact</br>
If you have any questions, please feel free to contact us from following URL.</br>
Contact form:  https://digital-standard.com/contact/ </br>
E-Mail: info@digital-standard.com </br>
https://digi-rooms.com/
