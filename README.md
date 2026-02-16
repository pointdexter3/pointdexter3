# About me

Senior/Lead Software Developer with experience building hybrid web applications used by millions of Canadians.

In my spare time I like to stay active, learn new things, and obsess over the details 🏃‍♂️📚🪴🥐

# Whatcha doing now?
📖 Reading fantasy<br>
🎲 Boardgames<br>
🏃‍♂️ Prioritizing Health / Running / Fitness with Whoop<br>
⚙️ Minor tinkering<br>

<br />

# Simplifi OFX Importer
🔭 I was recently inspired to create a [OFX to Simplify CSV Converter](https://github.com/pointdexter3/simplifi-csv-formatter) for builk importing transactions into the Simplifi budgeting app.
- Applies to Simplifi Manual Accounts, for those that do not wish to share their FI credentials with 3rd parties. Interim solution until Canada's Open Banking is widely adopted.
- V1: Initial implementation was my first attempt of using chatgpt to work through things I was less familiar with (more advanced bash scripting, csv parsing / modification). At the time I found if the problem was non-trivial I would hit a wall of gaslighting at maybe 70% of the solution which burned a good deal of time.  
- V2: Rewritten to use nodejs/typescript and parse FI's exported OFX standard files. OFX over the initial implementations CSV as the latter was wildly inconsistent between differents FI's and accounts.

  
<br />

# DEPRECIATED ~~Bulk import TODOIST project template files [(sync api V9)](https://developer.todoist.com/sync/v9/#overview).~~

1. Creates a parent project.
2. Asks for project CSV template files.
3. Creates new projects based on the file names. 
4. Makes the new projects sub-projects of the parent project
5. Imports the tasks from the template CSV’s for each corresponding project


***Great for vacation checklists*** 🥰

## Main shortcut
> UPDATE_LINK

## Relies on the following utilities (extracted to reduce noise, haven’t looked at how to make dependencies shareable with shortcuts):
> [Generate uuid]()UPDATE_LINK<br>
> [Generate temp id]()UPDATE_LINK

<sub> if templates are in iCloud, make sure they are downloaded</sub>


<br />

<br />

<br />

<br />

# iOS Shortcuts

<br />

<br />

<br />


# TODOIST natural language actions
- Problem: Todoist iOS shortcuts do not allow for natural language for dates/times
- Opportunity: minimize the interaction as much as possible when creating todoist tasks in iOS.
  - I want to activate siri using language I find more natural
  - I want to pre-configure due dates & projects
  - I want to be able to avoid accidental natural language interpretation (pre-configurations are appended to the end of the text sent to Todoist API)


| activate siri → voice command | user dictated text        | text sent to API             | Todoist task                        |
|------------------------------|----------------------------|------------------------------|-------------------------------------|
|  |  |  |
| task                         | empty the litterbox tomorrow | empty the litterbox tomorrow       | empty the litterbox (due date: tomorrow)                |
| today                        | empty the litterbox tomorrow | empty the litterbox tomorrow today | empty the litterbox tomorrow (due date: today)          |
| add to grocery list          | apples saturday              | apples saturday #Grocery\ List     | apples (project "Grocery List", due date: this Saturday) |
| today                        | empty the litterbox          | empty the litterbox today          | empty the litterbox (due date: today)                   |

- [iOS shortcut - task](https://github.com/pointdexter3/iOS-shortcuts/blob/main/todoist/api_v1/Todoist-Task.shortcut)
- [iOS shortcut - today](https://github.com/pointdexter3/iOS-shortcuts/blob/main/todoist/api_v1/Todoist-Today.shortcut)
- [iOS shortcut - Grocery List](https://github.com/pointdexter3/iOS-shortcuts/blob/main/todoist/api_v1/Todoist-Add-To-Grocery-List.shortcut)
- Add your Todoist api key to the text block within the shortcut [How to find your api key](https://todoist.com/help/articles/find-your-api-token-Jpzx9IIlB).

<br />

# Create Calendar Event from Text via ShareSheet (ChatGPT)
- Usecase: email events that do not provide an ICS file. Copy the text in the email and have the shortcut autopopulate the event details.
- [iOS shortcut]() UPDATE_LINK.
- Setup:
  - Install ChatGPT app
  - Save shortcut (uses chatGPT shortcuts app integration)
  - ℹ️ click info button on shortcut screen -> toggle on "Show in Share Sheet"
- Use:
  - Select text
  - click Share
  - scroll to bottom of share sheet to find the "Create Calendar Event From Text - github" option
  - create calendar screen will appear with all the details filled, verify title/dates/details are as expected and click save to <br />


<br />

# Add non-savable calendar events / ics files to calendar via ShareSheet
- Usecase: on iOS sometimes you open an event that doesn't have the "add to calendar" option.
- [iOS shortcut]() UPDATE_LINK.
- Setup:
  - ℹ️ click info button on shortcut screen -> toggle on "Show in Share Sheet"
- Use:
  - calendar event screen without the add option
  - click the Share option   
  - scroll to bottom of share sheet to find the "import ics - github" option


<br />


# TODOIST bulk add to grocery list (ChatGPT)
- Speak a list of items and have them added as tasks to your grocery list project in Todoist
- [iOS shortcut dependency]() UPDATE_LINK, have chatgpt determine list items
- [iOS shortcut main]() UPDATE_LINK
- Add your Todoist api key to the text block within the shortcut [How to find your api key](https://todoist.com/help/articles/find-your-api-token-Jpzx9IIlB).
- Setup:
  - Install ChatGPT app
  - Save shortcut (uses chatGPT shortcuts app integration)
  - Add your Todoist api key to the text block within the shortcut [How to find your api key](https://todoist.com/help/articles/find-your-api-token-Jpzx9IIlB).
- Use:
  - trigger shortcut (action button or rename to work better with siri
  - speak a list of items   
  - items are added to grocery list in todoist
  - care to avoid ambiguity eg "ketchup chips" could be 2 items or 1



# 🏗️ Under construction...

<br />

# MeadowStore [WIP]
- simple iOS app with shortcut intents to allow saving key/value pairs via icloud storage for use as persistent storage for iOS shortcuts 
- not currently available in testflight


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
