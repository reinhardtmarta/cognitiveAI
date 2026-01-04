# Make / Usage Guide for Secure Fragmented Cognitive AI Simulation

## 1. Overview
This notebook demonstrates a secure, fragmented cognitive AI architecture that:
- Generates autonomous knowledge
- Filters outputs via Guard Agents
- Stores internal data in a secure memory cloud
- Provides human-accessible outputs through a Creation Cloud

No external API or human interaction is required.



## 2. Modules

### 2.1 Cognitive AI (Passive)
- Receives filtered inputs
- Generates hypotheses and internal knowledge
- Cannot act externally

### 2.2 Operational AI
- Converts hypotheses into structured outputs
- Prepares data for Guard Agents

### 2.3 Guard Agents
- Monitors all outputs
- Blocks, modifies, or logs unsafe outputs
- Ensures system integrity

### 2.4 Memory and Creation Clouds
- **Internal Memory:** Stores all cognitive outputs securely
- **Creation Cloud:** Outputs safe, filtered responses for human consumption
  

## 3. Notebook Setup

### 3.1 Requirements
- Python 3.x
- Libraries:

pip install networkx matplotlib graphviz

### 3.2 Running the Notebook
1. Open [Cognitive AI Notebook](https://github.com/reinhardtmarta/cognitiveAI) in Colab
2. Run all cells sequentially
3. Observe the logs and graphs generated



## 4. Inputs & Tests
- You can create test inputs as:
- python
inputs = ["Calculate safe AI", "Send data to humans", "Dangerous command"]

The notebook will simulate:

Processing by Cognitive AI

Structuring by Operational AI

Filtering by Guard Agents

Storage in Creation Cloud




5. Visualizations

Information Flow Graph: Shows the path of data between modules

Concurrency Simulation: Test multiple queries at the same time

Guard Agent Logs: See which outputs were blocked or modified



6. Extending the Simulation

Add more Guard Agents rules

Test with larger input sets

Modify Cognitive AI logic to simulate advanced knowledge generation


7. References

Original GitHub Repository

Concepts based on: Multi-Agent Systems, Federated Learning, Guarded AI architectures

