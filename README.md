# Lifesaving dataset captured by drone.

## Introduction
 * We have captured videos and audios by drone for lifesaving activities. We established 10 virtual rescue situations indoors, and data were captured by drone in the same situation three times. In each of the 10 rescue situations,  mannequins dressed as firefighters, rescuers, medical staff, and the general person(male, female, child) are arranged differently every time, and the speaker who sends a rescue signal by voice is also configured differently(male, female, child).

 * We have caputred 30 sets of data for multi object detection, crowd counting, optical character recognition, speaker recognition, etc. Images were composed of 1920x1080 resolution, and voice data acquired by 7-channel microphone (16Khz sampling rate and 1024 chunk size).


## Dataset Example
* Images below are example images from dataset

* OCR example
<p align='center'>
    <img src="./config/ocr_example_01.png" alt="drawing" width="400" />
    <img src="./config/ocr_example_02.png" alt="drawing" width ="400" />
</p>

* Object recognition example
<p align='center'>
    <img src="./config/human_example_01.png" alt="drawing" width="400" /> 
    <img src="./config/human_example_02.png" alt="drawing" width="400" /> 

</p>


## Download
* [TBD](https://www.google.com)


## Directory Structure
<pre>
 [root path]/
 └──[scene number]/                  
    ├──scene_number.bag
    ├──image_times.txt
    ├──audio_times.txt
    ├──[scene_number].WAV
    ├──[scene_number].mp4(TBD)
    └──[images]/
        └──(frame_number).png
</pre>



## Acknowledgement

이 데이터는 2022년도 정부(과학기술정보통신부)의 재원으로 정보통신기획평가원의 지원을 받아 수행된 연구의 결과물임 (No.171115245, 인명 구조용 드론을 위한 영상/음성 인지 기술 고도화)

This work was supported by Institute of Information & communications Technology Planning & Evaluation (IITP) grant funded by the Korea government(MSIT) (No. 171115245, Advanced Audio-Visual Perception for Autonomous Rescue Drones)

"이 데이터는 과학기술정보통신부의 재원으로 한국지능정보사회진흥원의 지원을 받아 구축된 "위급상황 음성/음향"을 활용하여 제작된 데이터입니다. 본 데이터에 활용된 데이터는 AI 허브(aihub.or.kr)에서 다운로드 받으실 수 있습니다."