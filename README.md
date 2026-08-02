# impressao_digital
## Repository Organization

Each folder in this repository corresponds to a single crystal structure and contains all files generated from its analysis.

The contents of each folder include:

* **`.eps` and `.png` files:** Fingerprint plots for all intermolecular contacts identified in the corresponding crystal structure.
* **`.cif` file:** The crystallographic information file used as the input for the analysis.
* **`<structure_name>.txt`:** A summary file containing the main information extracted from the corresponding `.cif` file, allowing quick identification of the analyzed structure without opening the crystallographic file.
* **`intermolecular_contacts_identified_<structure_name>.cif.txt`:** A text file listing all identified intermolecular contacts together with the percentage contribution of each contact to the Hirshfeld fingerprint.

In addition to the individual folders, the repository contains a file named **`Summary of All Folders.txt`** in the root directory. This file compiles the percentage contributions of the intermolecular contacts from every analyzed structure, providing a convenient overview of the complete dataset without the need to inspect each folder individually.

