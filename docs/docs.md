# boots

## Usage
> This will bootstrap your os

boots

## Flags
|Flag|Usage|
|----|-----|
|`--debug`|enable debug messages|
|`--disable-update-checks`|disables update checks|
|`--raw`|print unstyled raw output (set it if output is written to a file)|

## Commands
|Command|Usage|
|-------|-----|
|`boots completion`|Generate the autocompletion script for the specified shell|
|`boots help`|Help about any command|
# ... completion
`boots completion`

## Usage
> Generate the autocompletion script for the specified shell

boots completion

## Description

```
Generate the autocompletion script for boots for the specified shell.
See each sub-command's help for details on how to use the generated script.

```

## Commands
|Command|Usage|
|-------|-----|
|`boots completion bash`|Generate the autocompletion script for bash|
|`boots completion fish`|Generate the autocompletion script for fish|
|`boots completion powershell`|Generate the autocompletion script for powershell|
|`boots completion zsh`|Generate the autocompletion script for zsh|
# ... completion bash
`boots completion bash`

## Usage
> Generate the autocompletion script for bash

boots completion bash

## Description

```
Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(boots completion bash)

To load completions for every new session, execute once:

#### Linux:

	boots completion bash > /etc/bash_completion.d/boots

#### macOS:

	boots completion bash > /usr/local/etc/bash_completion.d/boots

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion fish
`boots completion fish`

## Usage
> Generate the autocompletion script for fish

boots completion fish

## Description

```
Generate the autocompletion script for the fish shell.

To load completions in your current shell session:

	boots completion fish | source

To load completions for every new session, execute once:

	boots completion fish > ~/.config/fish/completions/boots.fish

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion powershell
`boots completion powershell`

## Usage
> Generate the autocompletion script for powershell

boots completion powershell

## Description

```
Generate the autocompletion script for powershell.

To load completions in your current shell session:

	boots completion powershell | Out-String | Invoke-Expression

To load completions for every new session, add the output of the above command
to your powershell profile.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion zsh
`boots completion zsh`

## Usage
> Generate the autocompletion script for zsh

boots completion zsh

## Description

```
Generate the autocompletion script for the zsh shell.

If shell completion is not already enabled in your environment you will need
to enable it.  You can execute the following once:

	echo "autoload -U compinit; compinit" >> ~/.zshrc

To load completions for every new session, execute once:

#### Linux:

	boots completion zsh > "${fpath[1]}/_boots"

#### macOS:

	boots completion zsh > /usr/local/share/zsh/site-functions/_boots

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... help
`boots help`

## Usage
> Help about any command

boots help [command]

## Description

```
Help provides help for any command in the application.
Simply type boots help [path to command] for full details.
```


---
> **Documentation automatically generated with [PTerm](https://github.com/pterm/cli-template) on 08 May 2022**
