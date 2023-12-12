# PowerShell Cheat Sheet

This cheat sheet provides a quick reference to some of the most commonly used PowerShell commands.

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

