# PowerShell Cheat Sheet 
 
This cheat sheet provides a quick reference to some of the most commonly used PowerShell commands.

# PowerShell Overview:-

PowerShell is a powerful scripting language and command-line shell developed by Microsoft, primarily used for automating system administration tasks and managing Windows-based servers and workstations.

## Key Concepts 

### 1. Cmdlets
Cmdlets are the core of PowerShell, which are specialized .NET classes implementing particular operations. They follow a verb-noun naming convention, like `Get-Content`, `Set-Item`, etc.

### 2. Scripting
PowerShell enables writing scripts to automate tasks, which are saved with a `.ps1` extension. Scripting is essential for automating repetitive tasks.

### 3. Pipeline
The pipeline concept in PowerShell allows passing the output of one cmdlet as the input to another, enabling complex operations with simple, one-liner commands.

### 4. Object-Based Nature
PowerShell works with .NET objects, meaning the output of commands is objects. Understanding how to manipulate these objects is crucial.

### 5. Remote Management
PowerShell supports remote management of computers, allowing scripts and commands to be run on remote systems.

### 6. Integrated Scripting Environment (ISE)
PowerShell ISE is a graphical interface supporting enhanced scripting, with a script editor, debugger, and console pane.

By mastering these key aspects, users can effectively utilize the most functional and widely-used features of PowerShell.


## Getting Help

- `Get-Help <cmd>`: Get detailed help information for a specific command.
- `Get-Command`: Lists all commands available.
- `Get-Module -ListAvailable`: List all modules installed.

## Basic File Operations

- `Get-ChildItem`: List files and directories in the current directory.
- `Copy-Item <path1> <path2>`: Copy file or directory from path1 to path2.
- `Move-Item <path1> <path2>`: Move file or directory from path1 to path2.
- `Remove-Item <path>`: Delete file or directory.

## Working with Text Files

- `Get-Content <file>`: Display the contents of a file.
- `Set-Content <file> <content>`: Write or replace content in a file.
- `Add-Content <file> <content>`: Append content to a file.

## System Information

- `Get-Process`: List all running processes.
- `Get-Service`: List all services and their status.
- `Get-SystemInfo`: Display detailed system information.

## Networking

- `Test-NetConnection <hostname>`: Test network connection to a host.
- `Get-NetIPAddress`: Get IP address configuration.
- `Resolve-DnsName <hostname>`: Resolve a DNS name to an IP address.

## PowerShell Scripting

- `If (<condition>) {<action>}`: Conditional execution.
- `ForEach ($item in <collection>) {<action>}`: Loop through each item in a collection.
- `Function <name> {<commands>}`: Define a reusable block of commands.

## PowerShell Remoting

- `Enter-PSSession -ComputerName <name>`: Start an interactive session with a remote computer.
- `Invoke-Command -ComputerName <name> -ScriptBlock {<commands>}`: Run commands on a remote computer.

## Managing Modules and Packages

- `Install-Module <name>`: Install a PowerShell module.
- `Find-Package <name>`: Find a package in a package repository.
- `Install-Package <name>`: Install a software package.

