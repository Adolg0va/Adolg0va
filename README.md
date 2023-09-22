class school:
    def __init__(self):
        self.Class = []

    def add_students(self, student):
        self.Class.append(Student)

    def print_students(self):
        for i in self.Class:
            print(f"Name: {i.name}, grade:{i.grade}")

    def find_student(self, fname):
        found= False
        for i in self.Class:
          if i.name == fname:
            found = True

        if not found:
            print("Student not found")




class Student:
    def __init__(self, name, grade):
        self.name = name
        self.grade = grade
