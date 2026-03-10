## Powershell vs Windows Command Line
- Windows CL works with text
- Powershell works with objects (items with data and functions)
- Powershell is built off the .NET framework
- Windows CL is built off legacy bash

## Basic Syntax: Verb-Noun
- Powershell commands are known as cmdlets
- Cmdlets follow a verb-noun naming convention
- Verb describes the action, noun specifies the object on which the action is performed

## Basic Cmdlets
- Get-Command: lists all available cmdlets, append -Name then the name your looking for (can use * at the end to get list of command with that name)
- Get-Help: provides info about cmdlets, append -Examples to show a list of common ways the cmdlet is used

## Find and Download Cmdlets
- You can download additional cmdlets from online repositories
- Find-Module: searches for modules (collections of cmdlets) in online repositories
- If you don't know exact name of module you can search for modules w/ similar name by filtering the Name property and appending a wildcard (*) to the name
- Install-Module: once identified modules can be downloaded

## Navigating and Working with File System
- Get-ChildItem: lists files and directories in a system (similar to ls), use -Path to list things for that specific directory
- Set-Location -Path: changes what directory your in (similar to cd)
- New-Item -Path -ItemType: creates a new item, you need to specify its path and its type (whether its a file or directory)
- Remove-Item -Path: removes an item (directory or file)
- Copy-Item: copies an item
- Move-Item: moves an item
- Get-Content: read and display content of a file

## Piping, Filtering, and Sorting Data
- Piping: technique where the output of one command becomes the input of another command, uses | to achieve this
- Example of piping: Get-ChildItem | Sort-Object Length
- Example of piping: Get-ChildItem | Where-Object -Property "Extension" -eq ".txt"
- Where-Object: filters objects based on specified conditions, returning only those that meet the criteria
- Select-Object: select specific properties from objects or limit number of objects returned
- Select-String: searches for text patterns within files
- Example of selecting properties that match using -like: Get-ChildItem | Where-Object -Property "Name" -like "ship*"

- Some comparison operators:
    - -eq: equal to
    - -ne: not equal to
    - -gt: greater than
    - -ge: greater than or equal to
    - -lt: less than
    - -le: less than or equal to
 
## System and Network Configuration
- Get-ComputerInfo: retrieves comprehensive system info
- Get-LocalUser: lists all the local users accounts on the system
- Get-NetIPConfiguration: provides info about the network interfaces on the system (ip addresses, DNS servers, etc)
- Get-NetIPAddress: details for all IP addresses configured on the system

## Real Time System Analysis
- Get-Process: lists all currently running processes
- Get-Service: status of services on machine
- Get-NetTCPConnection: displays current TCP connections
- Get-FileHash -Path: generates file hashes

## Scripting
- Scripting: the process of writing and executing commands in a text file to automate tasks
- Invoke-Command: runs commands on local and remote computers
