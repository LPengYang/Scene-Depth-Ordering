# Scene-Depth-Ordering
Single Image Dehazing Using Scene Depth Ordering. The revised version is published on [IEEE TITS](https://ieeexplore.ieee.org/document/11306239).


<hr />

> **Abstract:** *—The reliability of vision-based systems, such as traffic monitoring and intelligent driving, is typically compromised in hazy weather owing to diminished visibility. 
In this paper, we propose a novel efficient image dehazing framework guided by depth order, leveraging the consistency of depth perception to establish strong global constraints for enhanced haze removal. The consistent depth perception ensures that the regions that look farther or closer in hazy images also appear farther or closer in the corresponding dehazing results, substantially avoiding potential visual degradation. To this end, the depth order in hazy images is approximated by the reverse order of color difference between pixel values and global atmospheric light, offering an effective and efficient alternative for depth perception modeling. Subsequently, we have developed a depth order embedded transformation model to estimate the transmission maps jointly constrained by depth order and haze imaging model, ensuring that the depth order remains unchanged in corresponding dehazing results.  This model harnesses the extracted depth order as a powerful global constraint for the dehazing process, facilitating the efficient use of global information and thus achieving superior image restoration. Extensive experiments demonstrate that the proposed method can better recover potential structure and vivid color with higher computational efficiency, offering an efficient solution for robust traffic monitoring against hazy weather.* 
<hr />

## Demo

We have provided two versions of demos, i,e., the concise version (**Main_concise.mlx**) that only returns dehazing results for input hazy images, and the detailed version (**Main_demo.mlx**) that outputs all intermediate results with visualization. 

## Demonstration of Extracted Depth Order and Global Optimization

![image](https://github.com/LPengYang/Scene-Depth-Ordering/blob/main/Demonstration_figures/Observation.png) 

![image](https://github.com/LPengYang/Scene-Depth-Ordering/blob/main/Demonstration_figures/Global_optimization.png) 

## Citation
If you use our work, please consider citing:

    @ARTICLE{11306239,
      author={Ling, Pengyang and Chen, Huaian and Wang, Haoxuan and Gu, Yuxuan and Jin, Yi and Zheng, Jinjin and Chen, Enhong},
      journal={IEEE Transactions on Intelligent Transportation Systems}, 
      title={Efficient Haze Removal via Scene Depth Ordering for Robust Traffic Monitoring}, 
      year={2025},
      volume={},
      number={},
      pages={1-14},
      keywords={Image color analysis;Atmospheric modeling;Estimation;Image dehazing;Degradation;Monitoring;Scattering;Feature 
      extraction;Computational modeling;Computational complexity;Image dehazing;atmospheric scattering model;transmission estimation;visibility 
      improvement},
      doi={10.1109/TITS.2025.3642629}}


