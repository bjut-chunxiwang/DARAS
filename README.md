 DARAS: Dynamic Audio-Room Acoustic Synthesis for Blind Room Impulse Response Estimation

📜 Abstract

Room Impulse Responses (RIRs) accurately characterize acoustic properties of indoor environments and play a crucial role in applications such as speech enhancement, speech recognition, and audio rendering in augmented reality (AR) and virtual reality (VR). Existing blind estimation methods struggle to achieve practical accuracy. To overcome this challenge, we propose the dynamic audio-room acoustic synthesis (DARAS) model, a novel deep learning framework that is explicitly designed for blind RIR estimation from monaural reverberant speech signals. First, a dedicated deep audio encoder effectively extracts relevant nonlinear latent space features. Second, the Mamba-based self-supervised blind room parameter estimation (MASS-BRPE) module, utilizing the efficient Mamba state space model (SSM), accurately estimates key room acoustic parameters and features. Third, the system incorporates a hybrid-path cross-attention feature fusion module, enhancing deep integration between audio and room acoustic features. Finally, our proposed dynamic acoustic tuning (DAT) decoder adaptively segments early reflections and late reverberation to improve the realism of synthesized RIRs. Experimental results, including a MUSHRA-based subjective listening study, demonstrate that DARAS substantially outperforms existing baseline models, providing a robust and effective solution for practical blind RIR estimation in real-world acoustic environments.

DARAS
 Overview of the DARAS Blind RIR Estimation Model. This figure illustrates the proposed DARAS model designed to estimate RIR from
 monaural reverberant speech. The model comprises four modules: (1) a Deep Audio Encoder extracting nonlinear features from reverberant speech; (2) the MASS-BRPEmodule, employing state space models (SSMs) to estimate room acoustic parameters and features; (3) a Hybrid-Path Cross-attention Feature
 Fusion module, dynamically guiding audio features integration with room acoustic features to achieve refined reverberation-aware representations; and (4) a DAT Decoder, adaptively segmenting RIR into early reflections and
 late reverberation stages based on the boundary point (Bp) estimated by the MASS-BRPE module, synthesizing each stage individually.

<img width="3012" height="1519" alt="OD" src="https://github.com/user-attachments/assets/7d15853d-332b-44dc-861a-efc6a0105cef" />

