# GCP Load Balancer Selector

## Overview

This web-based tool helps users quickly determine the right Google Cloud Load Balancer based on their use case. It was built to simplify decision-making by guiding users through a series of intuitive questions and providing tailored recommendations with links to the official GCP documentation.

## How it Works

1. A user visits the hosted tool in their web browser.
2. The page prompts a sequence of multiple-choice questions:

   * Type of traffic (HTTP/S, TCP, UDP, gRPC)
   * User location (Global, Regional)
   * Backend type (VM, GKE, Serverless)
   * Load balancer visibility (External, Internal)
   * Need for advanced features (Yes/No)
3. Based on the combination of answers, the tool matches a predefined rule set and outputs:

   * A recommended GCP Load Balancer type
   * A brief explanation
   * A link to the relevant official documentation

## Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **Framework**: None (Vanilla JS)
* **Hosting**: GitHub Pages (via [kamxnet](https://github.com/kamxnet/gcp-lb-selector))

## Development & Deployment

### Project Structure:

```
/ (root)
├── index.html             # Main HTML with embedded JavaScript logic
├── README.md              # Documentation (this file)
├── LICENSE
```


### Deployment

This project is deployed using **GitHub Pages**:

1. Visit: `https://kamxnet.github.io/gcp-lb-selector`

## Owner

Kam Bawa [ksbnetworks@gmail.com](mailto:ksbnetworks@gmail.com.com)
