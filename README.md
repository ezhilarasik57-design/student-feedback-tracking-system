🎓 Student Feedback Tracking System – C Program

📌 Objective
To develop a Linked List-based Student Feedback Tracking System that manages and organizes student feedback data efficiently for a college or university.

📋 Features:
✅ Insert new student feedback details.
🔍 Search feedback by Feedback ID or Student Name.
❌ Delete outdated or incorrect feedback records.
🔁 Display feedback records in reverse order (for review sessions).
📋 Clone the feedback list (for separate analysis).
🏫 Generate course-wise feedback lists.

🗃️ Data Structure
Each feedback record is represented as a node in a singly linked list. Each node contains:
Feedback ID (int).
Student Name (string).
Course (string).
Year (int).
Feedback Content (string)
🛠️ Functionality Overview
Function	Description
insertFeedback()	Adds a new student feedback record
searchByID()	Searches for feedback by Feedback ID
searchByName()	Searches for feedback records by student name
deleteFeedback()	Deletes a feedback record by Feedback ID
displayReverse()	Displays feedback records in reverse order
cloneList()	Clones the entire feedback list
displayByCourse()	Displays feedback records filtered by course

💡 Sample Menu (CLI)

--- Student Feedback Tracking System ---
1. Insert Feedback Record
2. Search by Feedback ID
3. Search by Student Name
4. Delete Record by Feedback ID
5. Display Records in Reverse
6. Clone Feedback List
7. Display Course-wise Feedback
8. Exit

🧪 Compilation & Execution
🔧 Compile: gcc feedback_tracking.c -o feedback_tracking
▶️ Run: ./feedback_tracking
⚠️ Requires a C compiler (GCC recommended).

🧼 Memory Management
All dynamically allocated memory is freed before exit.
No memory leaks when deleting or cloning.

📝 Notes
Names and courses are stored using dynamically allocated strings.
Searching is case-insensitive for names.

👨‍💻 Author
Your Name
Your College/Institution
Year/Batch (optional)

If you want, I can also provide a version ready for a Word document or PDF with exact indentation and bullet alignment. Do you want me to do that?
