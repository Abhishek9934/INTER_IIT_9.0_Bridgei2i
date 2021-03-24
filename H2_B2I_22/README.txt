--We are assuming that you guys will insert actual headline headings data , and actual theme and actual sentiment corresponding to each brand as in the test dataset the actual predictions were not given.


Folder Structure:

Main.ipynb -- this is code which we have implemented , please run this , it produces to output files - output_1.csv and output_2.csv

evaluation.csv -- this was provide by you only for evaluation purpose


how to run the code

-for training purpose
	firstly you have to upload two files in google, one containing tweets.
	other containing articles
	Further, we have to change the file path
	tweet_path --update the location of training tweets here
	article_path --update the location of training articles here.

-for testing purpose 
	we have to insert a testing file.
	Then update the file path
	in the variable test_data_path

-after that, run the whole code simultaneously
-have to wait for around 20-30 mins


--final output
	will get two downloaded files.
	1. output_1.csv-- This file contain headlines
	2. output_2.csv-- This file will contain brand sentiment analysis
	output_1.csv---> headlines predicted, mobile tag
	output_2.csv---> mobile tag predicted tag actual tag and 
	sentiment analysis for all the possible mobile brands
