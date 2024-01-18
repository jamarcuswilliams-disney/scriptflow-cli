# Ripple CLI
Ripple CLI is a command-line tool for managing and executing custom flows of commands in different terminal profiles such as Bash, Zsh, PowerShell, and CMD. It allows you to create, list, run, delete, and edit flows easily.

## Installation
You can install Ripple CLI globally using npm:

```bash
npm install -g ripple_cli
```
This will make the ripple command available globally in your terminal.

## Usage
Ripple CLI provides the following commands:

### Initialize Ripple CLI
To initialize Ripple CLI and configure your terminal profile and flow directory, run:

```bash
flow init
```
Create a New Flow

###  Create a New Flow
To create a new flow, use the following command:

```bash
flow create
```
You will be prompted to provide a flow name, flow path, and a list of commands. The script will generate a script file with the appropriate shebang line for your selected terminal profile.

### List All Flows
To list all available flows, use the following command:

```bash
flow list
```

### Run a Flow
To execute a previously defined flow by name, use the following command:

```bash
flow run <flowName>
```

Replace <flowName> with the name of the flow you want to run.

### Delete a Flow
To delete a flow by name, use the following command:

```bash
flow delete <flowName>
```

Replace <flowName> with the name of the flow you want to delete.

### Edit a Flow
To edit the script file associated with a flow, use the following command:

```bash
ripple edit <flowName>
```

Replace <flowName> with the name of the flow you want to edit. This command opens the script file in the default text editor for your terminal profile.

## Configuration
The configuration for Ripple CLI is stored in a config.json file. You can customize terminal profiles and default settings by modifying this file.

## Contributing
If you'd like to contribute to Ripple CLI or report issues, please check the GitHub repository for more details.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

