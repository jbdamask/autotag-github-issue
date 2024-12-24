# Github issue autotagger
Install this as a github action:
* Create .github/workflows folder in your repo at the root level
* Copy in this file
Create a new repository secret for your OpenAI API key (if you don't have one, check the latest OpenAI developer quickstart)
* In your GitHub repo, click Settings, Secrets and Variables, Actions
* Create new repository secret with the name OPENAI_API_KEY and paste in your key
Try it out
* git add .
* git commit -m "Adding LLM-based issue tagger"
* git push origin main
Now add a new Issue. After a few seconds you'll see it has a label. 
## Troubleshooting
Check the Actions logs if it doesn't look like things are working. This should point you in the right direction
