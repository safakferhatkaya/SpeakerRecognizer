# Speaker Recognizer

It was made as a term project of ELM368 Digital Signal Processing course.

In this project, with the analysis made from the 3-second audio data kept in the database of the group members; It is determined which group member the owner of the sound received as input belongs to.
The path followed for this is as follows:
A low-pass filter designed to suppress noise has been applied to the sounds.
The MFCC of the sounds in the database and the input sound were calculated, 
then the correlation coefficients were calculated using Kendall's method of 
correlation coefficients to calculate the similarities between the data. 
Cumulative similarities are calculated and the person with the highest cumulative similarity is printed on the screen as the owner of the voice.

Here is the sample output.

![image](https://user-images.githubusercontent.com/78663077/120869979-5cf60b80-c5a0-11eb-9b8b-90b480820b33.png)

Here is the denoising filter's magnitude spectrum. 
This is designed in pyfda, you can find it with the name a18_filtre.mat.

![image](https://user-images.githubusercontent.com/78663077/120870366-6b90f280-c5a1-11eb-8ba3-1e29ce3161c1.png)
