# Master Key Claims and Citation Map

## IEEE Reference Numbering (use these exact numbers in all parts)

[1] Keysight, "Why the Future Belongs to Photonics" (qualitative only). keysight.com.
[2] R. Laskey, "What is the difference between photonic and electronic semiconductors?" PhotonDelta, Dec. 15, 2025.
[3] R. Laskey, "How do photonic chips compare to traditional processors?" PhotonDelta, Feb. 13, 2026.
[4] M. ElKabbash et al., Photonic Computing research page, U. of Arizona Wyant College.
[5] S. K. Garai, "Method of all-optical frequency encoded decimal to binary... data conversion using SOAs," Applied Optics, Jul. 20, 2011, PMID 21772361.
[6] R. Nagarajan, "Highly Integrated Silicon Photonics Light Engines in High-Speed Data Transport," Marvell blog, Aug. 16, 2021.
[7] M. Swayne, "Scientists Shine Light on Multidimensional Photonic Computing," The Quantum Insider, Jul. 10, 2025 (covering Nature Reviews Physics 2025, DOI s42254-025-00843-3).
[8] A. Dudhia, "How Do Quantum and Photonic Deep Learning Platforms Compare to Current GPU Hardware?" NHSJS, Nov. 8, 2024.
[9] World Economic Forum, "Photonic computing: promise and commercialization," Aug. 2025 (BLOCKED, cite with caution).
[10] S. Dutta and S. Mukhopadhyay, "Alternating approach of implementing frequency encoded all-optical logic gates...," Optik, vol. 122, no. 12, pp. 1088-1094, Jun. 2011.
[11] C. Han et al., "Exploring 400 Gbps/lambda and beyond with AI-accelerated silicon photonic slow-light technology," Nature Communications, Jul. 16, 2025, PMC12267857.
[12] K. Min, "Harnessing the Power of Light: Multi-Wavelength Technology Transforms Data Centers," Cisco Investments, Oct. 15, 2024.
[13] Photonect Corp., "VR Just Got 10X More Realistic...," May 1, 2025.
[14] Z. Peterson, "Quantum Computing Electronics vs. Photonics...," Altium, Apr. 22, 2021.
[15] J. M. Lukens and P. Lougovski, "Frequency-encoded photonic qubits for scalable quantum information processing," arXiv:1612.03131, Dec. 2016; Optica, DOI: 10.1364/OPTICA.4.000008.
[16] N. A. Peters et al., "A Quantum Interconnect for Matter Qubits Based on Frequency-Encoded Photonic Qubits," ORNL project, started Oct. 2016.
[17] MIT TLO, "Radio-Frequency Photonic Architecture for Deep Neural Networks" (MAFT-ONN, case #24089, inventors D. R. Englund and R. Davis).
[18] F. Su and J.-P. Laude, "History and technology of wavelength division multiplexing," OE Reports 166, SPIE, Oct. 30, 1997.
[19] J. Guo et al., Photonic GEMM accelerator, IEEE JSTQE, vol. 28, pp. 72-79, 2022, DOI: 10.1109/JSTQE.2022.3196884 (metadata only; full text not retrieved).
[20] Aliro Technologies, "Encoding Photonic Qubits," Aliro Quantum blog, Nov. 5, 2025.
[21] "Wavelength-division multiplexing," Wikipedia, last edited Mar. 11, 2026.
[22] P. Pintus et al., "Integrated non-reciprocal magneto-optics with ultra-high endurance for photonic in-memory computing," Nature Photonics, Oct. 23, 2024, DOI: 10.1038/s41566-024-01549-1.
[23] J. Oncea, "Silicon Photonics Tackles AI's Data Bottleneck," Photonics Online, Dec. 2, 2025.
[24] S. Vinet, W. Wu, Y. Zhang, and T. Jennewein, "Feasibility study of frequency-encoded photonic qubits over a free-space channel," arXiv:2412.06104v1, Dec. 8, 2024.

Flagged Uncertain (blocked during retrieval, include only as contextual citations if absolutely needed):
- APS PRL 134.240803 (2025)
- Nature Light Science s41377-024-01696-8 (2024)
- Nature Communications s41467-024-46014-3 (2024)
- npj Nanophotonics s44310-024-00024-7 (2024)

## Key Verified Numerical Claims (with citation)

### Performance / Data Rates
- 400 Gbps per wavelength with silicon slow-light modulators; 3.2 Tbps aggregate across 8 channels; 90 GHz EO bandwidth; 0.82 V*cm efficiency; 1.6 Tb/s/mm^2 on-chip density [11]
- 570 picoseconds end-to-end photonic image classification; 2.1375 nJ per inference vs 153,580 J classical GPU baseline [8]
- Linear transformations in optical neural networks operate at more than 100 GHz [8]
- 31 picoseconds light traversal through nanophotonic circuit [8]
- 224 Gbps PAM-4 IEEE standard rate; 390 Gbps PAM-8 demonstrated [11]
- 217 TOPS on-chip diffractive optics; 11+ TOPS via combined time, wavelength, spatial multiplexing; three orders of magnitude better energy efficiency than traditional chips [7]
- MAFT-ONN three-layer DNN computes over four million fully analog operations per computation [17]
- Tbps convolutional neural network speeds demonstrated [7]

### Energy / Efficiency
- Silicon photonics reduced power per unit bandwidth by greater than 30x over 20 years; bandwidth density per volume up 10x; bandwidth per module up 400x [6]
- 1 fJ/bit at 25 Gbps for depletion-mode resonant silicon modulators; sub-picojoule-per-bit target [23]
- 70% power savings for AI workloads from co-packaged optics [23]
- Photonic system power: 3.75 W (high-speed) and 2 W (low-speed); classical GPU 70 W training [8]

### Capacity / Bandwidth Density
- Switch capacity progression: 12.8 Tbit/s to 51.2 Tbit/s generation [6]
- 1.6 Tbps transceiver throughput target; 200 Gbps per lane, 8 lanes in parallel [23]
- Single chip integration of 500 to 10,000 components [23]
- 64 to 128 wavelength channels per bus [23]
- DWDM: 40 channels at 100 GHz or 80 channels at 50 GHz spacing; 160-signal systems carry 16+ Tbit/s [21]
- 320-channel DWDM system with 12.5 GHz spacing [21]
- IBM Muxmaster (1997): 20 wavelengths at up to 2 Gbit/s each [18]

### WDM History (for History of Computing section)
- WDM concept first published 1970 (O. E. Delange, Proc. IEEE 58, p. 1683) [21]
- Lab WDM systems operational by 1980 [21]
- Tomlinson and Lin 1978 optical multiplexer 1 to 1.4 micron [21]
- Ishio/Minowa/Nosu 1984 IEEE review of WDM [21]
- DWDM first commercial deployment June 1996 (Ciena on Sprint) [21]
- ITU-T G.694.1 grid reference 193.10 THz (1552.52 nm) [21]
- ITU proposed 100 GHz spacing (~0.8 nm) in 1997 [18]
- Carrier-wave frequencies 192 to 196 THz [18]

### Commercialization / Market
- Silicon photonics market projected $863M by 2029 at 45% CAGR (Yole Group) [23]
- Xanadu programmable photonic quantum chip at room temperature, Nature, Mar. 8, 2021 [14]
- Photonic chips projected 10-15+ years to price parity; widespread adoption by 2030 [3]
- Xscape Photonics multi-wavelength programmable laser platform (Columbia U. spinout: Gaeta, Lipson, Bergman, Raghunathan, Okawachi) [12]
- Ayar Labs TeraPhys optical chiplet; Lightmatter Passage [23]
- 2.4 billion switching cycles in Ce:YIG magneto-optic memory cells, three orders of magnitude better endurance [22]
- MAFT-ONN MIT (D. Englund, R. Davis, 2024 filing) [17]

### Memory Bandwidth Baseline (for comparisons)
- NVIDIA Blackwell: 8 TB/s single-core, 64 TB/s 8-core [8]
- Intel Core X-Series: 0.094 TB/s theoretical [8]
- NVIDIA DGX: 8-16 GPUs, 900 GB/s internal, 400 Gb/s InfiniBand [23]
- AI models exceed 100 trillion parameters [23]

### Quantum / Frequency Encoding
- Frequency-encoded photonic qubits free-space: Z-basis visibility 85.5 +/- 2.2%; X-basis 92.4 +/- 2.7%; 260 MHz frequency separation; 780 nm wavelength [24]
- Frequency bin spacing up to 50 GHz with electro-optic modulators [24]
- Lukens & Lougovski 2016 foundational spectral LOQC paper [15]
- ORNL Peters project started October 2016 [16]

### Challenges
- Manufacturing complexity cited as primary disadvantage requiring precise optical control and alignment [2] [3]
- Nonlinear operations hard without noise/instability; opto-electronic interface delays; shallow computations [7]
- Photon loss (scattering, failure to reach destination) [8]
- Integration of beam splitters, modulators, detectors into single circuit a significant challenge [8]
- Noise and crosstalk always remain, reducing accuracy [8]
- Intrinsic efficiency-bandwidth trade-off in pure silicon modulators [11]
- Two-class 93.8%, four-class 89.8% photonic accuracy vs Keras 96% (so there IS accuracy gap in some configurations) [8]
- 10% wall-plug efficiency for C/L/O band lasers [23]

### History of Computing Context Facts
- Garai 2011 early all-optical logic using SOAs [5]
- Dutta and Mukhopadhyay 2011 frequency-encoded logic gates/flip-flop [10]
- Moore's Law: transistor doubling every 2 years [8]
- Tomlinson and Lin 1978 early WDM [21]
- Delange 1970 WDM concept [21]

## Style Rules for All Drafting Agents

1. ZERO em dashes (no "—" character). Use commas, colons, periods, semicolons, or " - " (hyphen with spaces) instead.
2. IEEE citation style: [N] format inline, where N is the reference number above.
3. Specific numbers wherever possible. No "many studies show" or "research indicates."
4. Add image placeholder markers using this format:

`[FIGURE N: Brief description] — placeholder for image to be generated`

Numbered figures across the whole paper (Figure 1 through whatever the final count is).

5. No generic academic openers ("In today's world," "Throughout history," "In recent years").
6. Claim-evidence-analysis paragraph structure.
7. Undergraduate audience: define technical terms on first use (waveguide, RC delay, WDM, tensor core, etc.).
