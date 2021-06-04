# Speaker Recognizer

It was made as a term project of ELM368 Digital Signal Processing course.

In this project, with the analysis made from the 3-second audio data kept in the database of the group members; It is determined which group member the owner of the sound received as input belongs to.
The path followed for this is as follows:
Calculation of the MFCC of the voices and the input voice in the database, followed by Kendall's method of correlation coefficients to calculate the similarities between the data. Then, the person with the highest cumulative similarity of the voice is printed on the screen as the owner of the voice.
