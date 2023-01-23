# Download Adobe Digital Editions
Invoke-WebRequest -Uri "https://www.adobe.com/go/edsp_win_install" -OutFile "AdobeDigitalEditions.exe"

# Install Adobe Digital Editions
Start-Process "AdobeDigitalEditions.exe" -ArgumentList "/S" -Wait

# Cleanup
Remove-Item "AdobeDigitalEditions.exe" -Force
