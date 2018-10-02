# ctftools1710
Ubuntu 17.10 Docker image with lots of ctf related tools.

(r2 was not installed as I was in a hurry and did not want to wait for its long build time)

## Installation
1. Install Docker: [Using chocolatey](https://stefanscherer.github.io/get-started-with-docker-on-windows-using-chocolatey/) is the most convenient way for me 
2. Run PowerShell as administrator and make sure `ExecutionPolicy` is set to `Unrestricted` or `Bypass` (run `Set-ExecutionPolicy Unrestricted`)
3. Build: `./build.ps1`

## Running it
Management: `.\start.ps1`, `.\stop.ps1`, `.\connect.ps1`
