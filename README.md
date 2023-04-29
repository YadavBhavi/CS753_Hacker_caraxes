# CS753_Hacker_Caraxes
Explore the impact of different types of noise on the audio-visual speech separation task. 
We are creating a synthetic dataset that contains speech signals corrupted with various types of noise such as white noise and pink noise, and evaluate the performance of the VisualVoice model on this dataset

## Run Locally

Import all the files from the original source ([VisualVoice](https://github.com/facebookresearch/VisualVoice/blob/main/README.md)). 
In Hacker.ipynb, make appropriate changes in order to run your .mp4 file.
This accepts a raw .mp4 file, Which is processed to obtain two video files with ROI, further used to obtain two wav files. 

## Authors 
@inproceedings{gao2021VisualVoice,
  title = {VisualVoice: Audio-Visual Speech Separation with Cross-Modal Consistency},
  author = {Gao, Ruohan and Grauman, Kristen},
  booktitle = {CVPR},
  year = {2021}
}
