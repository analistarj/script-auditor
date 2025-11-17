# script-auditor

Automated audit scripts for IT controls and compliance.

## Overview

This repository contains a collection of Python scripts designed to automate common IT audit tasks, including:

- Security control verification
- Log analysis and anomaly detection
- Compliance checks (e.g., ITGC, SOX, ISO 27001)
- Reporting of findings in human readable formats

These tools support auditors and security professionals in streamlining repetitive tasks and improving audit coverage.

## Requirements

- Python 3.8+
- Required libraries are listed in `requirements.txt` (to be created). The main dependencies include pandas, requests and other auditing packages.

## Usage

Clone the repository and run the desired script from the command line, for example:

```bash
python scriptbucket.py --help
```

Each script includes command line arguments and documentation. Refer to the comments inside each file for details on input parameters and output.

## Contributing

Contributions are welcome! Please open an issue to discuss proposed changes or new audit scenarios. Feel free to submit pull requests with additional scripts, bug fixes or improvements.

## License

[MIT](LICENSE)
