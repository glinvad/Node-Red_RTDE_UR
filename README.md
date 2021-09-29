# Node-Red_RTDE_UR
 A Node-red Dashboard for Universal Robots using RTDE

**Tested Node-red Version**
- 2.0.6

**Requied Node-red nodes:**
- node-red-contrib-bitunloader
- node-red-contrib-ur-robot
- node-red-dashboard
- node-red-contrib-ui-led
- node-red-contrib-ui-artless-gauge

**A overview of the Node-red Dashboard**
![Dashboard overview](https://github.com/glinvad/Node-Red_RTDE_UR/blob/main/Pictures/Dashboard.gif)

![UR polyscope](https://github.com/glinvad/Node-Red_RTDE_UR/blob/main/Pictures/URSim.gif)

**A overview of the Node-red flow**
![Flow overview](https://github.com/glinvad/Node-Red_RTDE_UR/blob/main/Pictures/Overview.jpg)


**How to setup**
For simpel testing, use URSim, an virtual mashine with the UR Polyscope software build in (It can be downloaded from Universal robots homepage).
If you are sitting on the same network as a UR robot (E-series or CB3 series) just connect to that.

REMEMBER TO CHANGE THE IP TO THE ROBOT OR SIMULATERE THAT HAVE RELEVANT DATA AVALIABLE

**How to import the code**
- Install Node-Red on your platform
- Install the Nodes
- Go to Import in the top corner 

![Import Node-red](https://github.com/glinvad/Node-Red_RTDE_UR/blob/main/Pictures/Import.jpg)
- Inset the code from the **Node-Red Code**
- Change the IP to your UR robot or URSim
- Have some fun with the data :)

**The Pop Up**
Just a bonus feature :)
![I am in control](https://github.com/glinvad/Node-Red_RTDE_UR/blob/main/Pictures/PopUp.jpg)

