# 🐍 Snake Eating Animation Setup 🐍

Follow these steps to set up the snake eating animation on your GitHub profile:

1. **Add the `snake.yml` file:**
   - Create a file named `snake.yml` in the `.github/workflows/` directory of your repository.
   - Add the provided content to your `snake.yml` file.
   - There is no need to replace `username`.

2. **Before running the workflow:**
   - Go to your repository's settings and give **Read and write** permissions to the workflow.
   - **Require approval for all outside collaborators** to ensure security (Not mandatory).

3. **Run the workflow:**
   - Navigate to the **Actions** tab in your GitHub repository.
   - Select the **Generate Snake** action and click **Run Workflow**.
   - Once the workflow is approved and executed, check the `output` branch.

4. **Check the output branch:**
   - Ensure that the following files are present in the `output` branch:
     - `github-contribution-grid-snake-dark.svg`
     - `github-contribution-grid-snake.gif`
     - `github-contribution-grid-snake.svg`

5. **Update your README:**
   - Add the following tag to your README file to display the snake animation:

     ```markdown
     ![GitHub Snake](https://raw.githubusercontent.com/github-username/github-username/output/github-contribution-grid-snake.svg)
     ```

   - Make sure to replace `github-username` with your GitHub username.

---

By following these steps, you'll have a cool snake animation eating your contributions on your GitHub profile!
