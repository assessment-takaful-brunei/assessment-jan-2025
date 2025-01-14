# Assessment: Islamic Insurance Product Management System

## Objective
Evaluate your ability to:
1. Build a simple backend service that serves Islamic insurance product information.
2. Create a frontend that interacts with the backend to display products.
3. Demonstrate basic coding, problem-solving, and documentation skills in the context of Islamic insurance.

---

## Instructions for the Candidate

### **Submission Options**
1. **Preferred Submission Method:**  
   - Push your work to the **GitHub Classroom repository** provided for this assignment.
   - Submitting via GitHub Classroom will carry **extra points**.
2. **Alternative Submission Method:**  
   - If you are unable to use GitHub, email your solution as a `.zip` file to **assessment@takafulbrunei.com**.
   - Make sure your `.zip` file contains all code files and a `README.md` or `instructions.txt`.

---

### **Assessment Timing**

- This assessment is designed to be completed within **2 hours**.
- We will track your:
  - **Start time**: When you accept the assignment on GitHub Classroom.
  - **End time**: When you push your code to the repository.
- Ensure you do not exceed the allocated 2-hour time frame during your attempt.
- If you cannot complete all tasks within the time limit:
  - Submit what you have completed.

> **Tip:** Plan your time wisely and focus on completing key sections that you are most comfortable with first.

---


### **Important Note**
- While we encourage you to make your application functional, **it is not a strict requirement** for this assessment.
- Our primary focus will be on:
  - The quality, structure, and readability of your code.
  - Your problem-solving approach.
  - Your ability to document and explain your work.
 
---

### **GitHub Submission Instructions**

1. **Clone the Repository**
   - After accepting the assignment in GitHub Classroom, a personal repository will be created for you.
   - Clone the provided Classroom repository to your local machine using the following command:
     ```bash
     git clone <repository-link>
     ```
     Replace `<repository-link>` with the link to your personal repository for this assignment. This link will be available when you accept the assignment.

2. **Create Your Work**
   - Add your backend and frontend code to the repository.
   - Commit your changes frequently with meaningful commit messages.

3. **Push Your Work**
   - Use the following Git commands to push your changes:
     ```bash
     git add .
     git commit -m "Initial submission for assessment"
     git push origin main
     ```

4. **Verify Your Submission**
   - After pushing your changes, visit your GitHub Classroom repository to confirm that your files are uploaded correctly.

---

### **Alternative Documentation Option**

If you are unable to create a `README.md` file:
1. Include a plain text file named `instructions.txt` in your submission.
   - This file should contain instructions on how to run your backend and frontend.
2. Alternatively, email the instructions along with your code to **assessment@takafulbrunei.com**.

---

### **Be Creative!**
- You are encouraged to be as **creative as you want**.
- Feel free to add:
  - Unique **features** (e.g., additional filters, advanced functionality).
  - Enhanced **UI/UX designs** to improve the user experience.
- While creativity is optional, adding something unique may earn **bonus points**.

---

### **Email Submission Instructions**
1. **Prepare Your Files**
   - Zip all the necessary files (including your `README.md` or `instructions.txt`).
   - Ensure your zip file is named as follows:
     ```
     [YourFullName OR Assessment Code]_IslamicInsuranceAssessment.zip
     ```

2. **Email Your Submission**
   - Send the zip file to **assessment@takafulbrunei.com** with the subject:
     ```
     Submission: Takaful Assessment - [Your Full Name OR Assessment Code Given]
     ```

---

## Part 1: Backend Development

### Scenario
You are tasked with creating an API to manage Islamic insurance products (Takaful products). Each product must have the following information:
- **Product ID** (Unique identifier)
- **Product Name** (e.g., Takaful Plan A)
- **Type** (e.g., Family Takaful, General Takaful)
- **Premium** (Amount to be paid by the participant)
- **Coverage Type** (e.g., Health, Life, Property)
- **Shariah Compliance** (Boolean: `true` if the product is Shariah-compliant)

### Task
1. **Create a backend service** using your preferred framework (e.g., FastAPI, Flask, or Node.js) that exposes an endpoint `/products`.
   - The API should return a list of sample Islamic insurance products (hardcoded for simplicity).
   - Example of the data to be returned:
     ```json
     [
       {
         "id": 1,
         "name": "Takaful Plan A",
         "type": "Family Takaful",
         "premium": 100,
         "coverage_type": "Health",
         "shariah_compliant": true
       },
       {
         "id": 2,
         "name": "Takaful Plan B",
         "type": "General Takaful",
         "premium": 200,
         "coverage_type": "Property",
         "shariah_compliant": false
       }
     ]
     ```

2. **Optional Bonus**
   - Implement a filtering feature using query parameters:
     - Filter by `type` (e.g., `type=Family Takaful`).
     - Filter by `shariah_compliant` (e.g., `shariah_compliant=true`).

---

## Part 2: Frontend Development

### Scenario
You need to create a user interface to display the Islamic insurance products fetched from the backend.

### Task
1. **Build a frontend application** (HTML/JavaScript, React, or Vue) that:
   - Fetches data from the backend API `/products`.
   - Displays the product `name`, `premium`, `coverage_type`, and whether it's `shariah_compliant` (yes/no).
   - Display the products in a neat table or list format.

2. **Optional Bonus**
   - Add a simple **search box** that allows users to filter products by their `type` (e.g., "Family Takaful").

---

## Part 3: Documentation

### Task
1. Write a **README.md** or **instructions.txt** file:
   - Describe how to run the backend and frontend locally.
   - Explain the purpose of each field in the product data (e.g., `type`, `premium`, `shariah_compliant`).
   - Include instructions for setting up the development environment.

---

## Submission Checklist
Before submitting your work, make sure:
1. All your code is committed and pushed to the repository (if submitting via GitHub Classroom).
2. Your backend and frontend are functional.
3. Your `README.md` or `instructions.txt` file contains clear instructions on how to set up and run your project.
4. You’ve mentioned any creative additions or unique features in your submission.

---

## Evaluation Criteria

| **Skill**              | **Criteria**                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Backend Development     | Correctness and clarity of API implementation, data structure, and error handling. |
| Frontend Development    | Clean, user-friendly UI, correct data fetching, and filtering.             |
| Problem Solving         | Ability to implement filtering and querying based on requirements.        |
| Documentation           | Clarity of README or instructions.txt, completeness of setup instructions. |
| Creativity              | Unique features, UI/UX design enhancements, and extra functionality.      |
| Submission Method       | Pushing your work to GitHub Classroom earns extra points.                 |

---

## Islamic Insurance Context
- **Takaful** is an Islamic insurance system based on mutual cooperation where participants contribute money into a pool to help each other in times of need. 
- **Shariah compliance** ensures that the products are in line with Islamic law, avoiding investments in prohibited areas (e.g., alcohol, gambling).

Good luck!
