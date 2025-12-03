# Lenapehoking

## Project Overview

**Lenapehoking** is an open-world preservation game built in **Unreal Engine 5.6** that immerses players in Lenape homelands at the time of Pontiac’s War (1763 Colonial America).

Developed in partnership with the **Delaware Tribe of Indians** and **Delaware Nation**, the project integrates tribal oral histories, historical landscapes, and 3D artifact scans into a living digital world.

-----

## 🎁 Cultural Co-Stewardship & Community Impact

Our goals are twofold:

1.  To create a public-facing interactive game that educates players about **Lenape history, resilience, and culture**.
2.  To deliver a full suite of assets, code, and documentation to both tribes for their sovereign use in education, exhibition, and cultural continuity projects.

The assets, environments, and interactive systems created for this project will be donated to the **Delaware Tribe of Indians** and **Delaware Nation**. This resource pack will include **3D scans, landscapes, oral history audio, and documentation** to support future 3D cultural projects, education, and community-led digital preservation efforts.

> 📰 **Featured Project:** Our unique approach to cultural preservation has been featured as part of **Princeton University's Social Entrepreneurship** focus articles and invited to present at Celebrate Princeton Innovation.
>
> *[Read the story here](https://kellercenter.princeton.edu/stories/reclaiming-narrative-cultural-storytelling-experience-gamers)*

-----

## ⚙️ Local Setup Guide

Due to the large file sizes common in Unreal Engine projects, this repository utilizes **Git Large File Storage (LFS)**. You **must** set up Git LFS before cloning the repository to successfully download all necessary game assets.

### 1\. Install Git LFS

Ensure you have Git installed, then install Git LFS on your system.

```bash
# Install Git LFS (on most systems)
git lfs install
```

### 2\. Clone the Repository

Clone the project repository to your local machine using the standard Git clone command. Git LFS will automatically handle the large files during this process.

```bash
git clone https://github.com/BoyagodaC/Lenape-Hoking
```


### 3\. Verify Git LFS Configuration

This project's `.gitattributes` file explicitly tracks several large file types using LFS. You can verify that LFS is correctly set up for these file types.

| File Extension | Description |
| :--- | :--- |
| `*.uasset` | Unreal Engine Asset Files (e.g., blueprints, materials) |
| `*.umap` | Unreal Engine Map/Level Files |
| `*.fbx` | 3D Model Files |
| `*.wav` | Audio Files |
| `*.mp4` | Video Files |
| `*.png` | Texture/Image Files |
| `*.tga` | Targa Image Files (often used for textures) |
| `*.dll` | Dynamic Link Libraries |
| `*.exe` | Executables |
| `*.lightmap.json` | Lightmap Data (often large) |
| `*.json` | Other JSON configuration data |

-----

## 🚀 How to Run the Project

1.  **Install Unreal Engine 5.6:** Ensure you have the correct version of the engine installed via the Epic Games Launcher.
2.  **Open the Project:** Navigate to the cloned local directory and double-click the main **`.uproject`** file (`Lenapehoking.uproject`).
3.  **Start Developing/Exploring\!** The project should open in the Unreal Engine editor 5.6.
