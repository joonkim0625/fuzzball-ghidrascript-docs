---
title: Installation
layout: default
nav_order: 2
---

# Installation

## Requirements

- **Operating System:** Ubuntu 20.04 or earlier
- **Hardware:** Recommended 8 GB of RAM
- **Software:** Software: Ghidra (The version these files were tested with is 10.3.3 2023-Aug-29 1442 EDT)

## Steps

1. Download the project files from the [Releases](https://github.com/joonkim0625/fuzzball-ghidrascript/releases/tag/v0.1.0) page.

2. Extract the downloaded archive to your preferred location.

3. Ensure that your system meets the specified requirements:
    - Make sure Ghidra is installed in your system.

4. Navigate to the extracted directory.

5. If the steps above are successfully, you will be able to see these files:

    ```bash
    fuzzball  fuzzball.py  z3
    ```

6. Based on the location of Ghidra installed path, you need to copy the script
   file `fuzzball.py` into the Ghidra Script Manager. For example, if you have
   installed `Ghidra` at the top of your home directory `~/`, the path where
   this script should be located is as follows:

   ```bash
   ~/<Path to Ghidra>/Ghidra/Features/Python/ghidra_script
   ```

7. If you have successfully moved the script into the Ghidra script folder, you
   will be able to see the script from Ghidra Script Manager. 

   ![menu-loc](../assets/ScriptManager-from-menu.png)

   You can launch `Ghidra Script Manager` by going to `Windows` and then select `Script Manager`.

   ![fuzzball-script-loc](../assets/FuzzBALL-script-location.png)


For more detailed information and usage instructions, refer to the [project documentation](https://joonkim0625.github.io/fuzzball-ghidrascript-docs/).

Feel free to reach out if you encounter any issues or have questions.

