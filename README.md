# Loop3
# Problem 3: Average Exam Scores

# Initialize variables
student_count = 0
total_students = 0

# Prompt user to continue
user_input = input("Do you want to continue? (Yes/No): ")

# Use a while loop based on user input
while user_input.lower() == "yes":
    # Prompt user for data
    last_name = input("Enter last name: ")
    exam1 = float(input("Enter Exam 1 score: "))
    exam2 = float(input("Enter Exam 2 score: "))
    
    # Calculate average
    average_score = (exam1 + exam2) / 2
    
    # Display results
    print(f"{last_name}'s Average Exam Score: {average_score:.2f}")
    
    # Update counters
    student_count += 1
    total_students += 1
    
    # Prompt user to continue
    user_input = input("Do you want to continue? (Yes/No): ")

# Display total number of students who entered data
print(f"\nTotal Number of Students: {student_count}")
