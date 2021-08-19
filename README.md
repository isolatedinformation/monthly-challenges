# QOSF Monthly Challenges

A repository containing monthly challenges in quantum computing.

## Current Challenge

**Link to Challenge Notebook**: [August 2021 Challenge](challenge-2021.08-aug/challenge-2021.08-aug.ipynb) - W states

**Release date**: August 19th, 2021  
**Submission deadline (optional):** September 16, 2021

You can see previous challenges [here](#previous-challenges).

## How it Works

These challenges will help you hone your quantum computing skills by being exposed to a variety of problems in different areas.

We release a new challenge every month that are open to anyone and everyone. You're welcome to try your hand at solving them individually or as a team.   

You are free to use any framework that you like and submit your solutions in any format. Just make sure that they're easy to evaluate.

**You're also welcome to *contribute* challenges! Open an issue on this repo and describe your idea and we'll be happy to take a look at it!** 

## Tentative Timeline

- We try and release each challenge on the same date every month, but some times this varies (hey, we're all volunteers).
- You get a month's time to solve each challenge, but if you wish to have your solution reviewed please aim to submit your solution within the first 2 or 3 weeks (to allow for sufficient time for reviews).

## Submission

- Please fork this repository and use that to work on your solutions to the challenges. 
	- Under the challenge directory you wish to attempt to solve, create a folder with your github username (all lowercase, separated-by-hyphens). Your solution goes into this directory. Look at prior submissions for examples if you are not clear on this.
	- Do not delete or modify any of the original challenge files since this will show up when you submit your solution.
- If you complete a challenge and want to "submit" your solution, raise a Pull Request (PR) from your repo to ours. 
- **After you submit your PR, you must find at least one other reviewer to review your work**. Your reviewer could be a fellow challenge submitter (trade off reviews!), reach out individually to another community member on Slack, or post in the [#monthly-challenges](https://qosf.slack.com/archives/C01D2GB1DMM) channel asking for a review.
- We will give shout-outs to the best submissions! 😃
- Note that if you're working as a team, it is sufficient to submit just one PR. Please make sure to have all of your teammates properly credited in your solution.

## Evaluation

- We want this to be a community driven project, so evaluation will be in the form of peer reviews.
- *Please* take some time to go through other solutions and provide your feedback! The only way this will work well is if we learn from each other. 
- If you like a solution, please leave an emoji reaction with a 👍 on the PR. We need some feedback for picking the best submissions.

## Communication

- Please join the [#monthly-challenges](https://qosf.slack.com/archives/C01D2GB1DMM) Slack channel for the challenge where you can share ideas with others and ask any questions you might have.

## Git FAQ

- We recommend you install the new [GitHub CLI tool](https://cli.github.com/) which is pretty cool. 
- Forking: https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo
	- Pro tip: If you're using the CLI we just told you about, you can do this without ever leaving the terminal! Run `gh repo fork qosf/monthly-challenges`. When asked if you want to clone the repository, hit `n`.
- Cloning (first time setup):  
  - ```git clone htps://github.com/{{your-github-username}}/monthly-challenges.git```
    - If you're using the CLI, just run  ```gh repo clone {{your-github-username}}/monthly-challenges```.
  - run `git remote add upstream https://github.com/qosf/monthly-challenges.git`. You **DO NOT** have to do this if you used the CLI to clone your repo (it does that automatically).
  - run ```git checkout main```
-  What to do before starting a new challenge:
   - Bring your fork on-par with our repo
		```
		git fetch upstream
		git checkout main
		git merge main upstream/main
		git push
		```
   - Create a branch to work on the new challenge
      - `git branch -b {{branch name}}`
- Work on the challenge (make sure your changes are all on the right branch).
- Periodically push your changes to your fork
   - `git push -u origin {{branch name}}` the first time you push. For subsequent pushes, just `git push`.
- Raising a Pull Request: https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests
  

Any other questions? Try the [GitHub documentation](https://docs.github.com/en) or ping us on Slack!

## Previous Challenges

<!-- use two spaces after each line to have line breaks -->  
[November 2020 Challenge](challenge-2020.11-nov/challenge-2020.11-nov.pdf): Diagonal Unitaries  
Release date: November 2nd, 2020  
Submission deadline (optional): November 23rd, 2020   

---

[December 2020 Challenge](challenge-2020.12-dec/challenge-2020.12-dec.ipynb): Minimum Hamming Distance  
Release date: December 10th, 2020   
Submission deadline (optional): January 9th, 2021  

---

[January 2021 Challenge](challenge-2021.01-jan/challenge-2021.01-jan.ipynb): Minimum Makespan    
Release date: January 10th, 2020  
Submission deadline (optional): February 9th, 2021  

---

[February 2021 Challenge](challenge-2021.02-feb/challenge-2021.02-feb.ipynb): QOSF Mentorship Screening Tasks  
Release date: February 18th, 2021  
Submission deadline (optional): March 17th, 2021  

---

[March 2021 Challenge](challenge-2021.03-mar/challenge-2021.03-mar.ipynb): Quantum Autoencoders (QML)  
Release date: March 19th, 2021  
Submission deadline (optional): April 18th, 2021  

---

[April 2021 Challenge](challenge-2021.04-apr/challenge-2021.04-apr.ipynb): Mermin-Peres Magic Square Game  
Release date: April 22nd, 2021  
Submission deadline (optional): May 21st, 2021  

---

[May 2021 Challenge](challenge-2021.05-may/challenge-2021.05-may.ipynb): unitaryHACK!  
Release date: May 14th, 2021  
Submission deadline (optional): May 30th, 2021    

---

[June 2021 Challenge](challenge-2021.06-jun/challenge-2021.06-jun.ipynb): k-Nearest Neighbors  
Release date: June 19th, 2021  
Submission deadline (optional): July 17th, 2021  

---

[July 2021 Challenge](challenge-2021.07-jul/challenge-2021.07-jul.ipynb): Quantum State Tomography  
Release date: July 21st, 2021  
Submission deadline (optional): August 18th, 2021  