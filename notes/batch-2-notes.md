# Research Batch 2 Notes

## Source 1: https://nhsjs.com/2024/how-do-quantum-and-photonic-deep-learning-platforms-compare-to-current-gpu-hardware/
**Title**: How Do Quantum and Photonic Deep Learning Platforms Compare to Current GPU Hardware?
**Author/Publisher**: Aarav Dudhia / NHSJS (National High School Journal of Science), nhsjs.com
**Date**: November 8, 2024
**Status**: FETCHED
**Key Claims**:
- Photonic end-to-end classification speed: 570 picoseconds (high-speed photonic chip).
- Light traversal time through nanophotonic circuit: 31 picoseconds.
- Photonic energy consumption: 2.1375 nanojoules (high-speed system); 9.32 nanojoules (low-speed system).
- Classical GPU energy consumption benchmark: 153,580 joules.
- Hybrid quantum execution time: greater than 30 hours; quantum energy consumption greater than 32.4 megajoules.
- Two-class photonic image classification accuracy: 93.8%; four-class: 89.8%.
- Python Keras four-class benchmark accuracy: 96%.
- ONN vowel recognition accuracy: 76.7% (138/180); CPU baseline 91.7% (165/180).
- Photonic chip length approximately 1.6 mm; silicon waveguide refractive index 4; phase modulator power approximately 10 mW per modulator.
- Photonic-to-electrical conversion latency: 10 picoseconds at 100 GHz bandwidth.
- Linear transformations in ONNs occur at rates greater than 100 GHz.
- NVIDIA Blackwell single-core memory bandwidth 8 TB/s; 8-core aggregate 64 TB/s. Intel Core X-Series theoretical bandwidth 0.094 TB/s.
- Quantum CX decomposition speedup O(n^1.75) vs classical O(n^2).
- Classical GPU training time: 2,194 seconds at 70 watts; photonic power 3.75 W (high-speed) or 2 W (low-speed); hybrid quantum estimated 300 W.
- Figures of Merit (FoM): classical GPU 81.5; photonic 2-class 43.8; photonic 4-class high-speed 64.8; photonic low-speed 51.7; quantum hybrid 46.3.
- CIFAR10 dataset: 60,000 images, 10 classes (5,000 train, 1,000 test per class). CIFAR100: 60,000 images, 100 classes, 20 superclasses (500 train, 100 test per class).
- Quantum circuits used 4 qubits (CIFAR10) and 7 qubits (CIFAR100).
- Two-class dataset: 216 letters per iteration; four-class: 432 letters per iteration.
- Moore's Law: transistor doubling every 2 years.
**Named Entities**: NVIDIA Blackwell (HGX B200, B100), NVIDIA Tensor Cores, CUDA, Intel Core X-Series, PIN attenuators, SiGe photodiodes, micro-ring modulators (MRM), grating couplers, beamsplitters, optical attenuators, phase shifters, saturable absorption, PyTorch, Qiskit, Keras, Microsoft Azure. Researchers cited: Shen Y, Harris NC, Skirlo S, Prabhu M, Baehr-Jones T, Hochberg M, Sun X, Zhao S, Larochelle H, Englund D, Soljacic M; Ashtiani F, Geers AJ, Aflatouni F; Trochun Y, Stirenko S, Rokovyi O, Alienin E, Pavlov E, Gordienko Y; Bermejo P, Orus R; Bourassa JE et al.
**Direct Quotes**:
- "Photonic processing allows for high bandwidths as optical signals are no longer limited by parasitic capacitances and resistance, therefore making PDNNs (photonic deep neural networks) a strong candidate for quick and energy-efficient processors (as quick as 570 picoseconds)."
- "optical signal processing is determined by how quickly light can propagate through the system, which is typically close to the speed of light."
- "linear transformations can occur at a rate of more than 100 GHz, and the ONN relies mainly on matrix multiplication."
- "Power consumption can be near zero in regard to calculating matrices, similar to how a simple lens can execute a Fourier transform without any use of power."
- "there is the problem of photon loss, which is when photons scatter and fail to reach their destination."
- "integrating a large number of optical components, such as beam splitters, modulators, and detectors, into a single photonic circuit is still a significant challenge."
- "noise and crosstalk will always remain in photonic systems, reducing accuracy."
**Notes**: Cited studies include Shen et al. 2017 (Nature, "Deep learning with coherent nanophotonic circuits"); Ashtiani et al. 2022 (Nature, "An on-chip photonic deep neural network for image classification"); Trochun et al. 2021 (IEEE); Bermejo and Orus 2023 (Scientific Reports); Bourassa et al. 2021 (Quantum, "Blueprint for a scalable photonic fault-tolerant quantum computer").

