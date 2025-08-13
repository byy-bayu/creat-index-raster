# create-index-raster

---

## How to Install a QGIS Plugin from a ZIP File

Follow these steps to install a QGIS plugin from a `.zip` file:

### **1. Prepare the ZIP file**

* Ensure the `.zip` file contains a valid QGIS plugin (commonly downloaded from GitHub or the official QGIS repository).
* Do **not** extract the file — QGIS can install it directly from the `.zip`.

---

### **2. Open QGIS**

* Launch **QGIS Desktop** (use the version compatible with your plugin).

---

### **3. Open the Plugin Installation Menu**

1. Go to **Plugins → Manage and Install Plugins...**
2. In the dialog window, select the **Install from ZIP** tab.

---

### **4. Select the ZIP File**

1. Click **Browse...** and locate your `.zip` file.
2. Click **Install Plugin**.

---

### **5. Activate the Plugin**

* Once installed, find it in the **Installed** tab.
* Make sure the checkbox next to the plugin name is enabled.

---

### **Troubleshooting**

If you see an "Invalid Plugin" error, check:

* The ZIP’s internal structure — the root folder should contain files like:

  ```
  __init__.py
  metadata.txt
  resources.qrc
  plugin_name.py
  ```
* The plugin is compatible with your QGIS version.
* All required Python dependencies are installed.

---

