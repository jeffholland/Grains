GRAINS - a granular processing patch

HOW TO USE:

1. Open "grains.pd."

The application will initialize with "ms1.wav", one of the provided audio 
files, as the input file.
You can import your own WAV files by placing them in the "audio" folder 
and typing their name into the "filename" symbol box.

2. Change parameters

Click and drag on the number boxes, or click and type numbers, to change 
the parameters.

Parameters include:

- grain_dur: the duration of each sound grain, in samples.

- samples_between: the duration of silence between grains, in samples.

- percent_sample: the percentage of the sample that is to be played,
starting from the beginning.

- pitch: pitch adjustment. 1 is no change. 0.5 is 2x faster, 2 is 
2x slower, etc.

- offsets: these parameters create discrepancies between the parameters 
being passed in and the ones that affect the actual output. Honestly even 
I don't understand exactly what they're doing. Just adding numbers to 
other numbers to achieve an interesting result.

3. Record output

Type the desired output filename into the output_filename symbol box and 
click on the "rec" toggle box. Click on it again when finished.