# Deep-Feature-preserving-Normal-Estimation-for-Point-Cloud-Filtering

Our source code is made available. 

Our code is implemented by Pytorch, and the detailed steps of running it are listed below:

Step1: Put the test point cloud in the floder "1_input_model", and rename it as "0_xxx.xyz". For example, "0_cube_05.xyz", where "0" represents the iteration number is zero, namely, the original point cloud.

Step2: Change the context in "name_total.txt". For example, "cube_05.xyz".

Step3: Run "main.py", where "3" in Line 30 of the code represents the number of iteration.

Step4: When the run is over, the filtering result of each iteration could be found in "4_output_model". And the result of last iteration is the final result of our method.

Note: Since our code needs to generate the height maps for all test points, please ensure that there is enough space to store them.


Please refer to our paper for more details.

@article{lu2020deep,
  title={Deep feature-preserving normal estimation for point cloud filtering},
  author={Lu, Dening and Lu, Xuequan and Sun, Yangxing and Wang, Jun},
  journal={Computer-Aided Design},
  pages={102860},
  year={2020},
  publisher={Elsevier}
}
