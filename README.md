### Backend Assignment v1.0


#### Create a simple CRUD Blog web application.

- For backend MUST use: Yii v1.1 and MySQL
- For frontend use native HTML, CSS, JavaScript, Bootstrap/Tailwind or any preferred frontend framework(e.g. React.js)


**Summary:**
This Yii application will securely handle user authentication, including user sign in, sign up and verify user email(not need to send real emails, just generate a token and use it). 

**Task Requirements:**

- **Authentication:** Secure user authentication processes, such as signin, signup and the verify user email logic.
- **Ajax Validation:** Real-time email validation during registration to ensure the email is not already in use.
- **CRUD Operations:** Verified Users can perform Create, Read, Update, and Delete (CRUD) operations on blog posts, associated with their unique user ID. (non-verified users won't be able to CRUD blog posts)
- **Form Validation:** Use multiple fields and implement validation rules.
- **Blog Post Visibility:** Users can mark their posts as public or private.
- **Likes:** Users can like blog posts.
- **Search and Filter:** Users can search for blog posts by title or description and filter results by date and author.

- **Bonus points**: Create a new branch from your main base branch and:
  - Implement a new feature in this new branch which is "Create new public webpage that shows in real-time(without refresh page) a list of blog posts that have at least 1 comment and their authors have at least 2 blogs" (optimize the SQL query)
  - Create a PR from this new branch and merge it into -> your main base branch
  - Write a small document(e.g. readme file) about how to setup and run your code


**Task Submission:**
Create a private repo on GitHub and share the repo with khaledalam.net@gmail.com
