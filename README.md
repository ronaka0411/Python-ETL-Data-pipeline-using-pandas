# Python-ETL-Data-pipeline-using-pandas
This ETL takes csv files as input and after some processing or transformation on the original data, writes to the output file. Here I need email IDs of specific students who have not registered for the placement test for Fall 2018 semester.

#Input Confidentiality:
I cannot share the input files here, but can surely give the structure of it.
AA students csv file - Students who have commited to the college (large file) (Columns Student ID, Emails)
Registered or Tested Students csv file - Students who have given test for course placement or have registered for it or are exemted from it (Columns Student ID)
Online testers Pool csv file - Student IDs of students who are selected for online testing

#Ouptput
I want the list of email of students who have not given or registered for test and also are not selected for online testing. The AA list contains all the students with their emails.
