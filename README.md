# Hwang Younghyun (황영현)

Machine-learning and scientific software, tested against known answers and independent recomputations.

I study astronomy at Yonsei University, with a second major in physics and a minor in mathematics. Each repository below states how it was tested, what it found and what it does not show.

Portfolio: https://astro-young.com
Email: dudgus4867@gmail.com

| Repository | What it is |
|---|---|
| [astra](https://github.com/hyh4867/astra) | Maps new buildings between two satellite images with a pretrained TinyCD model: F1 0.91 on 128 held-out LEVIR-CD image pairs, with separate tests under misalignment and blur. |
| [supernova-analyzer](https://github.com/hyh4867/supernova-analyzer) | SALT3 light-curve fits and residual analysis of the DES-Dovekie and Pantheon+ catalogues with their full covariance; the catalogue results were recomputed from the raw files by a separate script. |
| [lenslab](https://github.com/hyh4867/lenslab) | A thin-lens ray-shooting simulator for point-mass and SIS lenses, checked against analytic image solutions and an independent flux calculation. |
| [thermal-drone-detection](https://github.com/hyh4867/thermal-drone-detection) | Small-drone detection in thermal video: a fine-tuned Faster R-CNN compared with a training-free baseline and tested on a second public dataset. Full 4-epoch run: recall 84.9% on the Anti-UAV300 test set and 48.6% on the second dataset. |
| [radar-track-lab](https://github.com/hyh4867/radar-track-lab) | Tracks aircraft in simulated airport-radar detections with an EKF and global nearest-neighbour association, using real ADS-B trajectories as ground truth: 175 m position error per track against 528 m for a filter-free baseline, averaged over 20 Monte Carlo runs. |
| [progression-lab](https://github.com/hyh4867/progression-lab) | A browser-only chord-progression analyser: key, chord functions, harmonic tension, reharmonisations with a reason for each change, and playable guitar voicings. |
| [shift-sleep-planner](https://github.com/hyh4867/shift-sleep-planner) | A Korean-language phone web app that turns a shift roster into sleep, nap and caffeine-cutoff times, with every rule tagged by its published source. |

Built with AI coding agents (Claude, Codex); tests and verification by me.
