# LeetCode-Profile-Finder
Finds anyone's LeetCode profile to check their Solved questions

LeetCode Profile Finder is a web application where users can enter a LeetCode profile ID to retrieve and visualize their question-solving statistics. The app fetches data using the LeetCode GraphQL API and displays the number of solved easy, medium, and hard questions in a pie chart format. Additionally, it provides a breakdown of overall submissions in a user-friendly card layout.

Working Flow:
Username Validation:

Ensures the username is valid using a regex.
API Call:

Uses a proxy and sends a GraphQL request to fetch user data.
Updating the Pie Chart:

Solved and total questions for each difficulty are passed to updateProgress() to reflect the data in the circular progress bars.
Displaying Submission Stats:

Generates cards for submission counts (overall and by difficulty level) and dynamically updates the DOM with the results.

Output for Better Understanding:

![image](https://github.com/user-attachments/assets/0cb36206-f96c-436b-bf56-068ae7ccd624)

![image](https://github.com/user-attachments/assets/b917f209-5589-45e0-87a7-385d391e9c05)


