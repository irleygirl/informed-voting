# Informed Voting
*A non-partisan, issue-based ballot research assistant.*

This is a non-partisan tool that helps you research candidates in your local elections based on the issues you care about. It doesn't make every decision easier, but it does help you understand what the decision is.

## Why I made this
Instead of relying on other people's opinions, I wanted to vote based on candidates' track records, experience, and integrity. I used to vote based on party lines, but it has become clear that the established institutions are not working on behalf of the populace. Now I want to be informed and use my vote well.

## What it does
A voter will set which issues are most important to them and get relevant research about candidates' track records, experience, and integrity, and how each aligns with their interests.

## How to use
You don't need to know how to code. This takes about five steps.

1. **Copy the prompt.** Open [`voter-guide-system-prompt.md`](https://github.com/irleygirl/informed-voting/blob/main/voter-guide-system-prompt.md) in this repository and copy the whole file. (Click the "Copy raw file" button, the two overlapping squares at the top right of the text.)
2. **Create a Claude Project.** Go to [claude.ai](https://claude.ai), open **Projects**, and click **New project**. Give it any name you like.
3. **Paste the prompt.** In the project, choose **Set project instructions**, paste what you copied, and save. (Check [Claude's help center](https://support.claude.com/en/articles/9519177-how-can-i-create-and-manage-projects) for what your plan includes.)
4. **Start a chat inside the project.** Tell it your state or ZIP code and which issues matter most to you. If you aren't sure, say so and it will ask a few everyday questions to help.
5. **Go one race at a time.** After each race, reply "Next." If it asks for your street address or a photo of your sample ballot, that is only to find your exact districts, and you can skip it and move on.

**Tips**
- If you don't see a web search option, add "use web search" to your first message.
- Don't share more personal information than you're comfortable with.
- This has been tested in a Claude Project. It may work in other AI assistants that allow custom instructions and web search, but I haven't tested them.

## What it can't do
This tool will not tell you how to vote, nor can it guarantee accuracy since it depends on info that is publicly available.

## Disclaimers
- This tool isn't connected to any political party, campaign, candidate, or election office.
- Information can be out of date, so check the sources it links to.
- It's powered by AI, which can make mistakes.
- Anything you type goes to whichever AI service you use, under that service's privacy policy.
- It doesn't give legal advice or official election guidance. Check with your election office for deadlines, polling places, and rules.

## Report a mistake or suggest an improvement
You can report an issue (factual error, outdated info, or an idea) [here on Github](https://github.com/irleygirl/informed-voting/issues).

## Credits and license
Created by [irleygirl](https://github.com/irleygirl). Released under the MIT License, so you can use and adapt it freely. Please keep the license notice and link back to [irleygirl/informed-voting](https://github.com/irleygirl/informed-voting).
