---
title: Installation
layout: default
nav_order: 1
---

# Installation
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

Pre-requisites: [Python](https://www.python.org/), [Git](https://git-scm.com/), and [Conda](https://www.anaconda.com/products/individual). All software has been tested on Ubuntu 18.04 and 24.04.

### Create a conda environment
  
  ```
  conda create --name babybench python=3.12
  conda activate babybench
  ```
  
###  Clone the BabyBench2025 repository
  
  ```
  git clone https://github.com/babybench/BabyBench2025.git
  cd BabyBench
  ```
  
### Install requirements
  
  ```
  pip install -r requirements.txt
  ```
  
### Install MIMo
  
  ```
  pip install -e MIMo
  ```
  

All done! You are ready to start using BabyBench.

### Launch the installation test
  
  ```
  python test_installation.py
  ```

This will run a test to check that the everything is correctly installed.  

### Troubleshooting

If you encounter any issues, visit the ![troubleshooting page](https://babybench.github.io/babybench2025/wiki/troubleshooting)