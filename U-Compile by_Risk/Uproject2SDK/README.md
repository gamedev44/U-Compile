## Uproject2SDK

#### A Side project by: Risk

### Instructions for Using the Folder-to-Exe Editor SDK Maker Tool

---

#### Overview
This tool allows you to create a **self-contained executable** for the Unreal Editor tools associated with a game project. It requires **Unreal Engine to be installed** on the user’s system and uses the project’s `.uproject` file to create a packaged editor executable.

---

#### Steps to Use the Tool

1. **Add the Script to the Parent Folder**:
   - Download and place the `Uproject2SDK.exe` script in the **parent directory** of your main project folder (the folder that contains your entire Unreal project).

2. **Drag and Drop Your Project Folder**:
   - Drag and drop your **entire project folder** (the folder containing your `.uproject` file) onto the `Uproject2SDK.exe` script.

3. **Wait for the Script to Complete**:
   - The script will:
     - Detect the `.uproject` file inside the folder.
     - Use the `.uproject` file to create a self-contained `.exe` editor.
   - Once the process is complete, an executable will be created in the same directory as your project folder.

---

#### Requirements
1. **Unreal Engine Installed**:
   - Ensure that Unreal Engine is installed on the machine where this tool is being used.
   - The script relies on Unreal Engine to execute the `.uproject` file.

2. **Valid Project Folder**:
   - The folder you drag onto the script must contain a valid `.uproject` file.

---

#### Output
- The resulting executable (`.exe`) will:
  - Launch the Unreal Engine Editor for your project.
  - Allow sharing of the editor tools for game development with other team members or collaborators who also have Unreal Engine installed.

---

#### Example Usage
1. Place the script in a folder named `UnrealProjects`.
2. Drag a project folder like `MyAwesomeGame` (which contains `MyAwesomeGame.uproject`) onto the script.
3. The script creates an executable named `MyAwesomeGame.exe` in the `UnrealProjects` folder.
4. Running `MyAwesomeGame.exe` will open the Unreal Engine Editor for the project.

---

This tool simplifies sharing and accessing Unreal projects with editor capabilities for development and collaboration. Let me know if you need additional details or refinements! 🎮