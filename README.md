# Computer-Aided Annotation for Video Tampering Dataset of Forensic Research

The annotation of video tampering dataset is a boring task that takes a lot of manpower and financial resources. At present, there is no published literature which is capable to improve the annotation efficiency of forged videos. A computer-aided annotation method for video tampering dataset is presented in this paper. This annotation method can be used to label the frames of forged video sequences. By means of comparing the original video frames with the forged video frames, we can locate the position and trajectory of the forged areas in the forged video frames. Then, we select several key points on the temporal domain according to the trajectory of the forged areas, and mark the forged area of the forged frames in the key point with a mouse. Finally, we use the linear prediction algorithm based on the coordinates of the key positions in temporal domain to generate the annotation information of forged areas in other video frames which without manually labeled. If the bounding box generated by the computer-aided algorithm deviates from the actual location of the forged area, we can use the mouse to modify the location of the bounding box during the preview period. This method combines the manually annotation with computer-aided annotation. It solves the problems of the inaccuracy of annotation by computer-aided as well as the low efficiency of annotation by manually, and meets the needs of annotation for an enormous amount of forged videos in the research of video passive forensics.

# How to use this code

python markbox.py originalvideofile.mp4 tamperedvideofile.mp4

short keys:
s: save bounding box
r: last video frame
space: next video frame
mouse right key: delete the selected bounding box
mouse left key: draw a new bounding box
ESC: quit

please see the file on arxiv for more details.
