# CS453: work in Colab, save progress in GitHub

Your submission is **your repository URL plus the final commit link**, submitted in the existing Google Classroom assignment. Google Classroom and GitHub Classroom are different products; no GitHub Classroom invitation or terminal commands are needed for this workflow.

## 1. Create your private copy from the course template

On the professor's public starter repository, select **Use this template > Create a new repository**. Choose your own account, name it `cs453-ai-project`, select **Private**, and create it. Do not use Fork and do not upload work to a branch in the professor's repository.

In your new repository, use **Settings > Collaborators > Add people** to invite the professor’s GitHub username `AliElzaileek`. You can work while the invitation is pending. Do not invite classmates.

## 2. Use the files already included

Your copy already contains `project.ipynb`, the guide in `docs/student-guide.pdf`, and the study notebooks in `references/`. There is no need to upload the workbook again. Keep `project.ipynb` at the repository root.

Complete the student README template in `docs/STUDENT_README_TEMPLATE.md`, then use its completed content to replace your own root `README.md`. Update its Colab link to your own username/repository. The two-week task uses code-defined graph data, so no data folder is required.

## 3. Open and work in Colab

Go to [Colab's GitHub browser](https://colab.research.google.com/github). Locate your repository and `project.ipynb`. For a private repository, enable **Include Private Repos** and complete GitHub authorization if prompted. Open the notebook and work there.

You may keep a working copy in Drive. **Saving to Drive does not update GitHub.** Reopening from GitHub loads the version last committed there. Keep one current working copy and explicitly commit progress.

## 4. Save progress to GitHub after each work session

In Colab's **File** menu, choose **Save a copy in/to GitHub**. Confirm your own repository, its branch (`master` in this starter; check your own default branch), and the existing path `project.ipynb`. Add a descriptive commit message and save. Complete authorization if required. Check the file and latest commit on GitHub before closing Colab. Avoid duplicate filenames such as `Copy of project.ipynb`.

If direct GitHub saving/private access fails, use the browser-only fallback: download the notebook from Colab as `.ipynb`, name it `project.ipynb`, then upload it through GitHub to replace that same file and commit. To resume, download the latest committed notebook from GitHub and upload it to Colab. A local upload also works without connecting the two accounts. Do not paste passwords or access tokens into notebook cells.

## 5. Show real progress over the two weeks

Commit at meaningful milestones: setup; agent and simulator; BFS implementation; A* implementation; final review. Example messages: `Add legal task actions`, `Add BFS baseline`, `Add A-star search`, `Verify final notebook and README`.

Do not fabricate/backdate history or submit all work as one unexplained last-minute upload. History supports your explanation; the number of commits is not a separate grading target.

## 6. Complete README.md

Use `docs/STUDENT_README_TEMPLATE.md` in your repository as a starting point and save its contents as `README.md`. Include project choice, your name/ID, assigned variant, file list, run steps, progress summary, assigned mission outputs and sources/assistance disclosure.

Add an Open in Colab link by replacing `YOUR_USERNAME` and, if different, the repository/branch in this example:

```markdown
[Open in Colab](https://colab.research.google.com/github/YOUR_USERNAME/cs453-ai-project/blob/master/project.ipynb)
```

For private repositories, the link does not grant access. The reader still needs GitHub permission and Colab authorization; the download/upload fallback remains available. A notebook opened from GitHub does not automatically load other repository files into its runtime. For later files, document upload/loading steps; the initial graph requires none.

## 7. Verify and submit the exact version

1. In Colab, restart the session and run all cells. Inspect mission outputs and written explanations.
2. Commit the final notebook and README to GitHub. Check that the saved notebook contains the expected outputs.
3. Reopen/download the committed `project.ipynb` into a fresh Colab session and run it again. Fix and recommit if necessary. If the saved content changes during this check, commit it and use the new final commit.
4. On GitHub, open the final commit's details and copy its URL. It has the form `https://github.com/YOUR_USERNAME/cs453-ai-project/commit/FULL_COMMIT_SHA`.
5. In the Google Classroom assignment, attach the repository URL and final commit URL using **Add or create > Link**, then select **Turn in**. If the interface accepts only one link, attach the repository and put the commit URL in a private assignment comment. Include the chosen project and GitHub username.
6. Confirm the professor's invitation was sent and will be available for acceptance. Do not switch the repo to public to fix an access issue; check the username and invitation first.

The submitted commit identifies the checkpoint version for marking, even when you continue the project later. Follow the announced deadline and late policy. Do not replace the submitted snapshot with later work without identifying the new commit and following that policy.

## Sources for the interface instructions

- [Google Colab's official GitHub integration notebook](https://github.com/googlecolab/colabtools/blob/main/notebooks/colab-github-demo.ipynb)
- [GitHub: create a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
- [GitHub: invite collaborators](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/repository-access-and-collaboration/inviting-collaborators-to-a-personal-repository)
- [GitHub: upload files](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
