# Open in GitHub

<p align="center">
	<img src="https://raw.githubusercontent.com/fabiospampinato/vscode-open-in-github/master/resources/logo-128x128.png" alt="Logo">
</p>

Open the current project or file in github.com.

There are many other extensions for doing this, but they either don't work well for me or they provide too few/many functionalities.

## Install

Follow the instructions in the [Marketplace](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-open-in-github), or run the following in the command palette:

```shell
ext install fabiospampinato.vscode-open-in-github
```

## Usage

It adds 6 commands to the command palette:

```js
'Open in GitHub: Project' // Open the current project in GitHub
'Open in GitHub: File' // Open the current file in GitHub
'Open in GitHub: File Blame' // Open the current file's blame in GitHub
'Open in GitHub: File History' // Open the current file's history in GitHub
'Open in GitHub: Issues' // Open the current project's issues in GitHub
'Open in GitHub: Pull Requests' // Open the current project's pull requests in GitHub
```

## Settings

```js
{
  "openInGitHub.github.domain": "github.com", // Custom GitHub domain
  "openInGitHub.remote.name": "origin", // Name of the remote repository
  "openInGitHub.remote.branch": "master", // Name of the remote branch
  "openInGitHub.useLocalBranch": true, // Use the local branch instead of the fixed remote branch
  "openInGitHub.useLocalRange": true // Highlight the local selection range when possible
}
```

## Demo

### Opening the project

![Project](resources/demo/project.gif)

### Opening the file

![File](resources/demo/file.gif)

## License

MIT © Fabio Spampinato