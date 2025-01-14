# Assessment: Takaful Product Management System

## Objective
Evaluate your ability to:
1. Build a simple backend service that serves Takaful product information.
2. Create a frontend that interacts with the backend to display products.
3. Demonstrate creativity by adding extra features and fields, showcasing problem-solving, documentation, and coding skills.

---

## Instructions for the Candidate

### **Submission Options**
1. **Preferred Submission Method:**  
   - Push your work to the **GitHub Classroom repository** provided for this assignment.
   - Submitting via GitHub Classroom will carry **extra points**.
2. **Alternative Submission Method:**  
   - If you are unable to use GitHub, email your solution as a `.zip` file to **assessment@takafulbrunei.com**.
   - Make sure your `.zip` file contains all code files and a `README.md`,`instructions.docx` or `instructions.txt`.

---

### **Assessment Timing**

- This assessment is designed to be completed within **2 hours**.
- We will track your:
  - **Start time**: When you accept the assignment on GitHub Classroom.
  - **End time**: When you push your code to the repository.
- Ensure you do not exceed the allocated 2-hour time frame during your attempt.
- If you cannot complete all tasks within the time limit:
  - Submit what you have completed.

> **Tip:** Prioritize completing the basics first, then focus on creativity and additional features.

---

### **Important Note**
- If you are not familiar with either API development or frontend development:
  - Start with the part you are **most comfortable with**. This is a **crucial step** to ensure you complete the core functionality first.
  - **If you prefer backend development**, focus on creating more detailed or complex endpoints.
  - **If you prefer frontend development**, use mock data to simulate API responses and focus on building a user-friendly interface.
- **Structuring your repository into two separate project folders** (`/frontend` and `/backend`) is a plus and demonstrates good organizational practices.
- Our primary focus will be on:
  - The quality, structure, and readability of your code.
  - Your problem-solving approach.
  - Your ability to document and explain your work.
- You are allowed to **overwrite this README.md file** with your own documentation. Ensure it includes:
  - Instructions for running your backend and frontend.
  - An explanation of any extra features or fields you’ve added.

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

### **Be Creative!**
- Once you have the basic functionality in place, focus on **creativity**:
  - Add extra fields to your models (e.g., `Policy Duration`, `Customer Feedback`, `Plan Benefits`).
  - Include **unique features** like:
    - Additional filtering or sorting options.
    - A visually enhanced user interface.
    - Interactive components like modals, graphs, or animations.
  - Showcase your skills and ideas by going beyond the requirements.
- Creativity and innovation will earn **bonus points**.

---

## Part 1: Backend Development

### Scenario
You are tasked with creating an API to manage Takaful products (Takaful products). Each product must have the following basic information:
- **Product ID** (Unique identifier)
- **Product Name** (e.g., Takaful Plan A)
- **Type** (e.g., Family Takaful, General Takaful)
- **Premium** (Amount to be paid by the participant)

---
## Example of an Insurance Product

To help you better understand insurance products, here is an example:

| **Field**               | **Description**                                 | **Example Value**            |
|-------------------------|-------------------------------------------------|------------------------------|
| **Product ID**          | Unique identifier for the product.              | `1`                          |
| **Product Name**        | Name of the insurance product.                  | `Family Health Protection`   |
| **Type**                | The type of insurance (e.g., Family, General).  | `Family Takaful`             |
| **Premium**             | Monthly or yearly payment for the product.      | `$200/month`                 |
| **Coverage Type**       | The type of coverage provided by the plan.      | `Health`                     |
| **Policy Duration**     | Duration of the insurance policy.               | `1 Year`                     |
| **Shariah Compliance**  | Indicates if the product follows Islamic laws.  | `Yes`                        |
| **Additional Benefits** | Extra features included in the plan:            |                              |
|                         | - Hospitalization Coverage: `$50,000`          |                              |
|                         | - Maternity Coverage: `$10,000`                |                              |
|                         | - Outpatient Visits: `10 visits/year`          |                              |

You can use this table as a reference when building your backend or displaying data on your frontend.
Feel free to extend the fields and values as part of your solution.

---

### Task
1. **Create a backend service** using your preferred framework (e.g., FastAPI, Flask, or Node.js) that exposes an endpoint `/products`.
   - The API should return a list of sample products.
   - Example of the data to be returned:
     ```json
     [
       {
         "id": 1,
         "name": "Family Health Protection",
         "type": "Family Takaful",
         "premium": 100
       },
       {
         "id": 2,
         "name": "Motor Takaful",
         "type": "General Takaful",
         "premium": 200
       }
     ]
     ```

2. **Optional Bonus**
   - Add additional fields to the product model, such as:
     - `Policy Duration` (e.g., "1 Year").
     - `Coverage Type` (e.g., "Health", "Property").
     - `Shariah Compliance` (e.g., `true` or `false`).
   - Implement a filtering feature using query parameters (e.g., filter by `type` or `premium`).

---

## Part 2: Frontend Development

### Scenario
You need to create a user interface to display the Takaful products fetched from the backend.

### Task
1. **Build a frontend application** (HTML/JavaScript, React, or Vue) that:
   - Fetches data from the backend API `/products`.
   - Displays the product `name`, `type`, and `premium` in a neat table or list format.

2. **Optional Bonus**
   - Add extra features like:
     - Filters for `type` or `premium`.
     - A **search box** for product names.
     - UI elements such as modals, dropdowns, or charts.

3. **Frontend Focus Alternative**
   - If you prefer focusing on the frontend, you may use **mock data** instead of an actual API and build the UI around it.

---

## Part 3: Documentation

### Task
1. Write a **README.md** or **instructions.txt** file:
   - If you overwrite this `README.md`, ensure it includes:
     - Instructions for running the backend and frontend locally.
     - An explanation of any extra features or fields you’ve added.

---

## Submission Checklist
Before submitting your work, make sure:
1. All your code is committed and pushed to the repository (if submitting via GitHub Classroom).
2. Your backend and frontend are functional.
3. Your `README.md`,`instructions.docx` or `instructions.txt` file contains clear instructions on how to set up and run your project.
4. You’ve highlighted any creative additions or extra features.

---

## Evaluation Criteria

| **Skill**              | **Criteria**                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Backend Development     | Simplicity and clarity of API implementation, data structure, and error handling. |
| Frontend Development    | Clean, user-friendly UI and additional interactivity.                      |
| Problem Solving         | Ability to expand on basic requirements and implement creative features.   |
| Documentation           | Clarity of README or instructions.txt, completeness of setup instructions. |
| Organization            | Clear separation of frontend and backend into project folders.            |
| Creativity              | Unique features, model enhancements, and innovative UI/UX design.         |
| Submission Method       | Pushing your work to GitHub Classroom earns extra points.                 |

---

## Takaful Context
- **Takaful** is an Islamic insurance system based on mutual cooperation where participants contribute money into a pool to help each other in times of need. 
- **Shariah compliance** ensures that the products are in line with Islamic law, avoiding investments in prohibited areas (e.g., alcohol, gambling).

Good luck!
