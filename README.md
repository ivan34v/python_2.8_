grades = [[5, 3, 3, 5, 4], [2, 2, 2, 3], [4, 5, 5, 2], [4, 4, 3], [5, 5, 5, 4, 5]]
students = {'Johnny', 'Bilbo', 'Steve', 'Khendrik', 'Aaron'}
sorted_students = sorted(students)
student_averages = {name: sum(grades[i]) / len(grades[i]) for i, name in enumerate(sorted_students)}
for student, average in student_averages.items():
    print(f"{student}: {average:.2f}")
