# Contribution Guidelines

## Project Setup
Refer to the [README](README.md).

## Reporting issues

- **Search for existing issues.** Please check to see if someone else has reported the same issue.
- **Share as much information as possible.** Include operating system and version, browser and version. Also, include steps to reproduce the bug.

## Contributing
We welcome any type of contributions. This may include changes to images, text in the documents, or changes to the code to render the PDF or related documentation. The general process for contributing is to fork the GitHub repository, make the changes, then submit a pull request. 
We ask that images and text follows the general style already present. In terms of text, please use citations where possible. 

## Pull requests
- Try not to pollute your pull request with unintended changes – keep them simple and small. If possible, squash your commits.
- Try to share how your code has been tested before submitting a pull request.
- If your PR resolves an issue, include **closes #ISSUE_NUMBER** in your commit message (or a [synonym](https://help.github.com/articles/closing-issues-via-commit-messages)).
- Please state in the PR if the changes (e.g. to code) have been tested thoroughly. 
- Review
    - If your PR is ready for review, another contributor will be assigned to review your PR
    - The reviewer will accept or comment on the PR. 
    - If needed address the comments left by the reviewer. Once you're ready to continue the review, ping the reviewer in a comment.
    - Once accepted your code will be merged to `main`

## Testing
Please test all changes locally before submitting a pull request. For instance you can run Pandoc locally (or the GitHub action via the forked repository) to ensure the documents render properly following your changes. 
