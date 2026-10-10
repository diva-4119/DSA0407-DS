
import numpy as np

student_scores = np.array([
    [85, 78, 90, 75],
    [80, 88, 85, 70],
    [90, 92, 88, 80],
    [75, 85, 82, 78]
])

subjects = ["Math", "Science", "English", "History"]

# Calculate average marks for each subject
averages = np.mean(student_scores, axis=0)

# Find the subject with the highest average
highest_index = np.argmax(averages)

print("Average marks for each subject:")
for i in range(4):
    print(subjects[i], ":", averages[i])

print("Subject with highest average:", subjects[highest_index])
print("Highest average:", averages[highest_index])
