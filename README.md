# Thorlabs-GVS
Driving Thorlabs-GVS Galvo Mirror Systems using nidaqmx Package in the Python
- Prerequisite Hardware: DAQ Card, Galvanometer Systems(eg. GVS202), Power Supply
- Develop Environment: Pycharm
---

Step 1. Configure Galvo Scanning Systems Referencing to the Pin Diagrams and Manual
- Pin Diagram: https://www.thorlabs.com/newgrouppage9.cfm?objectgroup_ID=3770
- Manual: https://www.thorlabs.com/drawings/e0a5f507a7d4cd7a-F52E8901-D119-7212-21E5CEFDE15E6A4E/GVS202-Manual.pdf

Step 2. Clone this Repository
- git clone https://github.com/kshvieworks/Thorlabs-GVS.git

Step 3. Configure venv in the python Directory. Tree Structure is like Below. 
- Thorlabs-GVS
    - python
      - venv

Step 4. Install Required Python Packages.
- ```nidaqmx``` ```PyQt6``` ```opencv-python``` ```numpy```

Step 5. Run LaserScanning.py and Check the Operation.