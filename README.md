# BuildAgentConfig
Stuff I want to install on my Build agents


Run this command to update the agent

`
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/arvesv/BuildAgentConfig/main/UpdateWIndowsBuildAgent.ps1'))
`