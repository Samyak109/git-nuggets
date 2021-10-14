# Git-nuggets

# How to contribute

Have an awesome Git Resource? Solved a cumbersome problem with git single handedly and want to share your approach with dev world ? 
We're open to any kind of contribution, just follow the guidelines and you're good to go!

### Issues

- Submit a new [issue](https://github.com/Samyak109/git-nuggets/issues)
- Comment on an issue to get assigned

### Code Contribution

#### Fork

Fork the repository on your account by clicking on the fork button on the top right corner of the repository.<br />
![fork](https://user-images.githubusercontent.com/55744578/136408259-1fe32569-0853-4d17-b0d5-ec5a7c4425bd.jpg)

#### Clone the fork

Clone setup the repository on your local machine using this command <br />
`$ git clone git@github.com:[your_github_handle]/git-nuggets.git`
<br />
You might also need to generate a Personal Access Token due to new rules by Github.
Here's how to generate a [Personal Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) in case you don't know.

#### Adding a exercise

- Make sure your exercise doesn't match with any of the already exisitng problems/exercises in the repository. Go through the repostiry and the issues section for some ideas and try to follow the same convention and folder structure.
- Folder Structure 
- Create a folder inside `Exercises/` and use name convention as `Ex:{Number}{Short Description}`. Make Sure Description is short and should express the problem.
- Create 3 Files
    1. Problem
    2. Hints
    3. Approach
- Please consider writing descriptive names and quality comments for your exercises.

#### Submitting a PR

- Creat and checkout a new branch using `git checkout -B <branch-name>`
  - Use `git add .` to stage your changes
  - Use `git commit -m "your-commit-message"` to commit your changes
  - Use `git push origin <branch-name> to push changes to remote`
- Lastly, go to your fork and click on "Compare & Pull Request"
  ![compare&pull](https://user-images.githubusercontent.com/43697446/134040805-c114ccf9-aa14-427e-b01f-8dcb2f58ef94.png)
- Write a brief discription about the PR and the changes you made
