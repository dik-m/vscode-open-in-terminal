# VSC Open in Terminal

<p align="center">
	<img src="https://raw.githubusercontent.com/fabiospampinato/vscode-open-in-terminal/master/resources/logo-128x128.png" alt="Logo">
</p>

Adds a few commands for opening the current project in Terminal.

It can be configured to use whichever terminal app you want.

## Install

Run the following in the command palette:

```shell
ext install vscode-open-in-terminal
```

## Usage

It adds 4 commands to the command palette:

```js
'Open in Terminal' // Open the current folder in the terminal
'Open Root in Terminal' // Open the current project in the terminal
'Open in Integrated Terminal' // Open the current folder in the integrated terminal
'Open Root in Integrated Terminal' // Open the current project in the integrated terminal
```

## Settings

```js
{
  "openInTerminal.app": "Terminal" // The name of your terminal app
}
```

## License

MIT © Fabio Spampinato
