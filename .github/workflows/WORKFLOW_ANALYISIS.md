-What triggers this workflow to run? 
    When there is a push to the Main branch, and a pull request to the main branch
-What are the four main steps this workflow performs? 
    1. Checkout code 2. Validate HTML 3. Check links 4. Upload artifact
-What does the "Checkout code" step do and why is it necessary?
    it "checks out" the code like its a book from a library. This is necessary to that what the programmer has is the most up-to-date code, and can change it without interfering with or be interfered with what others on the team are doing. 
-What is the purpose of the environment configuration?
    to make reliable, clean pull requests automated.
-How does this automated deployment improve reliability compared to manual deployment?
    Beacuse it can be done whenever and wherever, it doesn't always fall to the shoulders of one or a few people who can (and do) make mistakes. 
- What would happen if you pushed code to a different branch (not main)?
    The code would "show up" in the branch without ever touching the main branch.