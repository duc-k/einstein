<div align="center">
  <img src="https://i.imgur.com/FdnrH7d.gif" />
  <h1>Installation</h1>
</div>

## Requirements

- You must have the vsce package installed on your machine, you can install it globally with the command `npm i --location=global vsce`

## Steps

- [x] Clone the repository from GitHub

```bash
git clone https://github.com/duc-k/einstein.git
```

- [x] Generate the .vsix file

```bash
vsce package
```

- [x] Install the .vsix file in VSCode

  - Open the command palette (`Ctrl+Shift+P`) and select `Install from VSIX`.
  - Now select the generated .vsix file.
  - Restart VSCode.
  - Now just be happy.