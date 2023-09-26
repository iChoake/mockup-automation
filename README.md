📁 Photoshop Mockup Automation Setup

### 🌍 GitHub Repository
Create a repository named `photoshop-mockup-automation`.

### 📂 Directory Structure:

```
📁 photoshop-mockup-automation
│
├── 📁 scripts
│   └── 📜 Batch Mockup Smart Object Replacement.jsx
│
├── 📁 mockups
│   └── 📜 md-design.psd
│
├── 📁 output
│
├── 📁 gui (if you have one)
│   └── 📜 [your-gui-files]
│
└── 📜 setup.sh
```

- **📁 `scripts`**: Contains your Photoshop `.jsx` script(s).
  
- **📁 `mockups`**: Store your Photoshop `.psd` mockup files.
  
- **📁 `output`**: Where your script will save the results.
  
- **📜 `setup.sh`**: Script for setting up everything on a user's machine.
  
- **📁 `gui`** (Optional): For GUI-related files if you integrate a graphical user interface.


## Basic Setup - For the techFriendy to Use:
 --
1. Place your mockup PSD file in the `example/mockup` directory.
2. Place the design you want to insert into the smart object in the`example/input` directory.
3. Open Photoshop.
4. Run the `Batch Mockup Smart Object Replacement.jsx` script from Photoshop's script menu.
5. The script will replace the "md-design" smart object layer in your mockup with the design provided.
6. The result will be saved in the `output` directory.

Note: Always ensure that the smart object layer in your PSD mockup is named "md-design" for this script to work correctly.
