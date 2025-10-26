🎓 Student Feedback Tracking System – C Program 📌 Objective
To develop a Linked List-based Student Feedback Tracking System that manages and organizes student feedback data efficiently for a college or university .
📋 Features
✅ Insert new student feedback details
🔍 Search feedback by Feedback ID or Student Name
❌ Delete outdated or incorrect feedback records
🔁 Display feedback records in reverse order (for review sessions)
📋 Clone the feedback list (for separate analysis)
🏫 Generate course-wise feedback lists
🗃️ Data Structure
Each feedback record is represented as a node in a singly linked list. Each node contains:
Feedback ID (int)
Student Name (string)
Course (string)
Year (int)
Feedback Content (string)
🛠️ Functionality Overview
Function Description
insertFeedback()      Adds a new student feedback record
searchByID()         Searches for feedback by Feedback ID
searchByName()       Searches for feedback records by student name
deleteFeedback()     Deletes a feedback record by Feedback ID
displayReverse()     Displays feedback records in reverse order
cloneList()          Clones the entire feedback list
displayByCourse()    Displays feedback records filtered by course
💡 Sample Menu (CLI)
--- Student Feedback Tracking System ---Insert Feedback Record
Search by Feedback ID
Search by Student Name
Delete Record by Feedback ID
Display Records in Reverse
Clone Feedback List
Display Course-wise Feedback
Exit

Enter your choice:
🧪 Compilation & Execution
🔧 Compile: gcc feedback_tracking.c -o feedback_tracking
▶️ Run: ./feedback_tracking
⚠️ Requires a C compiler (GCC recommended).
🧼 Memory ManagementAll dynamically allocated memory is freed before exit.No memory leaks when deleting or cloning.
📝 NotesNames and courses are stored using dynamically allocated strings.Searching is case-insensitive for names.
👨‍💻 AuthorYour Name
Your College/Institution
Year/Batch (optional)
