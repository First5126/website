# website
2025 EMP Website hosted on Github Pages. 

Uses Html and Jekyll and Github Actions to deploy site to Github Pages.

Uses the Jekyll theme Creative, https://jekyllthemes.io/theme/creative-theme-jekyll


To Modify the Site:
* Install VSCode and Git
* Clone the repository
* Get into the habit of doing a Pull/Fetch from the repository everytime you work on the website
* Create a new branch based off of dev
* Commit into your new branch
* Push branch to github
* Create a Pull Request with your changes to merge into dev and ask for reviewers.
* Approval of PR will allow you to merge your changes into dev branch.
* After merge, you can delete your branch.
* GitHub Actions will push those changes into a dev environment for verification of changes.
* When Ready to release, create a PR to merge dev to prod and ask for reviewers.
* When reviewed, we will merge that PR into main.
* GitHub Actions will deploy the site to prod.

 
To run on windows desktop
## Prerequisite:
Docker Desktop - [Download here](https://www.docker.com/products/docker-desktop/)
Install Ruby, https://rubyinstaller.org/
Install Jekyll, in terminal window `gem install jekyll`
Install Bundler, in terminal window `gem install bundler`
Make sure docker is running
Start Docker: `docker-compose up` in Terminal Window
Go to http://127.0.0.1:4000/ in your browser