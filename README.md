# About me

Senior Software Developer with experience building hybrid web applications used by millions of Canadians.

In my spare time I like to stay active, learn new things, and obsess over the details 🏃‍♂️📚🪴🥐

# Whatcha doing now?
📖 Reading fantasy<br>
🧶 Crotchet<br>
🏃‍♂️ ~~Beginner~~ Novice runner<br>
⚙️ Minor tinkering<br>


# Simplifi OFX Importer
🔭 I was recently inspired to create a [OFX to Simplify CSV Converter](https://github.com/pointdexter3/simplifi-csv-formatter) for builk importing transactions into the Simplifi budgeting app.
- Applies to Simplifi Manual Accounts, for those that do not wish to share their FI credentials with 3rd parties. Interim solution until Canada's Open Banking is widely adopted.
- V1: Initial implementation was a trial of using chatgpt to help me work through things I was less familiar with (more advanced bash scripting, csv parsing / modification). to limited success (my expereince was that if the problem was non-trivial I would hit a wall of lies at maybe 70% of the solution)
- V2: Rewritten to use nodejs/typescript and parse FI's exported OFX standard files. OFX over the initial implementations CSV as the latter was wildly inconsistent between differents FI's and accounts.

# Bulk import TODOIST project template files [(sync api V9)](https://developer.todoist.com/sync/v9/#overview).

1. Creates a parent project.
2. Asks for project CSV template files.
3. Creates new projects based on the file names. 
4. Makes the new projects sub-projects of the parent project
5. Imports the tasks from the template CSV’s for each corresponding project


***Great for vacation checklists*** 🥰

## Main shortcut
> https://www.icloud.com/shortcuts/6f21ced9d61f4c1faf516f30b9160ea8

## Relies on the following utilities (extracted to reduce noise, haven’t looked at how to make dependencies shareable with shortcuts):
> [Generate uuid](https://www.icloud.com/shortcuts/c58fe8d7739b47f8b3fa8cd5d9744eae)<br>
> [Generate temp id](https://www.icloud.com/shortcuts/c3095a21e16544ae9e039dd149f7f23c)

<sub> if templates are in iCloud, make sure they are downloaded</sub>

# 🏗️ Under construction...


<!--
**pointdexter3/pointdexter3** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
