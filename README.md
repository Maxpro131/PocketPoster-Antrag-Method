# PocketPoster-Antrag-Method
This tutorial shows you how to get the app hash for PocketPoster without a PC/Mac. You can use this method until the owner of PocketPoster adds it natively.
<br>Create an issue, if you still need help

> [!NOTE]
> This method requires a pairing file. Generating a pairing file is a one-time process using a PC/Mac.
> 
> Since this method requires a PC/Mac <strong><i>before</i></strong> using it, I recommend it only to SideStore/StikDebug users

## IMPORTANT:
<strong>The symlinks exploit is patched on iOS 26.2b2/18.7.3 or higher</strong>, which means PocketPoster isn't able to apply any wallpapers on those versions

### Prerequisites
<li>A pairing file</li>
<li><a href=https://github.com/khcrysalis/Antrag/releases/latest/>Antrag</a> with the pairing file imported <br>(settings icon at the top right > Tunnel and Pairing > Import Pairing File)</li>
<li><a href=https://apps.apple.com/app/id6755608044>LocalDevVPN</a> enabled <br>(alternative: <a href=https://apps.apple.com/app/id6744045754>StikDebug's VPN</a>)</li>

## How to get the app hash
<details>
  <summary>Tutorial for iPhone/iPad wallpapers</summary>
  <ol>
    <strong>NOTE:</strong> PocketPoster isn't supported on <strong>iOS 26.2 beta 2 & iOS 18.7.3</strong> or higher. If you're on such version, use Nugget instead.
    <li>Go to the main menu of Antrag</li>
    <li>Switch to system</li>
    <img src="https://raw.githubusercontent.com/Maxpro131/PP-Antrag-Method/refs/heads/main/Resources/2.png">
    <li>Search for "PosterBoard" and tap on it</li>
    <img src="https://raw.githubusercontent.com/Maxpro131/PP-Antrag-Method/refs/heads/main/Resources/3.png">
    <li>Scroll down to "Container Path." Hold and copy it</li>
    <img src="https://raw.githubusercontent.com/Maxpro131/PP-Antrag-Method/refs/heads/main/Resources/4.png">
    <li>Go to the PocketPoster settings and paste the container path in the top text field</li>
    <img src="https://raw.githubusercontent.com/Maxpro131/PP-Antrag-Method/refs/heads/main/Resources/5.png">
    <li>Remove "/private/var/mobile/Containers/Data/Application/" so only a random string of letters and numbers is left. <br>(example:
/private/var/mobile/Containers/Data/Application/C0D26996-4AD5-426E-98C5-9A07FD77DBDC --> C0D26996-4AD5-426E-98C5-9A07FD77DBDC )</li>
  </ol>
</details>
<details>
  <summary>Tutorial for CarPlay wallpapers</summary>
  <ol>
    <strong>NOTE:</strong> CarPlay wallpapers aren't supported on iOS 26
    <li>Go to the main menu of Antrag</li>
    <li>Switch to system</li>
    <img src="https://raw.githubusercontent.com/Maxpro131/PP-Antrag-Method/refs/heads/main/Resources/2.png">
    <li>Search for "CarPlayWallpaper" and tap on it</li>
    <img src="https://raw.githubusercontent.com/Maxpro131/PP-Antrag-Method/refs/heads/main/Resources/6.png">
    <li>Scroll down to "Container Path." Hold and copy it</li>
    <img src="https://raw.githubusercontent.com/Maxpro131/PP-Antrag-Method/refs/heads/main/Resources/7.png">
    <li>Go to the PocketPoster settings and paste the container path in the bottom text field</li>
    <img src="https://raw.githubusercontent.com/Maxpro131/PP-Antrag-Method/refs/heads/main/Resources/8.png">
    <li>Remove "/private/var/mobile/Containers/Data/Application/" so only a random string of letters and numbers is left. <br>(example:
/private/var/mobile/Containers/Data/Application/10B2EB4E-DC15-4421-ACD2-203CC8D2C8A8 --> 10B2EB4E-DC15-4421-ACD2-203CC8D2C8A8 )</li>
  </ol>
</details
