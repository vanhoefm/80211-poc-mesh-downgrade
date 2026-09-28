This repository contains proof-of-concept code to support submissions made in the IEEE 802.11 TGmf Task Group regarding a downgrade issue in SAE when used in mesh networks.


## Code in this repository

- `hostap-gemini-mesh-downgrade-tests`: extended [hostap](https://w1.fi/cvs.html) implementation that supports SAE group negotiation in mesh networks. This was used to confirm the downgrade issues in practice.

- `old-chatgrp-h2e-mesh-support`: essentially an old initial version of the code in `hostap-gemini-mesh-downgrade-tests` that was generated using ChatGTP.

- `hostap-gemini-mesh-downgrade-tests-scalar-defense`: the defenses that were proposed in my submissions to the TGmf.


## Main submitted documents to IEEE 802.11 TGmf

- Presentation discussing the downgrade issue: [document 11-26/0789r1](https://mentor.ieee.org/802.11/dcn/26/11-26-0789-01-000m-sae-mesh-downgrade.pptx).

