# Frontend Mentor - Fylo landing page with two column layout

## How I handled this exercise 👋  

First thing was to get a sketch pad and draw out both versions: mobile and desktop... what areas will I be dealing with? What order of areas change on mobile?

### Initial set up
`git`: Set up [personal repo](https://github.com/pychap/fylo-landing-page) and made sure all's connected. [This article](https://www.a2hosting.com/kb/developer-corner/version-control-systems1/403-forbidden-error-message-when-you-try-to-push-to-a-github-repository), and the below helped me with some issues I was having.

Git note to self about post-initialization steps (thanks to [Matt Studdert's article](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248)):  
*  I need to make the connection between [my] locally initialized project and the remote Git repository on GitHub. To do this, copy the command from the repository setup page that looks like this: `git remote add origin git@github.com:username/repository-name.git`. Paste it into the command line and hit enter.  
*  Next, push the code to that repository by typing `git push -u origin master` and hitting enter.  

Next I set up my SCSS environment. I use Visual Studio code with "Watch SASS", and I have a simple Parcel workflow. Once scss is set up I get to the `index.html` file and link up the stylesheet.

### HTML
I then structure out the HTML observing best practices for HTML5 content logic.

