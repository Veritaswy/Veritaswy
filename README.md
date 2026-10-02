<div align="center">

# Yuxuan Zhang

**张宇轩**

Undergraduate in Computer Science and Technology<br>
School of Artificial Intelligence, China University of Mining and Technology, Beijing

[zhangyuxuan@student.cumtb.edu.cn](mailto:zhangyuxuan@student.cumtb.edu.cn)

*Robot exploration when the robot has to come back, and vision in scenes where color is a poor guide.*

</div>

## News

- **Oct 2026.** Technical report on arXiv: [OpenSpace Lab Solution to the IROS 2026 Indoor Exploration Competition](https://arxiv.org/abs/2610.01505). **1st** on the Single-Robot Public Track. **3rd** on both Private Tracks.
- **2025.** Survey on sequential prediction for crop growth and yield, under review at *Computers and Electronics in Agriculture*.
- **2025.** First Prize, Beijing site, Contemporary Undergraduate Mathematical Contest in Modeling. Second Prize, inaugural Beijing College Students' "AI+" Innovation Competition.

## Publications

**OpenSpace Lab Solution to the IROS 2026 Indoor Exploration Competition**

**Yuxuan Zhang**, Dong Li, Zezhou Sun, Yuxuan Xu, Siyu Teng, Yuchen Li, Jianjian Yang, Long Chen

*arXiv:2610.01505*, 2026. &nbsp; [pdf](https://arxiv.org/pdf/2610.01505) · [abs](https://arxiv.org/abs/2610.01505) · [project](https://github.com/Veritaswy/Indoor-Exploration-Challenge)

The single-robot planner ranks unexplored regions with a pretrained map-completion model, and keeps the cost of returning to the base inside every decision. The multi-robot system scores targets by information gain, travel, and a shared step budget, and uses the shared map plus teammate intent to avoid searching the same space twice.

| Track | Rank | Coverage |
| --- | ---: | ---: |
| Single-Robot Public | 1 / 5 | 61.04% |
| Single-Robot Private | 3 / 10 | 39.53% |
| Multi-Robot Private | 3 / 10 | 39.91% |

On the large public maps the margin over second place was 3.53 points (49.81% vs. 46.28%). Inside the private benchmark, the same system placed 1st on the medium-scale single-robot maps (42.53%). A full-length paper is in preparation. Code will be released with that manuscript.

**A Review of Sequential Prediction Methods for Crop Growth and Yield: Advances in Machine Learning and Deep Learning Approaches**

Third author. *Computers and Electronics in Agriculture*, under review.

A survey of machine-learning and deep-learning models for sequential crop growth and yield prediction: what recent models take as input, what they predict, and how they are compared. I wrote the abstract and the introduction, with Prof. Zhenbo Li's group at China Agricultural University.

## Research

- **Exploration with a return constraint.** The map counts only if the robot gets back into communication range and uploads it before the step budget runs out.
- **Multi-robot coordination.** A shared map and shared intent, so a team does not spend its budget twice on the same room.
- **Perception when color fails.** Semantic segmentation in low light, on look-alike surfaces, and on small targets. Current project: RGB-D segmentation for underground mines, on the MUSeg dataset.

## Experience

**OpenSpace Lab** · 2026

First author of the IROS 2026 indoor exploration report. The team spans China University of Mining and Technology, Beijing, the Institute of Automation at the Chinese Academy of Sciences, Macau University of Science and Technology, Mohamed bin Zayed University of Artificial Intelligence, Shenzhen University, and the Technical University of Munich.

**China Agricultural University** · Nov 2024 – Sep 2025

Prof. Zhenbo Li's group, College of Information and Electrical Engineering. Third author of the crop-prediction survey now under review.

**Multimodal semantic segmentation for underground mines** · May 2025 – present

Undergraduate project at CUMTB. Reproduced published segmentation models on MUSeg, then started extending SegFormer from RGB to RGB-D for dark scenes and surfaces that color cannot separate.

## Education

**B.Eng. Computer Science and Technology**, 2024 – 2028 (expected)

School of Artificial Intelligence, China University of Mining and Technology, Beijing

## Awards

- **1st place**, Single-Robot Public Track, IROS 2026 Indoor Exploration Competition (OpenSpace Lab)
- **3rd place**, Single-Robot Private Track and Multi-Robot Private Track, IROS 2026
- **First Prize**, Beijing site, undergraduate division, 2025 Contemporary Undergraduate Mathematical Contest in Modeling (高教社杯)
- **Second Prize**, inaugural Beijing College Students' "AI+" Innovation Competition, industry–intelligence application track (team 科创算力天团)
- **Third Prize**, 16th Chinese Mathematics Competitions, non-mathematics group A
- **Third Prize**, 16th Lanqiao Cup, Beijing regional, Python, university group A
