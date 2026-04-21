# LLM-Driven Multi-Agent Optical Digital Twin for Automated Data Generation

[![Python](https://img.shields.io/badge/Python-3.8%7C3.9%7C3.10-blue)](https://www.python.org/)
[![InfluxDB](https://img.shields.io/badge/InfluxDB-2.x-brightgreen)](https://www.influxdata.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14%2B-blue)](https://www.postgresql.org/)
[![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-3.x-orange)](https://kafka.apache.org/)
[![Grafana](https://img.shields.io/badge/Grafana-9.x-yellow)](https://grafana.com/)
[![Kadeck](https://img.shields.io/badge/Kadeck-Kafka%20UI-blueviolet)](https://www.kadeck.com/)
[![GNPy](https://img.shields.io/badge/GNPy-Enabled-success)](https://github.com/Telecominfraproject/oopt-gnpy)
[![OptiCommPy](https://img.shields.io/badge/OptiCommPy-Enabled-success)](https://github.com/edsonportosilva/OptiCommPy)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-black)](https://platform.openai.com/)

![LLM-Driven Multi-agent Optical Digital Twin Framework](architecture.png)

The proposed LLM-driven multi-agent optical DT framework translates natural-language user requests into executable physical-layer studies through a layered architecture comprising an agentic AI layer, an orchestrator, a network knowledge base, a digital twin, and the optical network physical layer. It bridges unstructured user intents and reproducible optical-network experimentation by automatically deriving study objectives, simulation constraints, scenario definitions, and reporting targets.

The optical network physical layer provides real network topology, device configuration, and monitoring data through telemetry interfaces. These data are stored in the knowledge base using InfluxDB and PostgreSQL to support both agent reasoning and DT execution. The digital twin serves as the computational core, combining physics-based, ML-based, and optimisation models for scalable QoT-related data generation and analysis. The orchestration layer manages task graphs, execution policies, simulator invocations, and lifecycle coordination across the pipeline. On top of this, the agentic AI layer performs task planning, scenario expansion, result analysis, iterative reflection, and report generation in a closed loop, enabling reliable and physically meaningful optical-network data generation with minimal manual effort.

## One-month Performance Monitoring Data from Optical Networks over NDFF


## 📧 Contact Information
If you have any questions regarding the dataset or want to have some collaborations, please feel free to contact:

Dr. Shuangyi Yan: shuangyi.yan@bristol.ac.uk (Team Leader & Project Manager)

Dr. Sen Shen: sen.shen@bristol.ac.uk (Optical Networks & AI/ML)

## ©️ Copyright
This open-source dataset is owned and managed by the **Smart Internet Lab, University of Bristol**. The data is provided for academic research and non-commercial use only. For any commercial use, please contact the authors for permission.
