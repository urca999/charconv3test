# charconv3

charconv3 is a Windows-only Python CLI tool that runs Blender headless and imports GHWTDE character assets to export them as GLB files.

## Setup

1. Install Blender.
2. Ensure NxTools is available.
3. Clone the repository.
4. Install the required packages using `pip install -r requirements.txt`.

## Usage

Run the command:  
`python -m charconv3.cli ghwtde2glb --blender-exe <path_to_blender> --nxtools-zip <path_to_nxtools_zip> --gh-character-dir <path_to_character_directory> --output-glb <output_path>`: