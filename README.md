# Hierarchical Image Segmentation Based on Nonsymmetry and Anti-packing Pattern Representation Model

## Description
> These are the source codes for the paper **Hierarchical Image Segmentation Based on Nonsymmetry and Anti-packing Pattern Representation Model**. If you find this code useful, please kindly cite the paper as following:
> 
[1] Yunping Zheng, Bowen Yang, and Mudar Sarem, "Hierarchical Image Segmentation Based on Nonsymmetry and Anti-packing Pattern Representation Model," IEEE Transaction on Image Processing, 2021.

Code Author : Bowen Yang   
Date : 01/13/2021

## Requirement

+ Linux
  + OpenCV 4.0.0
  + Matlab R2015b
  + Cmake  (3.15 at  least)
+ Windows
  + OpenCV 4.0.0
  + Matlab R2015b
  + Microsoft Visual Studio 2017

## Usage

+ Linux

  + Step 1

    	Modify `CmakeLists.txt`

  + Step 2

    	Run these commands to compile the files.

    	`cmake -DCMAKE_BUILD_TYPE=Release .`

    	`make -j4`

  + Step 3

    	Run demo for a single file

    	`# program imagePath mode(0: Only label 1: Output images and label) saveHir(Number of saved images)`

    	`./run_demo ./1.jpg 1 60`

    	Run demo for a sample dataset

    	`# program inputDirectory outputDirectory mode saveHir`

    	`./run_dataset ../BSDS500/images ../BSDS500/precomputedResults 0 60`

+ Windows

  + Step 1

    	Create a VS project.

  + Step 2

    	Modify `NAMLabReleasex64.props`  and `NAMLabDebugx64.props`, and then add them to this project.

  + Step 3

    	Run demo and run dataset on Release X64 version.

## Contact

Yunping Zheng

<zhengyp@scut.edu.cn>
