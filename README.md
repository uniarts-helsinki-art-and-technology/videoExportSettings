
# Exporting video files

It's sometimes hard to export video in correct file format in order to meet the requirements of the media player. Currently we provide instruction for Handbrake but later we'll add also instructions for FFMPEG. These Handbrake presets are here to help you when preparing the file.

## 1. Download Handbrake

Download the awesome open source video transcoder Handbrake from here:
https://handbrake.fr/

## 2. Download presets

Click "Code" and select "Download zip" from this github page.

## 2. Select correct preset

Select correct preset for your media player from table below. The number in table refers to the number in preset file name.

Media player | HD video | HD video + sound (stereo) | 4K video | 4K video + sound (stereo) |
--- | --- | --- | --- |--- |
BrightSign XD3 | 0 | 0 | 0 | [4K_H265_10bit_RF15_Stereo](https://github.com/uniarts-helsinki-art-and-technology/videoExportSettings/blob/main/4K_H265_10bit_RF15_Stereo.json) |
BrightSign X | 0 | 0 | 0 | 0 |
Raspberry Pi [video player](https://github.com/uniarts-helsinki-art-and-technology/videoPlayer) | 0 | 0 | 0 | 0 |

## 3. Import preset to Handbrake

In Handbrake, select "Presets" > "Settings" > "Import" and import the selected preset.


![Import preset](https://github.com/uniarts-helsinki-art-and-technology/videoExportSettings/blob/main/handbrake_preset_import.png)


## 4. Start encoding

Select video by clicking "Open source", select correct preset from "Presets" and click start.
:-)
