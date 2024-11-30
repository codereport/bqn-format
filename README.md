# <p align="center">bqn-format</p>

<p align="center">
    <a href="https://github.com/codereport/bqn-format/issues" alt="contributions welcome">
        <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" /></a>
    <a href="https://lbesson.mit-license.org/" alt="MIT license">
        <img src="https://img.shields.io/badge/License-MIT-blue.svg" /></a>
    <a href="mlochbaum.github.io/BQN">
        <img src="https://img.shields.io/badge/BQN-0.7-ff69b4.svg"/></a>
    <a href="https://github.com/codereport?tab=followers" alt="GitHub followers">
        <img src="https://img.shields.io/github/followers/codereport.svg?style=social&label=Follow" /></a>
    <a href="https://GitHub.com/codereport/bqn-format/stargazers/" alt="GitHub stars">
        <img src="https://img.shields.io/github/stars/codereport/bqn-format.svg?style=social&label=Star" /></a>
    <a href="https://twitter.com/code_report" alt="Twitter">
        <img src="https://img.shields.io/twitter/follow/code_report.svg?style=social&label=@code_report" /></a>
</p>

### 🚧🚧🚧 THIS IS A WIP. MANY CORNER CASES CURRENTLY DO NOT WORK.  🚧🚧🚧

A (soon to be configurable) formatter for [BQN](https://mlochbaum.github.io/BQN).

### Usage

#### Running from the command line

Basic usage shown below:
```bash
bqn-format .        # for all bqn files (including subdirectories)
bqn-format test.bqn # for single file
```

Note, after `git clone`-ing this repo, you will probably want to put the `bqn-format` script on your path:
```bash
export PATH=$PATH:/home/cph/bqn-format
```

#### Using from VS Code

There is a [Run on Save](https://marketplace.visualstudio.com/items?itemName=emeraldwalk.RunOnSave) where you can add something like the following to your JSON Settings:

```json
  "emeraldwalk.runonsave": {
    "commands": [
      {
        "match": ".*bqn.*",
        "cmd": "bqn-format ${file}"
      }
    ]
  },
```

Then your BQN code will be formatted on save.

Eventually there will be a BQN formatter extension or this will be folded into the existing [BQN VS Code extension](https://marketplace.visualstudio.com/items?itemName=mk12.bqn).

### Demo

Coming.



