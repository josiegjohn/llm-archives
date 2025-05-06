# llm-archives

### Instructions

Click the "Use this template" button for this repository and choose "Create a new repository". You can give it the same name (llm-archives).

Once it's ready, go to [Groq](https://console.groq.com/keys) and follow the directions to get an API key. You'll need to login (or create an account if you don't have one).

Copy the API key value and then click on the Settings of your GitHub repository and click on "Secrets and variables" on the left side, then choose "Codespaces"

Click the green "New Repository Secret" button and paste your API Key into the "Secret" box, then put GROQ_API_KEY in the Name box above it. Click "Add Secret" and click on the name of the repository to return to the main page.

From there, click the green "Code" button and create a new Codespace in the Codespaces tab.

In the Terminal type the following: pip install requests groq and hit enter.

Then type: python get_stories.py

You should see a file called cns_maryland_posts.json appear. Let's look at it. It contains some details of the past 10 CNS stories.

Back in the Terminal, type: python entity_extraction.py and watch the output.

### Evaluation for JOUR389W

My EVALUATION:

It took me a second to see where the output was going, but once I saw it in the bottom it was pretty accurate. In hindsight I didn't give it the best article for this assignment, most noticably because some quotes are literally from the city of Roanoke. Which is not a person, but is talking. So technically it did nothing wrong, but I almost would have liked to see Roanoke listed as a person as well, with an explanation of why.

For Roanoke Rambler, they take on a lot of investigative stories with a small team, this could save them some time while on the hunt for potential stories. We used this to get information from stories published by CNS, but maybe an example of what Roanoke Rambler could do with this would be to read Congress press releases for most commonly mentioned organizations and names, or something like that. 
Or, in their own archives, Roanoke Rambler could keep track of what topic theyve covered, who they have covering each topic, what sources they've talked to already, things like this.
For a small organization run by a small group of white guys, this could have a good place in keeping track of what communities they cover. Like for example, there's two areas of Roanoke-- Old Southwest, a lower income diverse area, and South Roanoke, a high income nondiverse area. They could use a similar entity to track, for example, stories based in South Roanoke or affecting South Roanoke residents compared to those from Old Southwest to make sure the coverage is fair.

They could also use this to watch crime, check for big names, things like that. Having this running in the background to track connections could provide a good base of story ideas. Like, if the mayor was in the crime stats. 

Let it be noted, at the end of this my laptop is so hot to the touch that I cannot rest my hand on certain parts of it. Cool. 
