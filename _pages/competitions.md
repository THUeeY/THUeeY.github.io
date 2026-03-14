---
permalink: /competitions/
title: "Competitions"
author_profile: true
---

{% include base_path %}

## [2021 APTO Big Data Competition](https://tianchi.aliyun.com/competition/entrance/531929/information?lang=en-us)

<div class="competition-entry" markdown="1">

— *Prediction on DME Patients' Response to Anti-VEGF Treatment*
( [Paper](https://www.sciencedirect.com/science/article/pii/S1361841526000113) )

<div style="font-size: 1.25em;" markdown="1">
🎉🎉🎉 Led a team to secure **first place** among 10,000+ teams globally, winning an $8K prize.
{: .notice--success}
</div>
<h3 style="margin-top: 2em;">Project overview</h3>
<figure class="align-center" style="margin-top: 1.5em;">
  <img src="{{ base_path }}/images/aptos_project.png" alt="APTO project overview" style="max-width: 100%; width: 800px; height: auto; border-radius: 6px; box-shadow: 0 2px 12px rgba(0,0,0,0.08);">
</figure>
<figure class="align-center" style="margin-top: 1.5em;">
  <img src="{{ base_path }}/images/aptos-frame.png" alt="APTO frame" style="max-width: 100%; width: 800px; height: auto; border-radius: 6px; box-shadow: 0 2px 12px rgba(0,0,0,0.08);">
</figure>

Participated in the APTOS 2021 Big Data Competition on predicting treatment response of diabetic macular edema (DME) from optical coherence tomography (OCT) images. The competition provided a dataset containing tens of thousands of OCT scans from approximately 2,000 patients.

In our team, I worked on model design and training for several tasks including retinal biomarker detection (IRF, SRF, PED, HRF), central subfield thickness (CST) regression, and treatment continuation prediction. The pipeline used deep learning models to analyze OCT slices and aggregated predictions across scans. The system incorporated convolutional and transformer-based networks for feature extraction, data augmentation strategies for OCT images, and ensemble models to combine outputs from multiple subtasks together with patient metadata.

The final system predicted post-treatment biomarkers, visual acuity changes, and whether anti-VEGF injection should continue. The approach achieved an overall score of 0.744 in the final evaluation, ranking 1st among all participating teams in the competition. 

<h3 style="margin-top: 2em;">Award Certificate</h3>
<figure class="align-center">
  <a href="{{ base_path }}/images/aptos-certificate.jpg">
    <img src="{{ base_path }}/images/aptos-certificate.jpg" alt="APTO competition award certificate" style="max-width: 60%; width: 700px; height: auto; border-radius: 6px; box-shadow: 0 2px 12px rgba(0,0,0,0.08); border: 1px solid #eee;">
  </a>
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; color: #666;">First Place — 2021 APTO Big Data Competition</figcaption>
</figure>

</div>
