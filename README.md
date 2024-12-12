# Scene-Depth-Ordering
Single Image Dehazing Using Scene Depth Ordering

<hr />

> **Abstract:** *—Single image dehazing is a classical but still challenging image restoration task. This difficulty stems from its internal ill-posed nature, which potentially raises visual degradation in dehazing results such as noisy amplification and color distortion.
In this paper, we propose a novel single image dehazing framework guided by depth order, leveraging the consistency of depth perception to establish strong global constraints for enhanced haze removal. The consistent depth perception ensures that the regions that look farther or closer in hazy images also appear farther or closer in the corresponding dehazing results, substantially avoiding potential visual degradation. To this end, the depth order in hazy images is approximated by the reverse order of color difference between pixel values and global atmospheric light, offering an effective and efficient alternative for depth perception modeling. Subsequently, we have developed a depth order embedded transformation model to estimate the transmission maps jointly constrained by depth order and haze imaging model, ensuring that the depth order remains unchanged in corresponding dehazing results.  This model harnesses the extracted depth order as a powerful global constraint for the dehazing process, facilitating the efficient use of global information and thus achieving superior image restoration. Extensive experiments demonstrate that the proposed method can better recover potential structure and vivid color with higher computational efficiency than the state-of-the-art dehazing methods.* 
<hr />

## Demo

We have provided two version of demos, i,e., the concise verison (**Main_concise.mlx**) that only returns dehazing results for input hazy images, and the detailed verison (**Main_demo.mlx**) that outputs all intermidiate results with visualization. 

## Demonstration of Extracted Depth Order and Global Optimization

![image](https://github.com/LPengYang/Scene-Depth-Ordering/blob/main/Demonstration_figures/Observation.png) 

![image](https://github.com/LPengYang/Scene-Depth-Ordering/blob/main/Demonstration_figures/Global_optimization.png) 


