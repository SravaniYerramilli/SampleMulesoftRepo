# SampleMulesoftRepo
Branching strategy is Feature, Dev, Qa, Master, dev being the default
Can have multiple feature branches
Code build should happen everytime a checkin happens in feature branch
Create a PR from feature to dev
Assign the PR to a group of people, merge the code from feature to dev after the PR approval(send email approval)
Trigger a pipeline to deploy code to dev environment
