---
title: "Scalable real2sim: Physics-aware asset generation via robotic pick-and-place setups"
summary: ""
tags:
- Robotics
- Simulation
- Digital Twins
- Asset Generation
- Pick-and-Place
- Research
- Publication
- arXiv
- Mesh Reconstruction
- 3D Reconstruction
date: "2025-03-01T00:00:00Z"

image:
  caption: "Scalable real2sim: Physics-aware asset generation via robotic pick-and-place setups."
  focal_point: Smart

url_project: "https://scalable-real2sim.github.io/"
url_preprint: "https://arxiv.org/abs/2503.00370"
url_video: "https://www.youtube.com/watch?v=EdhKJsD5uew"
url_code: "https://github.com/nepfaff/scalable-real2sim"
url_dataset: "https://mitprod-my.sharepoint.com/personal/nepfaff_mit_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fnepfaff%5Fmit%5Fedu%2FDocuments%2Fscalable%5Freal2sim%5Fpublic%5Fbenchmark%5Fdataset&ga=1"

---
Simulating object dynamics from real-world perception shows great promise for digital twins and robotic manipulation but often demands labor-intensive measurements and expertise. We present a fully automated Real2Sim pipeline that generates simulation-ready assets for real-world objects through robotic interaction. Using only a robot's joint torque sensors and an external camera, the pipeline identifies visual geometry, collision geometry, and physical properties such as inertial parameters. Our approach introduces a general method for extracting high-quality, object-centric meshes from photometric reconstruction techniques (e.g., NeRF, Gaussian Splatting) by employing alpha-transparent training while explicitly distinguishing foreground occlusions from background subtraction. We validate the full pipeline through extensive experiments, demonstrating its effectiveness across diverse objects. By eliminating the need for manual intervention or environment modifications, our pipeline can be integrated directly into existing pick-and-place setups, enabling scalable and efficient dataset creation. Project page (with code and data): https://scalable-real2sim.github.io/.

<br/><br/>

## Publications
{{< cite page="/publication/pfaff-2025" view="2" >}}
