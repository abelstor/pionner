## Git branches Workshop

### How to manage git branches to streamline your workflow

- Create a new branch for each feature or bugfix you work on:
  ```bash
  git checkout -b your-feature-name
  ```
- Regularly commit your changes with clear messages:
  ```bash
  git add .
  git commit -m "Add feature X"
  ```
- Push your branch to the remote repository:
  ```bash
  git push origin your-feature-name
  ```
- When your feature is complete, create a pull request to merge your branch into the main branch.
- After the pull request is approved and merged, delete your feature branch both locally and remotely:
  ```bash
  git branch -d your-feature-name
  git push origin --delete your-feature-name
  ```
