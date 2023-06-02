# Signed Biodiversity Data Packages: A Method to Cite, Verify, Mobilize, and Future Proof, Large Image Corpora. hash://sha256/0154b9ddce4d2e280e627a08d1a2d42884201af6ac1ec19606e393deda57f4bb hash://md5/bae7f441cdd2648d2356b2330e4b71e8 https://doi.org/10.5281/zenodo.7998190

by 

Jorrit H. Poelen [orcid:0000-0003-3138-4118](https://orcid.org/0000-0003-3138-4118)

Ronin Institute

UC Santa Barbara Cheadle Center for Biodiversity and Ecological Restoration

Jason Best [orcid:0000-0002-7414-5523](https://orcid.org/0000-0002-7414-5523)

Botanical Research Institute of Texas

Please cite as:

Poelen, Jorrit H., & Best, Jason. (2023, June 2). Signed Biodiversity Data Packages: A Method to Cite, Verify, Mobilize, and Future Proof, Large Image Corpora. hash://sha256/0154b9ddce4d2e280e627a08d1a2d42884201af6ac1ec19606e393deda57f4bb hash://md5/bae7f441cdd2648d2356b2330e4b71e8. Zenodo. https://doi.org/10.5281/zenodo.7998190


## Abstract

Access to Natural History Collections helps researchers to better understand the natural world.
Millions of digital images of herbarium specimens are openly available via the Internet.
However, using these images in a data-intensive research project raises basic questions like:
"How do I efficiently access, and verify, hundreds of thousands of images?", and, "How do I cite
a version of a large image corpus?"

Here, we present a method to cite, verify and mobilize such image corpora across different
locations and medium types. We demonstrate our method with >100k images made available
through the Botanical Research Institute of Texas using available tools (e.g., rsync, Preston)
and technologies (e.g., internet, postal service). Our results show that our packaging method
allows the US Postal Service to transfer a packaged corpus at about 3 images/s, whereas
retrieving individual images via HTTP achieved a transfer rate of about 0.2 images/s.

Our results support that signed digital packaging of image corpora enables distributed storage
using readily available transfer and storage methods. In addition, our method is future proof
because they can be used with any digital media, including those that are not yet available.

## Recorded

<iframe src="https://player.vimeo.com/video/832006741?h=b572e446f1" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

## Content
included files are:

[Poelen_DD2023.mp4](./Poelen_DD2023.mp4) - recorded presentation (see also https://vimeo.com/832006741)

[Poelen_DD2023.pdf](./Poelen_DD2023.pdf) - presentation slides

[Poelen_DD2023.pptx](./Poelen_DD2023.pptx) - presentation slides (powerpoint) 

[Poelen_DD2023_Abstract.pdf](./Poelen_DD2023_Abstract.pdf) - presentation abstract. 

Part of:

Digital Data in Biodiversity Data Conference 2023 
@ Arizona State University 5-7 June 2023.


## Provenance

$ preston head
hash://sha256/0154b9ddce4d2e280e627a08d1a2d42884201af6ac1ec19606e393deda57f4bb

$ preston head | preston cat | md5sum | sed 's+^+hash://md5/+g' | cut -d ' ' -f1
hash://md5/bae7f441cdd2648d2356b2330e4b71e8

$ preston alias
<urn:preston:guoda:bio:Poelen_DD2023.pdf> <http://purl.org/pav/hasVersion> <hash://sha256/56e997ea728d9276d750c837820796536e86915ca56168f035023e9e254a1f1d> <urn:uuid:03d88005-cb81-4c89-a5a3-6a1c0d2b2b15> .
<urn:preston:guoda:bio:Poelen_DD2023.pptx> <http://purl.org/pav/hasVersion> <hash://sha256/77a0a28a66dcfb335cb4a636f7b2ae0910e911e7e090a8d2b77c44647f916d2d> <urn:uuid:f84952cb-7a08-4acb-8066-fc94e103c073> .
<urn:preston:guoda:bio:Poelen_DD2023.mp4> <http://purl.org/pav/hasVersion> <hash://sha256/085ce0a06692610606f90a7f8a3be79fe2b3d8d670f7b7ad6109600e0e6af05a> <urn:uuid:aac8ae03-0f4c-4db3-89d6-bee1843f5124> .
<urn:uuid:24509fda-cb15-4bf0-816a-52f8795ed9d0> <http://purl.org/pav/hasVersion> <hash://sha256/085ce0a06692610606f90a7f8a3be79fe2b3d8d670f7b7ad6109600e0e6af05a> <urn:uuid:4c326c81-dfa2-460e-a544-63cc3c1dc900> .
<https://docs.google.com/presentation/d/1EDp2PWdggttM0ZumuSED8MKEwQ_iKNgWZ4_wpFoqQaI/export/pptx> <http://purl.org/pav/hasVersion> <hash://sha256/77a0a28a66dcfb335cb4a636f7b2ae0910e911e7e090a8d2b77c44647f916d2d> <urn:uuid:1869c40a-367e-46b4-b23a-079c5dfbe0fd> .
<https://docs.google.com/presentation/d/1EDp2PWdggttM0ZumuSED8MKEwQ_iKNgWZ4_wpFoqQaI/export/pdf> <http://purl.org/pav/hasVersion> <hash://sha256/56e997ea728d9276d750c837820796536e86915ca56168f035023e9e254a1f1d> <urn:uuid:fdf921ad-3dfa-4720-a49d-f5f9f7f99b0f> .
<urn:preston:guoda:bio:Poelen_DD2023.mp4> <http://purl.org/pav/hasVersion> <hash://sha256/2a5ae6e43b324f7faee95f5bcaa25fcf2fc19a42b60bdcf880333dcb2e4cc77e> <urn:uuid:c21ff7b2-1932-4cf9-afcc-1e82900f4295> .
<urn:preston:guoda:bio:Poelen_DD2023.pdf> <http://purl.org/pav/hasVersion> <hash://sha256/c4c1602421ec450a61417123b29d13998451ea1df885add2de807cceb3dd1278> <urn:uuid:e1dd4e5a-56fb-4a53-9c44-12898deb0fdb> .
<urn:preston:guoda:bio:Poelen_DD2023_Abstract.pdf> <http://purl.org/pav/hasVersion> <hash://sha256/ec9d5f60c62994a0c5f512c0ce54f3e0faba08b70cae454022f0be6c8455e9b0> <urn:uuid:fbf0c0e4-ca25-49f1-87cf-14c0bff11960> .
<urn:preston:guoda:bio:Poelen_DD2023.pptx> <http://purl.org/pav/hasVersion> <hash://sha256/3b581c7123f742b4d806f4c56df798dbb46f927d9f55a496b26918329a7ca627> <urn:uuid:2cb0e901-5019-4058-b0b7-a8b216d2e6ad> .
<urn:uuid:a36b76d8-dc5c-490c-a4f0-4d71560922ab> <http://purl.org/pav/hasVersion> <hash://sha256/2a5ae6e43b324f7faee95f5bcaa25fcf2fc19a42b60bdcf880333dcb2e4cc77e> <urn:uuid:238049a1-c722-4511-9dac-085ba3effd92> .
<urn:uuid:0f12ad74-d270-43f2-824d-b8f445657346> <http://purl.org/pav/hasVersion> <hash://sha256/ec9d5f60c62994a0c5f512c0ce54f3e0faba08b70cae454022f0be6c8455e9b0> <urn:uuid:57abcd50-04a1-4681-a109-d357b74940ad> .
<https://docs.google.com/presentation/d/1EDp2PWdggttM0ZumuSED8MKEwQ_iKNgWZ4_wpFoqQaI/export/pptx> <http://purl.org/pav/hasVersion> <hash://sha256/3b581c7123f742b4d806f4c56df798dbb46f927d9f55a496b26918329a7ca627> <urn:uuid:05b6a358-3037-4d25-9fe1-9d56cee84647> .
<https://docs.google.com/presentation/d/1EDp2PWdggttM0ZumuSED8MKEwQ_iKNgWZ4_wpFoqQaI/export/pdf> <http://purl.org/pav/hasVersion> <hash://sha256/c4c1602421ec450a61417123b29d13998451ea1df885add2de807cceb3dd1278> <urn:uuid:e9b0717d-557a-404b-92af-eb3054969eeb> .


