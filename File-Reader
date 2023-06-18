file_name = input("Enter the name of the file: ")

try:
    with open(file_name, "r") as file:
        content = file.read()
        print(content)
except FileNotFoundError:
    print("File not found!")
