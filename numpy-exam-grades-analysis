import numpy as np

grades = np.array([[80, 65, 60],[45, 87, 65],[20, 18, 35]])

examNames = np.array(["Quiz", "Quiz2", "Quiz3"])

studentAverages = grades.mean(axis=1)
print("Student Averages:", studentAverages)

passedStudents = studentAverages[studentAverages >= 55]
failedStudents = studentAverages[studentAverages < 55]
print("Passed Students:", passedStudents)
print("Failed Students:", failedStudents)

bestStudentIndex = np.argmax(studentAverages)
worstStudentIndex = np.argmin(studentAverages)
print("Best Student Index:", bestStudentIndex)
print("Worst Student Index:", worstStudentIndex)

examGrades = grades.transpose()

examAverages = examGrades.mean(axis=1)
print("Exam Averages:", examAverages)

bestExamIndex = np.argmax(examAverages)
print("Best Exam:", examNames[bestExamIndex])
