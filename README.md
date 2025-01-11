# Cryptanalysis of Tor
**Date:** December 14, 2023  
**Author:** Nicholas Nagy  
**Institution:** Mount Allison University

## Introduction
This repository contains a comprehensive paper discussing the cryptanalysis of Tor, an open-source software project designed to enable anonymous communication. The paper delves into the history of Tor, the details of its multi-layered encryption (including TLS and AES), its vulnerabilities and methods to mitigate attacks. It also explores emerging improvements such as ShorTor and frameworks like AnoA for analyzing anonymity properties.

## Repository Contents
- **cryptanalysis_of_tor.pdf**  
  The full PDF document containing:
  - **History of Tor**  
    Details about its inception, purpose, and evolution.  
  - **Technical Structure**  
    Explanation of how Tor encrypts and routes traffic using guard, middle, and exit nodes.  
  - **Security Analysis**  
    In-depth look at known vulnerabilities (traffic analysis, Sybil attacks, TLS ciphersuite weaknesses).  
  - **ShorTor**  
    Discussion on potential improvements to Tor focusing on reduced latency without compromising anonymity.  
  - **AnoA Framework**  
    Overview of how anonymity can be quantitatively measured and analyzed.
  - **References**  
    Comprehensive list of sources and scholarly articles cited throughout the paper.

## Highlights
- **Layered Encryption Approach**  
  Explains Tor’s use of AES (in both CBC and Counter modes) and TLS for secure and private traffic routing.
- **Known Vulnerabilities**  
  Discusses CBC-mode attacks (BEAST, Lucky-Thirteen, POODLE, etc.), traffic analysis, Sybil attacks, and rogue node exploits.
- **ShorTor**  
  Introduces an enhanced version of Tor designed to decrease latency through multi-hop overlay routing.
- **AnoA Framework**  
  Explores how anonymity levels can be formally and quantitatively analyzed in anonymous communication protocols.

## How to Use
1. **Clone or download** this repository.
2. **Open** the `cryptanalysis_of_tor.pdf` file using any standard PDF viewer.
3. **Review** the paper for insights into Tor’s encryption techniques, vulnerabilities, and prospective improvements.

## Contributing
Contributions, suggestions, or improvements to the paper or any associated research are welcome. Please open an issue or submit a pull request with your proposed changes or additional insights.

## License
Feel free to modify or reference this work for academic and research purposes. Refer to the paper’s references and this repository’s [LICENSE](LICENSE) file (if provided) for more information regarding usage and distribution.

---

**Contact**  
If you have any questions or wish to discuss this research, please contact the author at:  
[nicknagy2003@gmail.com](mailto:nicknagy2003@gmail.com)
