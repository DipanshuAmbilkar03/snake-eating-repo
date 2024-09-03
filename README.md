# 🐍 Snake Eating Animation Setup 🐍

![Screenshot 2024-09-03 190838](https://github.com/user-attachments/assets/79d1203d-bda7-40c3-85a2-d62fe0584b1d)

Follow these steps to set up the snake eating animation on your GitHub profile:

1. **Add the `snake.yml` file:**
   - Create a file named `snake.yml` in the `.github/workflows/` directory of your repository.
   - Add the provided content to your `snake.yml` file.
   - There is no need to replace `username`.
     
      ![first](https://github.com/user-attachments/assets/c79101f9-e799-47e5-8efc-926d4cdddf6a)

2. **Before running the workflow:**
   - Go to your repository's settings and in the Actions/General give **Read and write** permissions to the workflow.
   - **Require approval for all outside collaborators** to ensure security (Not mandatory).

     ![Screenshot 2024-09-03 180434](https://github.com/user-attachments/assets/507444ba-d6a9-47dc-b317-fca5f1ef3daa)

3. **Run the workflow:**
   - Navigate to the **Actions** tab in your GitHub repository.
   - Select the **Generate Snake** action and click **Run Workflow**.
     
     ![Screenshot 2024-09-03 180241](https://github.com/user-attachments/assets/5fc0a686-0c61-42a9-868b-004259c1f248)

   - Once the workflow is approved and executed, check the `output` branch.

5. **Check the output branch:**
   - Ensure that the following files are present in the `output` branch:
     - `github-contribution-grid-snake-dark.svg`
     - `github-contribution-grid-snake.gif`
     - `github-contribution-grid-snake.svg`
    
       ![Screenshot 2024-09-03 180511](https://github.com/user-attachments/assets/9bd12f04-21a3-4a3a-99fa-4e60237bcac6)

6. **Update your README:**
   - Add the following tag to your README file to display the snake animation:

     ```markdown
     ![GitHub Snake](https://raw.githubusercontent.com/github-username/github-username/output/github-contribution-grid-snake.svg)
     ```

   - Make sure to replace `github-username` with your GitHub username.

---

By following these steps, you'll have a cool snake animation eating your contributions on your GitHub profile!
