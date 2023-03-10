---
page_type: sample
languages:
- csharp
- cpp
- cppcx
- cppwinrt
products:
- windows
- windows-uwp
urlFragment: OCR
extendedZipContent:
- path: SharedContent
  target: SharedContent
- path: LICENSE
  target: LICENSE
description: "Shows how to use the optical character recognition (OCR) API to extract text in the specific language from an image."
---

<!---
  category: ControlsLayoutAndText
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=620579
--->

# OCR sample

Shows how to use Windows.Media.Ocr API. Optical character recognition (OCR) API allows for application developer to extract text in the specific language from an image.

> **Note:** This sample is part of a large collection of UWP feature samples. 
> You can download this sample as a standalone ZIP file
> [from docs.microsoft.com](https://docs.microsoft.com/samples/microsoft/windows-universal-samples/ocr/),
> or you can download the entire collection as a single
> [ZIP file](https://github.com/Microsoft/Windows-universal-samples/archive/master.zip), but be 
> sure to unzip everything to access shared dependencies. For more info on working with the ZIP file, 
> the samples collection, and GitHub, see [Get the UWP samples from GitHub](https://aka.ms/ovu2uq). 
> For more samples, see the [Samples portal](https://aka.ms/winsamples) on the Windows Dev Center. 

This sample covers:

Scenario 1: Load image from a file and extract text in user specified language.

1. Determine whether any language is OCR supported on device.
2. Get list of all available OCR languages on device.
3. Create OCR recognizer for specific language.
4. Create OCR recognizer for the first OCR supported language from GlobalizationPreferences.Languages list.
5. Load image from a file and extract text.
6. Overlay word bounding boxes over displayed image.
7. Differentiate vertical and horizontal text lines.

Scenario 2: Capture image from camera and extract text.

1. Check if specific language is available on device.
2. Capture image from camera and extract text.
3. Overlay word bounding boxes and recognized text over displayed image.

## Related topics

### Reference

[Windows.Media.Ocr namespace](https://msdn.microsoft.com/library/windows/apps/windows.media.ocr.aspx)  
[Windows.Globalization.Language class](https://msdn.microsoft.com/library/windows/apps/windows.globalization.language.aspx)  
[GlobalizationPreferences.Languages property](https://msdn.microsoft.com/library/windows/apps/windows.system.userprofile.globalizationpreferences.languages.aspx)  
[Language matching](https://msdn.microsoft.com/library/windows/apps/jj673578.aspx)  
[Windows.Graphics.Imaging.BitmapDecoder class](https://msdn.microsoft.com/library/windows/apps/windows.graphics.imaging.bitmapdecoder.aspx)  
[Windows.Media.Capture.MediaCapture namespace](https://msdn.microsoft.com/library/windows/apps/windows.media.capture.aspx)  

### Related samples

* [InkAnalysis](/Samples/InkAnalysis)
* [OCR sample](/archived/OCR/) for JavaScript (archived)

## System requirements

* Windows 10
* Camera (required by sample but not by OCR feature itself)
