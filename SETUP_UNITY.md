# Unity Installation Guide

## Prerequisites
- **Unity Hub**: Install Unity Hub to manage your Unity installations.
- **Unity Editor**: Download and install the recommended version of Unity Editor via Unity Hub.
- **Visual Studio** (or any preferred IDE): Install Visual Studio during the Unity installation for script editing support.

## Project Cloning
1. Open a command line interface or terminal.
2. Navigate to the directory where you want to clone the project.
3. Run the following command:
   ```
   git clone https://github.com/jasonvirtual2-cell/minecraft-mini.git
   ```
4. Navigate to the project directory:
   ```
   cd minecraft-mini
   ```

## Scene Creation
1. Open Unity Hub and click on **Add** to add the cloned project.
2. Once the project loads in the Unity Editor, go to the **Hierarchy** panel.
3. Right-click in the panel, then select **Create > Scene**.
4. Name your scene appropriately, like `MainScene`.

## Prefab Creation
1. Select any Game Object from the **Hierarchy** you want to make into a prefab.
2. Drag the Game Object to the **Project** panel's `Assets` directory.
3. This creates a prefab that can be reused throughout your scenes.

## Controls
- **WASD**: Move your character.
- **Mouse**: Look around.
- **Space**: Jump.
- **Left Click**: Interact with objects.

## Troubleshooting
- **Unity won’t start**: Ensure all prerequisites are installed and up-to-date.
- **Missing assets**: Check the `Assets` folder for any missing files or red tags.
- **Game crashes**: Verify your Unity version is compatible with the project and check the Console for errors.

---