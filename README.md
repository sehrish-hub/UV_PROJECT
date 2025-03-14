UV Project Setup (Short Version)

⿡ Create & Open Folder
mkdir UVProject && cd UVProject
code .

⿢ Initialize UV Project
uv init  # Creates the basic project structure

⿣ Run Python File
uv run hello.py  # Runs hello.py

⿤ Manage Packages
Add a package → uv add <package_name>
Remove a package → uv remove <package_name>

Note: UV is a package manager like pip, so these commands work similarly to:
pip install <package_name>
pip uninstall <package_name>