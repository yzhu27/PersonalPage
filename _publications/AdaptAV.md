---
title: "AdaptAV: Continuous Adaption of Vision Models for Autonomous Vehicles Using Cloud-based Oracle"
collection: publications
category: manuscripts
permalink: /publication/AdaptAV
excerpt: 'Deploying vision perception models in autonomous vehicles requires that we prioritize inference speeds, resulting in a model with shallower architectures and lesser model parameters (i.e., more pruned). Such small models do not generalize well, which could result in poor performance when encountered with novel scenarios. We propose a system that overcomes this by continuously retraining the vision models on the cloud with data uploaded by vehicles. We leverage the abundant compute resources, including machine learning accelerators, of the cloud to run a state-of-the-art, highly accurate oracle model that will guide the retraining process of the on-vehicle model. This newly trained model is transmitted to the vehicle over the network and is utilized by the vehicle for perceptions, leading to improved inference accuracy over time.'
date: 2024-10-7
venue: 'VTC 2024'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Yuheng Z., Dhruva U., Boluo G. & Man-Ki Y. (2024). AdaptAV: Continuous Adaption of Vision Models for Autonomous Vehicles Using Cloud-based Oracle. Proceedings of the 100th IEEE Vehicular Technology Conference, Oct. 2024'
---

Abstract:

Deploying vision perception models in autonomous vehicles requires that we prioritize inference speeds, resulting in a model with shallower architectures and lesser model parameters (i.e., more pruned). Such small models do not generalize well, which could result in poor performance when encountered with novel scenarios. We propose a system that overcomes this by continuously retraining the vision models on the cloud with data uploaded by vehicles. We leverage the abundant compute resources, including machine learning accelerators, of the cloud to run a state-of-the-art, highly accurate oracle model that will guide the retraining process of the on-vehicle model. This newly trained model is transmitted to the vehicle over the network and is utilized by the vehicle for perceptions, leading to improved inference accuracy over time.