## Source 2: https://www.weforum.org/stories/2025/08/photonic-computing-promise-commercialization/
**Title**: N/A
**Author/Publisher**: World Economic Forum (weforum.org)
**Date**: N/A
**Status**: FAILED (HTTP 403 Forbidden on initial fetch and one retry)
**Key Claims**: N/A
**Named Entities**: N/A
**Direct Quotes**: N/A
**Notes**: The site blocked the WebFetch request with a 403 status code. Retried once per rules; same result. Suggest manual retrieval or archived copy via web.archive.org if needed for paper.

## Source 3: https://www.sciencedirect.com/science/article/abs/pii/S0030402610003360
**Title**: Alternating approach of implementing frequency encoded all-optical logic gates and flip-flop using semiconductor optical amplifier
**Author/Publisher**: Soma Dutta, Sourangshu Mukhopadhyay / Optik (Elsevier), ScienceDirect
**Date**: June 2011 (Volume 122, Issue 12, Pages 1088-1094). DOI: 10.1016/j.ijleo.2010.06.046
**Status**: FETCHED (abstract only, as article is paywalled)
**Key Claims**:
- Pump beam power range: 2 to 4 dB.
- Probe beam energy range: -4 to -2 dB.
- Input wavelengths: 1555 nm and 1550 nm (frequencies nu1 and nu2).
- C band frequency range cited: 1536 to 1570 nm.
- Processing speed target: far above GHz range.
**Named Entities**: Semiconductor Optical Amplifier (SOA), GaAs, Fabry-Perot SOA (FP-SOA), Traveling Wave SOA (TW-SOA), Reflecting SOA (RSOA), ADD/DROP multiplexers, wavelength converters. Referenced researchers: SK Garai et al., JM Jeong et al., LQ Guo et al., Y Ichioka et al., BK Jenkins et al., TA Ibrahim et al.
**Direct Quotes**:
- "frequency of light remains unaltered after refection, refraction, absorption, etc. during the transmission of light."
- "photon is found to be a very suitable information carrier than electron not only in the connection of super fast speed."
- "coded information (0, 1) in a signal remains unchanged in refraction, reflection, absorption, etc."
**Notes**: 19 cited references including Garai et al. 2009 (frequency-encoded multiplexer/demultiplexer), Jeong et al. 1991 (all-optical logic via cross-phase modulation), Guo et al. 2008 (wavelength conversion with reflective SOAs), Ichioka et al. 1984 (optical parallel logic gates), Ibrahim et al. 2003 (AND/NAND gates in semiconductor microresonators).

