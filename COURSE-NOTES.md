# Course Notes

This note includes the instructions on how to install Claude Code, and the links to the coding examples and prompts used in the lessons.

## Note

- To mark this reading item as complete, make sure to scroll down to the end and click on "Mark as Complete".
- There's a second reading item at the end of this course. To get 100% course completion, make sure to also mark it as complete.

## Claude Code Installation

To follow along with the lessons, here's how you can install Claude Code.

Install Node.js, then run:

```bash
npm install -g @anthropic-ai/claude-code
```

For more installation guides, you can find them in the [Claude Code Installation Guide](https://docs.anthropic.com/claude/docs/claude-code-installation). If you're using Windows, make sure to check the [Windows Setup Guide](https://docs.anthropic.com/claude/docs/claude-code-windows-setup).

Once you have Claude Code installed, you can:

- launch it from your terminal: navigate to your project folder & then type `claude`
- launch it from the terminal integrated within VS Code by typing `claude`, the extension will auto-install.
- If you run into issues, ensure that `code` command is available. If not installed, use Cmd+Shift+P (Mac) or Ctrl+Shift+P (Windows/Linux) and search for "Shell Command: Install 'code' command in PATH"

For more info, check [Claude Code IDE Integrations](https://docs.anthropic.com/claude/docs/claude-code-ide-integrations).

## Links to Course Codebase Examples

Here are the links to the coding examples covered in the lessons:

### Codebase for the RAG chatbot (Lessons 2-6)

- [Here's the repo of the starting codebase used in lesson 2](https://github.com/deeplearning-ai/claude-code-rag-chatbot-starter).
- Lessons 3-6 add features to the starting codebase.
- [Here's the state of the codebase after lesson 5](https://github.com/deeplearning-ai/claude-code-rag-chatbot-final).
- Feel free to fork the starting codebase and follow the lessons' activities.

### E-commerce data analysis (Lesson 7)

- [Here are the lesson's files](https://github.com/deeplearning-ai/claude-code-ecommerce-analysis).
- It includes the data, the starting and refactored notebooks, and the dashboard file.
- Feel free to fork this repo, and try lesson 7 tasks using the starting notebook and the data folder.

### Figma design mockup (Lesson 8)

- [Here's the link to the Figma mockup design](https://www.figma.com/file/Hl6GlTWYOUkiUwHQKAJRXv/Claude-Code-Course-Mockup?type=design&node-id=0%3A1&mode=design&t=JIwJHZxNLxpJ4Yvg-1) (which you can open with Figma Desktop App).
- In lesson 8, you will build a Next.js app based on this mockup.
- [Here's the link to the repo of the app we got during filming](https://github.com/deeplearning-ai/claude-code-nextjs-app).

## Prompts and Summaries of Lessons

You can find the prompts used in each lesson and a summary of Claude Code features in the optional reading item at the end of the course (Prompts & Summaries of Lessons). You can also find them in [this repo](https://github.com/deeplearning-ai/claude-code-course-prompts).

## Claude Code Cost

If you'd like to install Claude Code to try the lessons:

- you can use the Pro or Max subscription. The pro subscription is enough for the lessons' activities.
- Or, you can be billed based on API usage. For a given session, you can see the cost using the `/cost` command.
