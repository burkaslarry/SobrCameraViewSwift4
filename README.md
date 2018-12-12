# AUTHOR OF SobrCameraView  , Silas Knobel  NO LONGER  MAINTAIN . I shall maintain it through enhancement

Feel free to fork and enhance it.

SobrCameraView for iOS enhanced
======================

Just buy me a drink and I could do this all day. 

http://paypal.me/larryburkas


This is the original one, for more details and insatruction to deploy this, go this git
https://github.com/softwarebrauerei/SobrCameraView-ios

#Updates :

Warning reduced to fit Swift 4.0

#To DO


There has a completion handler on AVCaptureStillImageOutput.jpegStillImageNSDataRepresentation and stated as
// completion(image!, self.biggestRectangle(SobrCameraView.highAccuracyRectangleDetector?.features(in: enhancedImage) as! [CIRectangleFeature]))
When it goes to be rewritten as
func capture(_ captureOutput: AVCapturePhotoOutput, didFinishProcessingPhotoSampleBuffer photoSampleBuffer: CMSampleBuffer?, previewPhotoSampleBuffer: CMSampleBuffer?, resolvedSettings: AVCaptureResolvedPhotoSettings, bracketSettings: AVCaptureBracketedStillImageSettings?, error: NSError?) {

I shall work on modifying the completion handler. 

## Authors
- DeusVultHK, https://twitter.com/justingomez987
- Silas Knobel, https://github.com/katunch


## License
This is
SobrCameraView is available under the MIT license. See the LICENSE file for more info.
