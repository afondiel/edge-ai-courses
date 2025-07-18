# Contributing to Edge AI Courses

We wholeheartedly welcome your contributions to make this curated collection of Edge AI courses and resources even more comprehensive and valuable! Your insights help empower engineers and practitioners worldwide.

Please take a moment to review this guide to ensure your contributions align with the repository's goals and structure.

## Code of Conduct

We expect all contributors to adhere to a respectful and inclusive code of conduct. Please treat others with courtesy and professionalism.

## How to Contribute

There are several ways you can contribute to this project:

### 1. Reporting Issues or Suggestions

If you find a missing course, an outdated link, an incorrect description, or have a suggestion for improving the repository (e.g., new categories, better structure), please open an [issue](https://github.com/afondiel/edge-ai-courses/issues).

When opening an issue, please:
* **Be clear and concise:** Describe the problem or suggestion in detail.
* **Provide relevant links:** If reporting an issue with a course, include its URL.
* **Suggest solutions (optional):** If you have an idea for a fix or improvement, feel free to share it.

### 2. Submitting New Courses or Updates (Pull Requests)

The core of this repository is the `Courses & Resources` table in the `README.md`. If you want to add a new course or update existing information, please follow these steps:

#### **Fork the Repository**
1.  Click the "Fork" button at the top right of this repository.

#### **Clone Your Fork**
2.  Clone your forked repository to your local machine:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/edge-ai-courses.git](https://github.com/YOUR_USERNAME/edge-ai-courses.git)
    cd edge-ai-courses
    ```

#### **Create a New Branch**
3.  Create a new branch for your changes:
    ```bash
    git checkout -b feature/add-new-course-name
    # OR
    git checkout -b fix/update-course-link
    ```

#### **Edit `README.md`**
4.  Open the `README.md` file in your preferred text editor.
5.  **Locate the `Courses & Resources` table.**
6.  **Adding a New Course:**
    * Add a new row to the table.
    * **Maintain the sorting order by `Level` (Beginner, Intermediate, Advanced, Varied).** Please insert your new course in the correct alphabetical position within its difficulty level.
    * **Course:** Provide the full course name.
    * **Description:** Keep it **concise** (aim for one short sentence) summarizing the main focus.
    * **Level:** Choose from `Beginner`, `Intermediate`, `Advanced`, or `Varied`.
    * **Price:** Use clear indicators like:
        * `**Free**`
        * `Paid (cert)`
        * `Paid (subscription)`
        * `Course specific, part of [University] curriculum`
        * `(Nanodegree price)`
        * `Varied (often discounted)`
    * **Organization:** Provide the name of the issuing organization/platform. Embed the link directly into the organization name: `[Organization Name](https://example.com/course-link)`.
    * **Example Row Structure:**
        ```markdown
        | New Course Title | A very concise description of what the course covers. | Beginner | **Free** | [New Org Name](https://example.com/new-course) |
        ```
7.  **Updating an Existing Course:**
    * Navigate to the specific row you want to update.
    * Make your changes, ensuring they follow the established formatting (concise description, price notation, linked organization).

#### **Commit Your Changes**
8.  Stage your changes:
    ```bash
    git add README.md
    ```
9.  Commit your changes with a clear and descriptive commit message. A good commit message explains *what* you did and *why*.
    ```bash
    git commit -m "feat: Add new [Course Name] by [Organization]"
    # OR
    git commit -m "fix: Update link for [Course Name]"
    ```
    (We follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for commit messages.)

#### **Push to Your Fork**
10. Push your changes to your forked repository:
    ```bash
    git push origin feature/add-new-course-name
    ```

#### **Create a Pull Request**
11. Go to your forked repository on GitHub. You should see a prompt to create a Pull Request.
12. Fill out the Pull Request template:
    * **Title:** Summarize your changes (e.g., `feat: Add new 'Introduction to Edge AI' course`).
    * **Description:** Provide more details about your changes, why they are valuable, and reference any related issues.

### 3. Reviewing Pull Requests

You can also contribute by reviewing existing [pull requests](https://github.com/afondiel/edge-ai-courses/pulls). Your feedback helps improve the quality of contributions.

## License

By contributing to this repository, you agree that your contributions will be licensed under the project's [MIT License](LICENSE).

---

Thank you for helping to build this valuable resource for the Edge AI community!