# 3D Reconstruction Software of Tree Point Clouds 

## 3D Reconstruction of Tree Point Clouds

In the 3D tree reconstruction software based on ALS point clouds, after selecting the input point cloud data, users can set different parameter values in the parameter bar to control the growth angle of the trunk, the density of branches, the smoothness of branches, etc. Different colors can be selected for the trunk and leaves. The software comes with different leaf models for users to choose from, and by adjusting parameters, the tree model can be made more realistic. The following is a demonstration of the software usage process.

## Using steps
### Cloning the Repository
```
# HTTPS
git clone https://github.com/UMR19/TreeReconstruction.git 
```
### Demonstration video
https://github.com/UMR19/TreeReconstruction/assets/100742005/3951bb09-d177-448a-9cd5-53e8fb718868

**Step 1:** Click the `ALSTreeReconstruction.exe`, select the exported tree point cloud file after the Models section, and reconstruct the model. The software can control the pitch angle with `W`, `A` keys, the left and right rotation with `S`, `D` keys, the left and right tilt angle with `Q`, `E` keys, and zoom with `Z`, `X` keys.

![Figure 1: Selecting the tree point cloud to be reconstructed](./images/fig1.png)
<center><b>Figure 1</b> Selecting the tree point cloud to be reconstructed</center>

**Step 2:**

1. Set different parameter values in the red box in Figure 2 to control the growth of the trunk, and click Reconstruct tree to reconstruct the tree (Figure 2).

![Figure 2: Demonstration of the tree point cloud reconstruction process](./images/fig2.png)
<center><b>Figure 2</b> Demonstration of the tree point cloud reconstruction process</center>

2. In the Tree control column, manually adjust parameters such as the thickness of the branch model and the size and density of the leaves to make the model more realistic (Figure 3).

![Figure 3: Demonstration of tree point cloud reconstruction effect (adjusting branches and leaves parameters)](./images/fig3.png)
<center><b>Figure 3</b> Demonstration of tree point cloud reconstruction effect (adjusting branches and leaves parameters)</center>

3. In the Leaf models sub-column of Tree control, select different leaf models to give the reconstructed tree model different styles. Figure 4 shows the reconstruction effect corresponding to the maple leaf model.

![Figure 4: Demonstration of tree point cloud reconstruction effect (using maple leaf model)](./images/fig4.png)
<center><b>Figure 4</b> Demonstration of tree point cloud reconstruction effect (using maple leaf model)</center>
