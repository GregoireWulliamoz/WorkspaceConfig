Download and install nerd font: https://www.nerdfonts.com/font-downloads

Install oh my posh: https://ohmyposh.dev/
winget install JanDeDobbeleer.OhMyPosh -s winget
New-Item -Path $PROFILE -Type File -Force
Install the powershell profile

Install-Module -Name Terminal-Icons -Repository PSGallery
Install-Module z -AllowClobber