# Rules for Cursor: AI Development Best Practices Guide

This repository provides a set of custom instructions ("User Rules") designed for AI-powered code editors like [Cursor](https://cursor.sh/) to promote software development best practices and improve the quality and consistency of AI-assisted coding.

These rules encourage a more structured, thoughtful, and robust development workflow when collaborating with an AI assistant. They aim to guide both the user and the AI towards better practices regarding project setup, planning, coding, testing, and version control.

## Why Use These Rules?

*   **Consistency:** Helps ensure the AI assistant follows a preferred workflow across different interactions.
*   **Best Practice Reinforcement:** Gently reminds you and guides the AI towards key practices like structuring projects, writing tests, committing often, and breaking down problems.
*   **Improved AI Interaction:** Provides clearer context and constraints to the AI, potentially leading to more relevant and useful suggestions.
*   **Reduced Rework:** Encourages planning and validation steps early, minimizing time spent on correcting AI-generated code that doesn't fit the overall structure or requirements.
*   **Active Learning:** Prompts you to review and understand generated code, fostering deeper comprehension rather than blind acceptance.

## Getting Started: How to Use These Rules in Cursor

1.  **Locate the Rules File:** Navigate to the `CUSTOM_INSTRUCTIONS.md` file in this repository.
2.  **Copy the Rules:** Select and copy the *entire* text content of the `CUSTOM_INSTRUCTIONS.md` file.
3.  **Open Cursor Settings:**
    *   In Cursor, go to `File` > `Settings` > `Cursor Settings`.
    *   Alternatively, use the shortcut `Ctrl+,` (Windows/Linux) or `Cmd+,` (macOS) and search for `Cursor Settings`.
4.  **Find the Rules Section:** Scroll down to the `Rules` section (or use the search within settings).
5.  **Paste the Instructions:** Paste the copied text into the text area under "User Rules". These preferences apply to all chats, composers, and Ctrl+K sessions within this workspace/project.
6.  **Save (Automatic):** Cursor typically saves settings automatically.
7.  **Start Working!** The AI assistant will now consider these rules during your interactions.

**Important Usage Notes:**

*   **@-Mentions:** Remember to use `@` to provide specific context like `@your_file.py`, `@your_test_file.py`, or `@AI_BEST_PRACTICES_GUIDE.md` when interacting with the AI. The rules encourage the AI to ask for this, but providing it proactively helps.
*   **Active Guidance:** While the rules prompt the AI to guide you, don't hesitate to explicitly ask, "Based on our practices, what should my next step be?"

## Repository Contents

*   **`CUSTOM_INSTRUCTIONS.md`:** Contains the raw text of the custom rules designed to be pasted directly into Cursor's settings. **(This is the main file you need!)**
*   **`AI_BEST_PRACTICES_GUIDE.md` (Recommended):** A consolidated markdown file containing the detailed explanations for each best practice that these rules are based on. Useful for understanding the *why* behind the rules. *(Alternatively, this could be a `lessons/` directory containing the individual `.md` files)*.
*   **`README.md`:** This file, providing an overview and instructions.
*   **`LICENSE`:** Specifies how you and others can use the contents of this repository.

## Underlying Best Practices

These rules are built upon core development principles including:

*   Starting with Project Structure
*   Brainstorming Before Coding
*   Breaking Down Complex Problems
*   Using Chat vs. Agent Tabs Appropriately
*   Customizing AI Behavior
*   Clear File Naming and Modularity
*   Always Writing Tests
*   Keeping Chats Focused
*   Understanding, Not Just Accepting, Code
*   Providing Context for New Technologies
*   Debugging Effectively (Getting Unstuck)
*   Committing Changes Often

Refer to `AI_BEST_PRACTICES_GUIDE.md` (or the `lessons/` directory) for detailed explanations of each.

## Contributing

Feedback and contributions are welcome! If you have suggestions for improving these rules or find issues, please feel free to:

*   Open an [Issue](https://github.com/SubliminalCoding/RULES_FOR_CURSOR_BEST_PRACTICES_GUIDE/issues) to discuss changes or report problems.
*   Submit a [Pull Request](https://github.com/SubliminalCoding/RULES_FOR_CURSOR_BEST_PRACTICES_GUIDE/pulls) with your proposed improvements.

## License

This project is licensed under the [MIT License](LICENSE) (or your chosen license - update this).
