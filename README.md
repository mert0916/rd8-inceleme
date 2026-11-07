# RD-8 · Inspection

Interactive 3D inspection page for **RD-8**, an 8-joint quadruped robot dog.

- Model generated from the parametric CadQuery design (AKT-1 v7 planetary actuators, leg v5, body, power shelf, front grille, head).
- Walking replay recorded from the trained MuJoCo / MJX + PPO policy (50 Hz).
- Isolate assemblies, explode, section planes, x-ray, edges, leg kinematics, center of mass and support polygon, actuator load map, parts list.

Open `index.html` through any static web server (for example `python -m http.server`). Opening the file directly does not work because the page loads its model with `fetch`.

The page uses three.js 0.160 from a CDN. Files: `rd8_inceleme.glb` (quantized mesh, KHR_mesh_quantization), `rd8_inceleme.json` (parts, kinematics), `yuruyus.json` (walking replay).

© RD-8 project. All rights reserved.
