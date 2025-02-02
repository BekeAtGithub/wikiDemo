Create a Wikipedia Bot Account

    Register a bot account on Wikipedia: Bot Registration / https://en.wikipedia.org/wiki/Help:Creating_a_bot
    Request API access.

    Will have to run python pwb.py generate_user_files to activate user-config.py file

How It Works

    GitHub Repository: Store the Wikipedia article's content in a file (yourfile.md).
    Python Script: Fetch the content from GitHub and push it to Wikipedia using Pywikibot.
    GitHub Actions: Automate updates by running the Python script whenever new changes are pushed to the repository.

update_wikipedia.py = This script fetches the content from a GitHub repository and updates a Wikipedia page using Pywikibot.

user-config.py = This configuration file helps Pywikibot know which Wikipedia site and account to use.

.github/workflows/update-wikipedia.yml = This workflow automatically updates the Wikipedia page whenever new content is pushed to the GitHub repository.

![alt text](https://github.com/BekeAtGithub/flaskEC2/blob/master/FlaskEC2.drawio.png)