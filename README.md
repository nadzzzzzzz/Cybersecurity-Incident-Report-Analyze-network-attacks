# DDoS Attack Analysis - Travel Agency Website

## Overview

This repository is part of the Google Cybersecurity Professional Certificate Program, focusing on a detailed analysis of a Distributed Denial-of-Service (DDoS) attack targeting a travel agency's website. The aim is to study the nature of the attack, identify its impacts, and develop strategies to mitigate such incidents in the future.

## Scenario

The travel agency's website started experiencing persistent connection timeouts, traced back to an overwhelming number of TCP SYN requests from various unfamiliar IP addresses, indicating a DDoS attack.

## Analysis Highlights

- *Attack Type:* Identified as a SYN flood attack, which is a form of DDoS.
- *Methodology:* Massive amounts of SYN packets were sent to disrupt the server's normal TCP three-way handshake, creating numerous half-open connections.
- *Impact:* The server's resources were exhausted, preventing responses to legitimate traffic and causing significant operational disruptions.

## Repository Structure

- /logs - Contains logs capturing the sequence and pattern of the attack.
- /scripts - Scripts used for log analysis and pattern detection.
- /docs - Documentation on findings, analysis, and recommendations for future prevention measures.

## Getting Started

To delve into the DDoS attack analysis:

1. Clone this repository to your local system.
2. Navigate to the /scripts directory.
3. Execute the scripts to process the logs stored in /logs.
4. Refer to the /docs directory for detailed analysis and mitigation strategies.

## Tools Used

- Wireshark: For capturing and analyzing network packets.
- Custom Python scripts for automating log analysis.

## Contributing

Contributions to enhance the analysis or improve mitigation strategies are welcome. To contribute:

1. Fork the repository.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For queries or issues related to this analysis, please open an issue in this repository.

## Acknowledgments

- Thanks to the Google Cybersecurity Professional Certificate Program for the educational framework and guidance provided for this analysis.
