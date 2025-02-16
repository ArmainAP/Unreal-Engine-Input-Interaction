# Unreal Engine Input Interaction

Welcome to the **Unreal Engine Input Interaction** plugin, a powerful tool designed to simplify and enhance interaction systems in your game. With built-in **Interactable & Interactor Components**, this plugin streamlines detecting, filtering, and handling interactions efficiently.

## Features

### 🗂 **DataAsset-Based Customization**
- Define and customize **interactable data** via **DataAssets** for a structured and scalable approach.
- Modify interaction settings dynamically without altering blueprints or code.

### 🎯 **Advanced Interaction Detection**
- **Camera Proximity-Based Detection**: Detect interactable objects based on the player's view.
- **Character Proximity-Based Detection**: Enable interactions only when players are within a defined distance.
- **Automatic Obstruction Handling**: Prevent interactions when obstacles block the line of sight.

### ⌨️ **Enhanced Input Integration**
- Uses **Enhanced Input System** for precise key filtering.
- Supports **tap-to-interact** and **hold-to-interact** mechanics.
- Configurable **interaction duration** and **delay time** between consecutive interactions.

## How It Works

### **Core Components**
- **Interactor Component**: Attach this to player characters or other entities that trigger interactions.
- **Interactable Component**: Attach this to objects that players can interact with.
- **Interactable DataAsset**: Define interaction settings such as input type, detection range, and timing.

### **Interaction Workflow**
1. The **Interactor Component** scans for nearby interactables.
2. The system evaluates:
   - Player **proximity** (camera or character distance).
   - **Line-of-sight** for obstruction handling.
   - Input **filters** (tap, hold, specific key bindings).
3. If all conditions are met, the interaction event triggers.

## Setup Instructions

1. **Install the Plugin**:
   - Copy the plugin to your Unreal Engine project’s `Plugins` folder.
   - Enable the plugin in the **Edit > Plugins** menu.

2. **Configure Interactables**:
   - Create a **DataAsset** using the provided Interactable Data template.
   - Set up interaction parameters such as detection mode, input settings, and timing.

3. **Attach Components**:
   - Add the **Interactor Component** to your player character or interaction handler.
   - Attach the **Interactable Component** to objects that should respond to interactions.

4. **Customize and Test**:
   - Adjust detection settings for different gameplay needs.
   - Playtest to fine-tune proximity, input filters, and interaction responsiveness.

## Contributing

We welcome contributions! If you have a feature request, bug report, or want to enhance the plugin, feel free to open an issue or submit a pull request.

## License

This project is released under the AGPL-3.0 license.

If you need a different license or have questions related to licensing, please contact **adrian.popoviciu@katcodelabs.com**.

## Credits

Created by **Adrian-Marian Popoviciu**. Special thanks to the Unreal Engine community for their valuable feedback and contributions.
