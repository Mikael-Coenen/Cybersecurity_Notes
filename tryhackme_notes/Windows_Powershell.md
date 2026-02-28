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
