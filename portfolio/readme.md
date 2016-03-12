#PORTFOLIO DEPLOYMENT PLAN

1. Develop site on local machine.
2. Navigate to proper folder in command line.
3. Commit content
  * `git add -A`
  * `git commit -m "comment here"`
4. Push to GitHub master branch
  * `push github master`
5. You or your team can now review code, and access it via github
  * `git pull github master`
6. Push the code to remote Staging server for testing
  * `git push Staging master`
7. Review code in the server environment. Make any needed changes
8. Once everything is working properly, push to the Live server.
  * `git push Live master`