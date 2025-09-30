---
title:          "Towards Practical Clock Synchronization in the Solar System Internet"
date:           Jul. 2025
selected:       true
pub:            "IEEE Aerospace Conference"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Clock synchronization remains a notable gap in the Delay Tolerant Networking (DTN) suite of protocols. However, following the great theoretical advances in the area and a highly successful DTN experiment campaign on the International Space Station (ISS), a strong enough foundation has been laid to support a practical clock synchronization protocol and implementation for the Solar System Internet (SSI). In this paper we work with the theoretical developments along with the lessons-learned from the DTN experiments to drive a clock synchronization protocol and implementation for practical SSI network architectures, complete with code and simulation analyses. In addition to the recent technical and feature growth of DTN, network architectures have begun taking center stage. This was particularly true with the ISS experiments which operated over a multitude of DTN network boundaries (as well as project and programmatic boundaries), yielding operational experience with proper DTN network architectures. Taking this a step further, it is expected that future users in space will subscribe to multiple service providers, implying multiple network areas and boundaries. Such an architecture is central to the upcoming LunaNet, which notably has nodes that do not neighbor authoritative clock sources. After covering the basics of DTN, we recall the most germane aspects of clock synchronization for DTNs. This includes remarks on routing in DTNs, which is often schedule-based; we emphasize that this alone demonstrates how crucial clock synchronization is for scalability. The introduction continues with a discussion of the ISS experiment network architectures and its implications for this work. The key components have been implemented and applied to clock synchronization for a portion of NASA's DTN experiments network. The implementation is openly available and will be integrated into the High-rate DTN (HDTN) implementation. We then cover parameter optimization and the ramifications of choosing underlying equation solvers for convergence. Observations based on network architectures are used to explain the multiple implementation paths available in DTN and which one was chosen. We conclude with the analysis of a simulation based on the ISS network architecture and the future work thereby inspired.
cover:          /assets/images/covers/cover3.jpg
authors:
  - Alan Hylton
  - Oliver Chiriac
  - Jacob Cleveland
  - Jihun Hwang
  - Karuna Petwe
  - Tobias Timofeyev
links:
  Paper: https://doi.org/10.1109/AERO63441.2025.11068429
  # Code: https://github.com/TobiasTimofeyev/Spectral_Kuramoto
  # Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
