# Demo to compute reaction time for TCD
TCD stands for talker change detection. This repository shares a "toy" html script to compute and display the human reaction time to detect a change in talker in a speech utterance.

# Test it
1. You can open it straightaway by pasting the below URL in your browser.
Link: http://htmlpreview.github.io/?https://github.com/neerajww/rt_demo/blob/master/rt_speech.html

2. Or, you can download this repository and open rt_speech.html in your local system's web browser.
 

# About the script
To run open the rt_speech.html file.
It contains some simple HTML javascript-ing.
1. Obtains the list of audio files from: ./data/rtSample/file_list.txt to ob
2. Obtain the file name and the ground truth change instant for each file and stores these in file_set_test and files_set_key variables, respectively.
3. On pressing Load 1 and 2 are carried out.
4. On pressing Hit the hitpressed() function is called to obtain the reaction time.


# To know more on TCD
Great to have you interested in this! You can follow our research here:
https://github.com/neerajww/TCD_human_machine
