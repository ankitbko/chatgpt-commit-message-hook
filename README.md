# Use ChatGPT to write commit messages
Git hook that calls ChatGPT to generate commit message based on staged content.

## Installation
1. Copy the `prepare-commit-msg` file into your repository's `.git/hooks` folder.
1. Make sure python3 and requests library is installed.
1. Set environment variable `CHATGPT_API_KEY` to your [OpenAI API Key](https://platform.openai.com/account/api-keys).

# Usage
Run 'git commit' and an editor will open with generated commit message.

Run 'git commit -m Your_message' and ChatGPT will take your message into consideration while generating the commit message.