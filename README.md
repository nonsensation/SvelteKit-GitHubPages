# Example SvelteKit for GitHub-Pages

Using:

* Static files (markdown)
* Routing
* Automatic Github Deploy on Push
* Libraries: 
    * PostCSS
    * Marked for Markdown Support

## Setup GitHub-Pages

This assumes your repositry is public.
I have **not** tested this with the GitHub-Username page, only a repository page.


1. commit and push to GH
2. In your Repository go to _Settings > Actions > General > Workflow permissions_ > and enable _Read and Write Permissions_, don't forget to hit _Save_
3. Wait for the _Build_ and _Deploy_ action to finish, the first time it will fail.  
   Change in the Repository _Settings > Actions > Pages_ to _Deploy from a Branch_ and choose the `gh-pages` Branch.
4. Go to _Actions_ and re-run the failed task.
5. Wait a minute, your Site should be published at https://your-username.gihub.io/your-repository
