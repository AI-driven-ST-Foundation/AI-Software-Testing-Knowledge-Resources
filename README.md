# AI-Powered Software Testing Tools and Research

This repository curates the best AI tools for mobile and web app automation testing alongside seminal and recent research on AI-driven software testing. It covers open-source frameworks and commercial platforms that leverage AI (machine learning, computer vision, NLP) to improve test creation, execution, and maintenance. Key topics include AI-powered test case generation, visual UI testing, self-healing automation, defect prediction, and CI/CD integration.

---

## Table of Contents

1. [AI Tools for Software Testing](#ai-tools-for-software-testing)
   - [Open-Source Tools](#open-source-tools)
   - [Commercial Platforms](#commercial-platforms)
2. [AI Models and Libraries](#ai-models-and-libraries)
3. [Research Papers](#research-papers)
   - [Test Case Generation](#test-case-generation)
   - [Visual Testing and GUI Automation](#visual-testing-and-gui-automation)
   - [Self-Healing Test Automation](#self-healing-test-automation)
   - [Defect Prediction and Analytics](#defect-prediction-and-analytics)
   - [AI in CI/CD](#ai-in-cicd)
   - [Additional Research Papers](#additional-research-papers)
4. [Blog Posts](#blog-posts)
5. [Contributions](#contributions)

---

## AI Tools for Software Testing

### Open-Source Tools
- **Microsoft OmniParser**  
  An AI tool for visual UI parsing and automation that detects interactive elements from screenshots.  
  [GitHub: microsoft/OmniParser](https://github.com/microsoft/OmniParser)

- **askUI VisionAgent**  
  An automation agent that "sees" the UI to perform operations based on plain English or Python API commands.  
  [GitHub: askui/vision-agent](https://github.com/askui/vision-agent)

- **Healenium**  
  A self-healing test automation library for Selenium that uses ML to dynamically update broken locators.  
  [Healenium Documentation](https://solutionshub.epam.com)

- **EvoSuite**  
  Automatically generates JUnit test suites for Java classes using genetic algorithms to achieve high code coverage.  
  [EvoSuite Website](https://cse.unr.edu)

- **SikuliX**  
  A GUI automation tool based on image recognition. Though it uses basic computer vision, it laid the groundwork for modern visual testing.  
  [SikuliX](http://sikulix.com)

- **Others:**  
  - **Robot Framework** with AI libraries  
  - **Appium** integrated with image recognition plugins  
  - Emerging projects like **TestGPT** for generating test cases from requirements

### Commercial Platforms
- **Applitools Eyes**  
  Uses proprietary visual AI to detect UI regressions intelligently by comparing screenshots beyond pixel-level differences.  
  [Applitools Eyes](https://applitools.com)

- **Functionize**  
  Converts plain English test steps into executable scripts using ML and NLP, with self-healing capabilities when the UI changes.  
  [Functionize](https://functionize.com)

- **Mabl**  
  A cloud-based service that auto-generates tests by crawling your web application, applying ML for self-healing and maintenance.  
  [Mabl](https://mabl.com)

- **Testim (Harness)**  
  Employs dynamic weighted locators and natural language-based test creation to maintain test stability despite UI changes.  
  [Testim on Harness](https://harness.io)

- **testRigor**  
  Enables writing tests in plain English and leverages GPT-4 for automated test script generation and maintenance across platforms.  
  [testRigor](https://testrigor.com)

- **AccelQ**  
  A no-code platform that uses generative AI for creating test scenarios and self-healing automation for web, API, and mainframe testing.  
  [AccelQ](https://accelq.com)

- **Rainforest QA**  
  Combines AI with crowd-testing to convert plain English tests into automated steps, with fallback human verification if needed.  
  [Rainforest QA](https://rainforestqa.com)

- **Other Platforms:**  
  - **OpenText UFT One** with AI-based visual recognition  
  - **Autify**, **Reflect**, **Meticulous**, **ProdPerfect**, **Tricentis Tosca (Vision AI)**, etc.

---

## AI Models and Libraries

- **YOLOv5 & YOLOv8**  
  State-of-the-art object detection models used for identifying UI elements in screenshots in real time.  
  [YOLOv5](https://github.com/ultralytics/yolov5) | [YOLOv8](https://github.com/ultralytics/yolov8)

- **OpenAI GPT-4**  
  Leverages natural language processing to generate test cases, write unit tests, and analyze logs.  
  [OpenAI API](https://openai.com/api)

- **Vision AI Libraries**  
  Tools such as OCR (Tesseract, Azure OCR) and template matching algorithms for robust visual UI element recognition.

- **Reinforcement Learning Agents**  
  Agents that explore GUIs and learn optimal testing strategies, enhancing exploratory test automation.

- **Code Analysis Models**  
  Models like code2vec, Graph Neural Networks, and transformer-based models (e.g., Codex) assist in generating tests and predicting defects.

---

## Research Papers

### Test Case Generation
- **EvoSuite: Automatic Test Suite Generation for Object-Oriented Software (Fraser & Arcuri, 2011)**  
  Pioneering work on generating JUnit tests using genetic algorithms.  
  [Read more](https://cse.unr.edu)

- **The Future of Software Testing: AI-Powered Test Case Generation and Validation (Baqar & Khanda, 2024)**  
  A survey of AI techniques for automatic test creation and maintenance.  
  [arXiv](https://arxiv.org)

- **Reinforcement Learning for Test Case Prioritization (Spieker et al., 2017)**  
  Uses RL to dynamically order and generate tests in a CI environment.  
  [More info](http://hspeiker.de)

- **ChatGPT and Test Generation (2023)**  
  Early explorations on leveraging large language models to generate test scenarios and unit tests.

### Visual Testing and GUI Automation
- **Vision-Based Mobile App GUI Testing: A Survey (Wang et al., 2023)**  
  Reviews image-based techniques using CNNs and OCR for mobile UI testing.  
  [arXiv](https://arxiv.org)

- **GUI Element Detection from Mobile UI Images Using YOLOv5 (Altinbas & Serif, 2022)**  
  Demonstrates accurate detection of UI components using YOLOv5.  
  [arXiv](https://arxiv.org)

- **Intelligent System for Visual Testing of Software Products (2021)**  
  Explores neural network approaches to enhance visual regression detection.

- **Visual GUI Testing in Practice: Challenges and Benefits (Alégroth et al., 2018)**  
  An empirical study on the advantages and challenges of visual testing in continuous integration.

### Self-Healing Test Automation
- **Self-Healing Test Automation Frameworks Using Reinforcement Learning (Dey et al., 2022)**  
  Proposes an RL-based approach for dynamically repairing test scripts.  
  [Online Scientific Research](https://onlinescientificresearch.com)

- **Multi-Year Grey Literature Review on AI-assisted Test Automation (Corradini et al., 2024)**  
  Surveys industry trends and implementations of self-healing in test automation.  
  [arXiv](https://arxiv.org)

- **Self-Healing Test Automation using AI and ML (2021)**  
  A case study demonstrating the effective use of ML to update test selectors automatically.

### Defect Prediction and Analytics
- **A Survey on Software Defect Prediction using Deep Learning (Akimova et al., 2021)**  
  Reviews deep learning methods for predicting defect-prone code areas.  
  [MDPI](https://mdpi.com)

- **DeepLineDP: Towards a Deep Learning Approach for Line-Level Defect Prediction (Wang et al., 2020)**  
  Applies CNNs for fine-grained defect prediction at the code line level.  
  [IEEE Xplore](https://ieeexplore.ieee.org)

- **Just-In-Time Defect Prediction with Bidirectional LSTMs (Hoang et al., 2019)**  
  Uses deep learning on commit messages and diffs to forecast risky commits.  
  [ACM ASE](https://dl.acm.org)

- **Software Defect Prediction: Do Classifiers Matter? (Lessmann et al., 2008)**  
  A classic study comparing various classifiers for defect prediction.

- **Bugram: Bug Detection with N-gram Language Models (Kang et al., 2019)**  
  Utilizes N-gram models to detect anomalous code sequences that may indicate bugs
