<p align="center">
  <img src="https://raw.githubusercontent.com/MahyarGarshasbi/Probabilistic-Flood-Mapping-with-Bayesian-Deep-Learning/main/Figures/FigM.png" width="850">
</p>

---

# Uncertainty-Aware Flood Inundation Mapping With a Bayesian Deep Learning Framework Using SAR Imagery

**Mahyar Garshasbi**, **Hosein Alizadeh**, **Barat Mojaradi**, **Motahareh Saadatpour**, and **Erfan Zarei**

*School of Civil Engineering, Iran University of Science and Technology, Tehran, Iran*

---

## Abstract

Climate change-induced extreme rainfall events are driving a rise in flood frequency, posing significant challenges that need to be addressed by decision-makers. To aid in this challenge, reliable, near-real-time flood extent maps are essential to facilitate disaster evaluation, emergency response, and rescue strategy development. Unlike hydrological models based on physical properties, which are often time-consuming and computationally expensive, the integration of satellite image processing with artificial intelligence (AI), namely deep learning methods, is effective in terms of efficiency and accuracy. This study proposes a Bayesian deep learning framework that generates probabilistic flood maps, assigning a probability of flooding to each pixel rather than a binary classification, enabling the quantification of uncertainty alongside the flood probability for each pixel. Our proposed model utilizes the VV and VH polarization modes of Sentinel-1 imagery, which is less susceptible to weather and sunlight variations. This enables our model to deliver rapid, reliable flood extent maps at a 10-m spatial resolution. Evaluated on a large-scale benchmark dataset of 11 diverse, global flood events, the results demonstrate the capability of our proposed model in flood detection with an overall accuracy of 95.87% and F1-score of 80.13%, with performing better compared to standard U-Net, which was trained similarly, in the majority of performance metrics. To test its generalization, the model was applied to the 2019 Golestan flood in northern Iran, where it maintained comparable performance on unseen data, achieving an overall accuracy of 92.5% and an F1-score of 81.0%. Furthermore, given its probabilistic nature, the uncertainty associated with Synthetic Aperture Radar-based flood mapping was quantified across various land-cover types.

---

## Citation

```bibtex
@article{garshasbi2025uncertainty,
  title={Uncertainty-Aware Flood Inundation Mapping With a Bayesian Deep Learning Framework Using SAR Imagery},
  author={Garshasbi, Mahyar and Alizadeh, Hosein and Mojaradi, Barat and Saadatpour, Motahareh and Zarei, Erfan},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  volume={18},
  pages={26716--26726},
  year={2025},
  publisher={IEEE},
  doi={10.1109/JSTARS.2025.3610403}
}
```

---

## Contact

📧 garsh011@umn.edu
