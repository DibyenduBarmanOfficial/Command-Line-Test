# Command-Line-Test
My Project in Linux Shell Scripting is to Implement a Login-based Online Test Platform using BASH Shell and Commands.

# Project Output :- 
Follow the link -> https://youtu.be/wNI8WeItYAo

# Project Brief :-
Command line test is a BASH shell-based tool that simulates login-based online testing scenarios. Initially, the user will be provided with a sign-in option where pre-defined users will be allowed to log in. Upon successful login, this tool will display questions for the user from the existing database. It will also handle error conditions like a time-out. This tool will also store answers provided by users for future verification.

These days there is a lot of online test platform which enables students to take tests online. They will typically have a user interface, backend question bank, and evaluation part. They will also support other features like predefined time per question, output reports, etc. The idea of this project is to simulate such an online test interface using Linux Shell Scripting and commands.

# Requirement Details :-

# 1. Provide a prompt for the user to sign-up and sign in

-> Sign In

-> Take Test

-> Sign up

-> Exit

# 2. Using sign-up users can register with a user-id and password

-> Ask for user-name. The user name should contain only alphanumeric symbols

-> Ask for new password. The password can contain any symbol in it. Accept at-least 8 characters

-> with at least a number and symbol

-> Ask the user to re-enter the password again for validation

# 3. Already registered users can sign in with their ID and password

-> The script should prompt for a user-name and password

-> The password should be like a shadow password

-> Show error in case passwords mismatches

# 4. Question bank

-> The user should provide a question bank file along with the script

-> If not search for a file named question_bank.txt as a default question bank.

# 5. Taking a test

-> Prompt the user with questions one by one randomly picked from the question_bank.

-> Prompt for questions with multiple choice

-> Every question should be timed, say 10 seconds

-> On timeout, the question should change with a fresh time

-> Every answer should be stored in currect_answer.txt file

-> The answer should be stored with attempt time (say if I answer within 5 seconds, then my answer with 5 seconds (attempt time) should be stored

-> If the user chooses this option, the script should show all the questions with all options, and the answer should be highlighted

-> All the user-entered answers have to be entered in the user_answer.txt

-> After an attempt successfully, all the question users will get the final score with correct & incorrect answers 
