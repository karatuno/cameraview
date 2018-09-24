# Custom CameraView

// forked from google cameraview  
-removed aspect ration selector  
-default full screen aspect ratio  
-removed black screen after OnResume is called in API 23  

## Update 23/09/2018
- Frame Stop Capture preview


*This is a preview release. The API is subject to change.*

This is not an official Google product.

CameraView aims to help Android developers easily integrate Camera features.

Requires API Level 9. The library uses Camera 1 API on API Level 9-20 and Camera2 on 21 and above.

| API Level | Camera API | Preview View |
|:---------:|------------|--------------|
| 9-13      | Camera1    | SurfaceView  |
| 14-20     | Camera1    | TextureView  |
| 21-23     | Camera2    | TextureView  |
| 24        | Camera2    | SurfaceView  |

## Features

- Camera preview by placing it in a layout XML (and calling the start method)
- Configuration by attributes
  - Aspect ratio (app:aspectRatio) //removed
  - Auto-focus (app:autoFocus)
  - Flash (app:flash)
  
## Added Features

  - Aspect ratio automatically selected according to screen  
  - Frame stop capture preview


You can see a complete usage in the demo app.

## Contribution

See [CONTRIBUTING.md](/CONTRIBUTING.md).