## Source 4: https://pmc.ncbi.nlm.nih.gov/articles/PMC12267857/
**Title**: Exploring 400 Gbps/lambda and beyond with AI-accelerated silicon photonic slow-light technology
**Author/Publisher**: Changhao Han, Qipeng Yang, Jun Qin, Yan Zhou, Zhao Zheng, Yunhao Zhang, Haoren Wang, Yu Sun, Junde Lu, Yimeng Wang, Zhangfeng Ge, Yichen Wu, Lei Wang, Zhixue He, Shaohua Yu, Weiwei Hu, Chao Peng, Haowen Shu, John E Bowers, Xingjun Wang / Nature Communications, via PMC (PubMed Central)
**Date**: July 16, 2025
**Status**: FETCHED
**Key Claims**:
- 400 Gbps per wavelength transmission rate (PAM-4 modulation).
- 3.2 Tbps total data capacity on an 8-channel system.
- 90 GHz electro-optic bandwidth.
- 0.82 V*cm modulation efficiency.
- 7 nm optical passband.
- 1.6 Tb/s/mm^2 on-chip data-rate density.
- 249 micrometer modulation arm length; 500 micrometer device pitch; 4 mm x 0.5 mm modulation area.
- 36 dB static extinction ratio.
- 91.82 dB*Hz^(2/3) IMD3 SFDR.
- Crosstalk: -30 dB at 60 GHz; -20 dB at 90 GHz.
- 224 Gbps PAM-4 (IEEE standard rate); 390 Gbps PAM-8.
- 10.5 dB insertion loss.
**Named Entities**: Silicon slow-light modulators (Si-SLMs), coupled-resonator optical waveguide (CROW), deep neural networks (DNN), bidirectional gated recurrent units (bi-GRU), three-layer GRU (T-biGRU), PAM-4/PAM-8 modulation, intensity modulation/direct detection (IM/DD). Key researchers: Haowen Shu (Peking University), John E. Bowers (UC Santa Barbara), Xingjun Wang (Peking University). Institutions: Peking University State Key Laboratory of Photonics and Communications, UC Santa Barbara, Beijing Information Science and Technology University, Peng Cheng Laboratory, Peking University Yangtze Delta Institute of Optoelectronics. Equipment: Keysight PNA-X Network Analyzer, Yokogawa AQ6370C, Keysight M8199B arbitrary wave generator, Keysight UXR-Series oscilloscope.
**Direct Quotes**:
- "silicon photonics is an important platform with high complementary metal-oxide semiconductor (CMOS) compatibility, which brings the feasibility of low-cost and large-scale production."
- "the intrinsic efficiency-bandwidth trade-off and nonlinear distortions of pure silicon modulators result in transmission limits."
- "a self-optimizing positive feedback loop between computing centers and Si-SLM systems through ANN."
**Notes**: 29 peer-reviewed citations referenced, including silicon modulators (refs 27-40), lithium niobate modulators (refs 15-19), plasmonic modulators (refs 20-21), neural network equalization (refs 56-57, 69-73).

## Source 5: https://www.ciscoinvestments.com/harnessing-power-light-multi-wavelength-technology-transforms-data-centers
**Title**: Harnessing the Power of Light: Multi-Wavelength Technology Transforms Data Centers
**Author/Publisher**: Kay Min / Cisco Investments
**Date**: October 15, 2024
**Status**: FETCHED
**Key Claims**: No explicit numerical figures for data rates, efficiency percentages, or costs were published in the article body. Claims focused on qualitative assertions about AI data-center scaling and multi-wavelength laser platforms.
**Named Entities**: Xscape Photonics (company); multi-wavelength programmable laser platform; photonic integrated chips (PICs). Personnel: Dr. Vivek Raghunathan (CEO and co-founder, PhD MIT in photonics); Professor Alex Gaeta (co-founder, president); Professor Michal Lipson (co-founder); Professor Keren Bergman (co-founder); Yoshi Okawachi (co-founder, Head of R&D Laser). Origin institution: Columbia University. Investor: Cisco Investments.
**Direct Quotes**:
- "The problem has shifted from device-level performance to actively designing data centers with faster interconnections to improve performance."
- A single laser can generate "hundreds of different colors of light," increasing efficiency and reducing complexity.
- "Our goal is to enable our customers to build a sustainable data center fabric that can scale the performance of AI while keeping power consumption and costs within reasonable amounts."
**Notes**: No external studies or papers cited. Article functions partly as an investor-facing write-up of Xscape Photonics.

