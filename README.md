# JSON 3D Model Viewer

A small tool designed for viewing custom models for minecraft resourse packs and models

### Installation and setup

##### **Release**
Pre-built releases can be downloaded for linux, windows and macOS on GitHub or the project an be run in the browser by cloning the repository and opening `src/index.html`

##### **Build from source**

(Requires, git and npm to be installed)

Clone the repository and enter the directory
```
git clone https://github.com/Rabbitminers/json-3d-model-viewer
cd json-3d-model-viewer
```
From here you can either build and install the application or run it in a browser opening `src/index.html` To build the appication run

```
npm install
npm run tauri build
```
This will install the necissary packages and then build the application to the correct format for your operating system


### Planned features
- Importable models & Textures while in the application
- Customisable Themes
- Screenshot functionality

### Known Issues
- "texture: "#missing" in json files is not currently supported and will prevent the object from being rendered