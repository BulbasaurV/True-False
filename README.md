# True-False
The history teacher at your school needs help in grading a True/False test. The students’ IDs and test answers are stored in a file. The first entry in the file contains answers to the test in the form:
TFFTFFTTTTFFTFTFTFTT
Every other entry in the file is the student ID, followed by a blank, followed by the student’s responses. For example, the entry:
ABC54301 TFTFTFTT TFTFTFFTTFT
indicates that the student ID is ABC54301 and the answer to question 1 is True, the answer to question 2 is False, and so on. This student did not answer question 9. The test has 20 questions, and the class has more than 150 students. Each correct answer is awarded two points, each wrong answer gets one point deducted, and no answer gets zero points.

Write a program that processes the test data. The output should be the student’s ID, followed by the answers, followed by the test score, followed by the test grade. Assume the following grade scale:
90%–100%, A; 80%–89.99%, B; 70%–79.99%, C; 60%–69.99%, D; and 0%–59.99%, F
