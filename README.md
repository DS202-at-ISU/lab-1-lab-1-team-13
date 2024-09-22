
<!-- README.md is generated from README.Rmd. Please edit the README.Rmd file -->

## Lab report \#1

## Section 12.1

- We all made our Githubs accounts and forked the team repository in our
  Githubs accounts using the Github classroom link shared on canvas
  announcements.
- We ensured the installation of R and RStudio on our personal devices.
- We installed Git by using the terminal commands `git --version` and
  installed Git using the Mac Xcode Command Line Tools using the GUI
  pop-up screen.
- We then declared our names and emails to Github using the following
  commands:
  - `git config --global user.name {your name}`
  - `git config --global user.email {your email}`

## Section 12.2 - We made our own personal testing repositories to test

the push and pull commands. - Creating a repo: - Using the Github GUI we
created our own public repo’s and named them as MyRepo and had these
repo’s made out of no templates and default README.md files.

## Section 12.3

- To edit the Rmd file, we opened the GitHub repo on RStudio using the
  GUI offered by executing the following steps:
  - Open RStudio
  - Click on File \> New Project \> Version Control \> Git \> Entered
    the GitHub Remote Repo Link and selected the location where we want
    the project to be saved on our local device.
- By doing so, RStudio, created a local version for the remote
  repository on our device and then we started to make local changes and
  saved them on our device.

## Section 12.4

- Since there are 6 steps listed on Chapter 12 Happy Git With R, that
  are to be executed, we started documenting all the steps here in this
  Rmd file.
- We split up the tasks as follows:
  - Amaya Brooks \> Sections 12.1 & 12.2
  - Pranava Sai Maganti \> Sections 12.3 & 12.4
  - Adam Grimm \> Sections 12.5 & 12.6
- We started editing this file one by one based on the order of
  sections, and once Amaya finished making her changes, she used the
  following commands to push her local changes to the remote repository:
  - To add/stage the files: `git add .`
  - To commit the changes:
    `git commit -m {message describing the changes briefly}`
  - To push the changes: `git push origin main`
- Once, her changes are done, Pranava followed the same steps to clone
  the repository through RStudio and checked for any changes by clicking
  on Git in the upper right tab and selected the button that updates the
  repo with any changes from the remote repo with the local repo.
- Once Pranava, finished his changes that is added documentation for
  Sections 12.3 and 12.4, he pushed the changes to the Remote Repository
  using the same steps mentioned earlier.
- Finally, Adam repeated the same steps for updating the local repo and
  added documentation for Sections 12.5 and 12.6 and pushed the changes
  to the remote repository.

## Section 12.7

- Since deleting the local repository is dangerous as it deletes all the
  local changes, without doing so, we are describing how to delete a
  local repository:
  - All GitHub repos once cloned, are saved as folders on our devices.
  - It depends on what commands we use to delete the folder - it either
    deletes the complete existence of the local repo folder or deletes a
    repo partially.
  - Command 1:
    - Navigate to the root folder where the local repo exists using the
      `cd {root_folder_name}`
    - Then using the following command we delete the repo partially
      (highly advised): `rm {local_repo_name}`
  - Command 2:
    - Navigate to the root folder where the local repo exists using the
      `cd {root_folder_name}`
    - Then using the following command we delete the repo permanently
      making it not visible even in the recycle bin (highly not
      recommended): `rm -rf {local_repo_name}`.

------------------------------------------------------------------------
