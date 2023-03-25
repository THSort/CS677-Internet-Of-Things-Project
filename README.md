# Explanation of files:
# 1. README.md: This file
# 2. 200_baseline.csv: This file is the data that was recorded from the accelerometer when the phone was still and no one was speaking.
# 3. 200_GoogleAssistant.csv: This file is the data that was recorded from the accelerometer when the phone was still and Google Assistant was speaking. 
# 4. Experiment1.csv: This file is the data that was recorded in the following manner:
#    a. The phone was placed on a table
#    b. The phone was still
#    c. I pressed "Start" on the app
#    d. I tapped the microphone icon on Google Assitant to start talking into it, and asked it "How is the weather today?" (M)
#    e. Google Assistant started speaking
#    f. When Google Assistant started speaking, I tapped the screen to generate a peak that would be used to determine when Google Assistant started speaking (V.S)
#    g. Google Assistant stopped speaking
#    h. When Google Assistant stopped speaking, I tapped the screen to generate a peak that would be used to determine when Google Assistant stopped speaking (T)
#    i. I pressed "Stop" on the app
# 5. app-debug.apk: This is the app that was used to record the data. It is an Android app that was built using Android Studio. It is a simple app that records the accelerometer data and saves it to a file. It also has a button to start and stop the recording.
# 6. Labelled Peaks.png: This is the annotated screenshot of the visualization of the z-axis values from Exeperiment1.csv. The peaks are labbeled according to the key in Picture Key.txt
# 7. Picture Key.txt: This is the key for the peaks in Labelled Peaks.png
# 8. data_Exploration.ipynb: This is the Jupyter notebook that was used to explore the data and generate the plots in the folder.