## Source 6: https://www.photonectcorp.com/post/vr-just-got-10x-more-realistic-how-photonic-chips-are-replacing-gpus
**Title**: VR Just Got 10X More Realistic: How Photonic Chips Are Replacing GPUs
**Author/Publisher**: Not listed / Photonect Corp (photonectcorp.com)
**Date**: May 1, 2025
**Status**: FETCHED
**Key Claims**:
- Current VR motion-to-photon latency: 20 milliseconds.
- Target latency for true immersion: below 7 ms.
- NVIDIA RTX 4090 power draw: up to 450 W.
- Next-gen headset resolution target: 8K per eye.
- Required rendering speeds: sub-1 ms.
- Speed of light cited: 186,000 miles per second.
- Claimed photonic AI acceleration potential: up to 1000x.
- Potential future latency with photonic chips: below 3 ms.
- Target frame rates: 120 Hz+.
**Named Entities**: Silicon photonics (Intel, Ayar Labs), optical neural networks, laser-assisted fiber attachment (Photonect patented technology), Photonect mode converter, MIT research on photonic AI accelerators, Meta research on VR latency, NVIDIA RTX 4090, Intel Silicon Photonics Roadmap, quantum computing.
**Direct Quotes**:
- "Photonic chips process information using light rather than electrons."
- "the breakthrough we need" (framing photonic processing as the breakthrough for next-generation VR).
**Notes**: Cited sources listed: Meta Research on VR Latency (2023); NVIDIA Power Consumption Reports (2023); MIT Study on Photonic AI Accelerators (2022); Intel Silicon Photonics Roadmap (2023). Tone is marketing-leaning; figures should be treated as vendor-cited rather than peer-reviewed.

## Source 7: https://resources.altium.com/p/quantum-computing-electronics-vs-photonics-new-chips-will-shift-balance
**Title**: Quantum Computing Electronics vs. Photonics: New Chips Will Shift the Balance
**Author/Publisher**: Zachariah Peterson / Altium Designer Blog (altium.com)
**Date**: April 22, 2021
**Status**: FETCHED
**Key Claims**:
- March 8, 2021: date of the Phys.org report on the Xanadu programmable photonic quantum chip announcement.
- 50 years: timeframe referenced for the progression of electronic IC scaling and integration.
- 2500+ technical articles: cited count of Peterson's published PCB design articles (author credential, not a scientific claim).
**Named Entities**: Companies: Xanadu (Canadian startup). Agencies and publishers: US National Institute of Standards and Technology (NIST), Nature, Phys.org, Altium Designer, Altium 365. Library: PennyLane (Python). Technologies: programmable photonic quantum chip, ring resonator cavities, beam splitters and phase shifters, waveguides, silicon photonics platform, CMOS process, superconducting qubits, trapped-ion qubits, microwave resonator cavities. Author affiliations: IEEE Photonics Society, IEEE Electronics Packaging Society, American Physical Society, PCEA, INCITS Quantum Computing Technical Advisory Committee, IEEE P3186 Working Group.
**Direct Quotes**:
- "The current incarnation receives data from fiber, but the bus width could be extended" (for many-photon operation capabilities).
- "Being able to run at room temperature removes the need for complex cooling systems or precise laser cooling setups."
- "The ability to perform computations with multiple inputs and outputs in parallel... does enable quantum advantage."
**Notes**: Cited papers: Phys.org report of March 8, 2021 on Xanadu and NIST; Nature paper on Xanadu chip at room temperature (DOI stem s41586-021-03202-1); Nature commentary (DOI stem d41586-021-00488-z).

## Source 8: https://arxiv.org/abs/1612.03131
**Title**: Frequency-encoded photonic qubits for scalable quantum information processing
**Author/Publisher**: Joseph M. Lukens, Pavel Lougovski / arXiv (Cornell University). Related journal DOI: 10.1364/OPTICA.4.000008 (Optica).
**Date**: Submitted December 9, 2016 (18:58:02 UTC)
**Status**: FETCHED (abstract and metadata only)
**Key Claims**:
- No numerical rates, efficiencies, or costs stated in the abstract.
- References "arbitrary N-qubit quantum gate" without specific benchmarks.
**Named Entities**: Researchers: Joseph M. Lukens, Pavel Lougovski. Technology: spectral linear optical quantum computation (spectral LOQC). Related field: high-speed fiber optics. Host: Cornell University (arXiv).
**Direct Quotes**:
- "spectral LOQC offer new potential for optical interconnects; it also brings the ubiquitous technology of high-speed fiber optics to bear on photonic quantum information."
- "favorable linear scaling of optical resources and enjoys an unprecedented degree of parallelism."
**Notes**: Abstract-level metadata only; no citation list visible from arXiv abstract page. Full reference list would need access to the Optica published version.
