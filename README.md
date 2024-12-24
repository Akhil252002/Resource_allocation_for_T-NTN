Title: Resource Allocation for T-NTN in 5G NR Systems
Description:
The project focuses on developing and implementing a Radio Resource Management (RRM) scheme to optimize resource allocation in integrated Terrestrial-Non-Terrestrial Networks (T-NTN). The integration of terrestrial networks (TN) and non-terrestrial networks (NTN) aims to enhance connectivity, improve network performance, and support innovative 5G applications. The project addresses challenges such as spectrum sharing, mobility management, and ensuring Quality-of-Service (QoS) for diverse user needs.
Features and Functionality
Adaptive Data Rate (ADR) Calculation:

Dynamically adjusts the data transmission rate based on network conditions, optimizing throughput and efficiency.
Mobility Management:

Provides seamless handovers between terrestrial and non-terrestrial networks, minimizing service disruptions during transitions.
Spectrum Sharing Mechanisms:

Implements dynamic spectrum sharing between TN and NTN to avoid interference and maximize spectrum utilization.
State Transition Analysis:

Uses Markov chains to analyze and predict the state transitions in communication systems, aiding in efficient resource allocation.
Delay and Latency Measurement:

Calculates Round Trip Delay (RTD) to monitor and improve signal transmission between T-NTN terminals and NTN nodes.
Fair Resource Allocation:

Ensures equitable distribution of radio resources among users while maximizing network performance.
Technologies Used
Hardware:

Intel i5 8th Generation or better CPU
8GB+ DDR4 RAM
Nvidia MX150 GPU (2GB+ VRAM)
256GB+ SSD for storage
Software:

Operating System: Windows OS
Development Tool: MATLAB R2023b
Mathematical Models: Loo probability density function, Markov Chains
Network Simulation: Built-in MATLAB functions and custom scripts
Installation and Usage Instructions
Hardware Setup:
Ensure your system meets the specified hardware requirements.
Install the latest drivers for your GPU and update the operating system.
Software Installation:
MATLAB Installation:

Download MATLAB R2023b from the MathWorks website.
Follow the installation wizard to complete the setup.
Ensure the following toolboxes are installed:
Communications Toolbox
Optimization Toolbox
Signal Processing Toolbox
Project Files:

Clone or download the project repository from GitHub:
bash
Copy code
git clone https://github.com/your-repository-name.git
Extract the project files if downloaded as a zip.
Usage Instructions:
Open the Project:

Launch MATLAB and navigate to the project directory.
Open the main script file (e.g., main.m).
Configuration:

Set parameters for the simulation (e.g., bandwidth, mobility patterns) in the configuration section of the script.
Run the Simulation:

Execute the main script by typing:
matlab
Copy code
run main.m
The output will display resource allocation metrics, throughput, and delay analysis.
Analyze Results:

Use the generated plots and logs to evaluate the performance metrics such as throughput, latency, and fairness.
Customize:

Modify parameters or algorithms in the code to test different scenarios or optimize further.
