# SEM NERF

## modifying ngp for affine camera 

### 1. in src/nerf_loader.cu
line 238, add the Elensmode options
To activate the affine mode, add "affine": 1 into the 1st line of transforms.json

### 2 in src/common.h 
line 194, add Affine  into the enum class ELensmode
