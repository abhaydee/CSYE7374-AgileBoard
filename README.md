-----CSYE 7374 FINAL PROJECT---------


GUIDELINES & Operating Instructions:

This project is implemented as a Command Line Interface (CLI) application, meaning all interactions occur via the console with text-based input and output. No graphical user interface (GUI) is provided.
The user interface is structured as a menu-driven system. Follow the provided options to proceed to the next step or navigate back.
A. Account Structure:

Role: An enumeration representing either a TeamLeader or TeamMember.
ID: Integer value that uniquely identifies an account.
Username: String that serves as the account identifier.
Password: String used for authentication.
DisplayName: A string that holds the name displayed for the user.
B. Task Structure:

Description: A string providing details about the task.
Status: An enumeration with possible values: TODO, DOING, DONE.
ID: Integer value that uniquely identifies a task.
AssignedMember: The type of this field depends on your implementation.
C. Capabilities of a Team Leader:

Create new tasks.
Update existing tasks (including modifying the description and reassigning the member responsible).
View all tasks.
Delete tasks.
D. Capabilities of a Team Member:

View tasks specifically assigned to them.
Update the status of their tasks.
Edge Cases Considered:

If a team member already has two or more tasks marked as DOING, they cannot be assigned additional tasks.
Tasks marked as DOING cannot be deleted or reassigned to another member.
Tasks marked as DONE cannot be reassigned to a different member.