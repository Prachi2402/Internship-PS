# Internship-PS

# Part 1

- Assume that the average length of each word is much smaller than the total number of words to be processed.
- Also assume that all words in the input will only consist of lowercase English alphabets from a-z and no other characters.

Note:
1. The words in each line of the output are anagrams of each other. Two words are anagrams if they have the same alphabets and the same frequency of the alphabets but their ordering is different.
2. The order of the words within each line of the output does not matter. The only thing that matters is that the words are correctly grouped line by line.
3. The relative order of the lines of the output also does not matter.
4. Any words that are not anagrams of any other words in the input list must occupy an independent line in the output.

Write a python program which takes the list of words as an input and prints the output to the screen.

# Part 2

Write a Python program that uses OpenCV to:
1. open an input video file (might have any frame rate)
2. extracts each frame and convert it into gray scale
3. add the text “OpenCV” in the top-right corner of each frame.
4. generate an output video file with the modified frames such that the frame rate of the output video file must always be in the 15-25 fps range.
  a. If the input file has a frame rate less than 25, then the output can have the same frame rate as the input.
  b. If the input file has a higher frame rate, then the frames must be sampled such that the output video must have a frame rate between 15 and 25. The duration of the video should not change however (should be same as input)
  
Implement the above in the form of a function which should accept a file path to an mp4 video file as an input and must store the output file in the respective file path.

# Part 3

Write a Python program using PyTesseract and OpenCV to read an input image containing text, and do the following:
1. Draw bounding boxes around every word
2. Annotate every bounding box with the detected text within the box

The output should look include a bounding box around every other word in the image. 

Write the program in the form of a function which should accept a file path to an image file as an input and must display the output on the screen.

