---
title: "Scalable real2sim: Physics-aware asset generation via robotic pick-and-place setups"
summary: " "  # Add a page description. Space to avoid printing out contents.
tags:
date: "2025-03-01T00:00:00Z"

image:
  caption: "Objects are placed in the first bin, where the robot picks them up and reconstructs their geometries by moving them in front of a static camera while re-grasping to reduce occlusions. Next, the robot identifies the object's physical parameters by following a trajectory designed to be informative for the inertial parameters. Finally, it places the object into the second bin and repeats the process with the next object. The extracted geometric and physical parameters are combined to generate a complete, simulatable object description."
  focal_point: Smart
  preview_only: true

url_project: "https://scalable-real2sim.github.io/"
url_preprint: "https://arxiv.org/abs/2503.00370"
url_video: "https://www.youtube.com/watch?v=EdhKJsD5uew"
url_code: "https://github.com/nepfaff/scalable-real2sim"
url_dataset: "https://mitprod-my.sharepoint.com/personal/nepfaff_mit_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fnepfaff%5Fmit%5Fedu%2FDocuments%2Fscalable%5Freal2sim%5Fpublic%5Fbenchmark%5Fdataset&ga=1"

---

Obtaining both visually and physically accurate assets for physics-based simulation can be an expensive, labor-intensive process. In this work, we propose an automated Real2Sim pipeline that generates simulation-ready assets through routine pick-and-place operations. In particular, the robot's joint torque sensors are used to infer the inertia of the manipulated object while an external camera combined with photometric reconstruction techniques (e.g. NeRF, Gaussian Splatting) reconstructs the visual appearance (mesh) of the object. This pipeline offers a route to scalable and efficient asset generation for robotics simulations. 

<br/><br/>

## Publications
{{< cite page="/publication/pfaff-2025" view="2" >}}
