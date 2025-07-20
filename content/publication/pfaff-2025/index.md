+++
title = "Scalable real2sim: Physics-aware asset generation via robotic pick-and-place setups"
date = 2025-03-01 # publication date
authors = ["Nicholas Pfaff","Evelyn Fu","Jeremy Binagia","Phillip Isola","Russ Tedrake"]
publication_types = ["3"]
abstract = "Simulating object dynamics from real-world perception shows great promise for digital twins and robotic manipulation but often demands labor-intensive measurements and expertise. We present a fully automated Real2Sim pipeline that generates simulation-ready assets for real-world objects through robotic interaction. Using only a robot's joint torque sensors and an external camera, the pipeline identifies visual geometry, collision geometry, and physical properties such as inertial parameters. Our approach introduces a general method for extracting high-quality, object-centric meshes from photometric reconstruction techniques (e.g., NeRF, Gaussian Splatting) by employing alpha-transparent training while explicitly distinguishing foreground occlusions from background subtraction. We validate the full pipeline through extensive experiments, demonstrating its effectiveness across diverse objects. By eliminating the need for manual intervention or environment modifications, our pipeline can be integrated directly into existing pick-and-place setups, enabling scalable and efficient dataset creation. Project page (with code and data): https://scalable-real2sim.github.io/."
featured = true
publication = "arXiv preprint arXiv:2503.00370"
tags = ["robotics", "simulation", "digital twins", "asset generation", "pick-and-place"]
url_pdf = "https://arxiv.org/abs/2503.00370"
# doi = "10.48550/arXiv.2503.00370"
+++
