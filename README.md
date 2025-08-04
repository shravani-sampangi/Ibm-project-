Power System Fault Detection Project  
This project focuses on developing an AI-powered system for detecting and classifying faults in power distribution networks to improve reliability, stability, and operational efficiency. Faults in power systems—such as line-to-ground, line-to-line, and three-phase faults—can lead to power outages, equipment damage, and financial losses if not addressed quickly and accurately. Traditional detection methods often struggle with overlapping electrical signals and complex system behaviors, making real-time fault classification a critical challenge.

To address these challenges, the system integrates IBM Watsonx.ai AutoAI and IBM Cloud Object Storage* into an automated machine learning workflow. The key capabilities of this solution include:

1. **Data Collection & Management**

   * Gathers structured datasets containing parameters like voltage, current, frequency, power factor, and labeled fault types.
   * Utilizes *IBM Cloud Object Storage* for secure and scalable dataset handling.

2. **Automated Data Preprocessing**

   * Cleans noisy, incomplete, and inconsistent data using Watsonx.ai AutoAI’s built-in preprocessing tools.
   * Performs feature engineering to extract patterns essential for fault classification, reducing the need for manual intervention.

3. **Machine Learning Model Development**

   * Uses *Snap Logistic Regression* (selected by AutoAI) for efficient and accurate multiclass fault classification.
   * Trains models automatically, selecting the best features and hyperparameters to optimize performance.

4. **Deployment & Real-Time Classification**

   * Deploys the trained model through Watsonx.ai, enabling real-time fault detection and classification.
   * Provides actionable outputs to assist operators in taking timely corrective measures.

5. **Scalability & Future Scope**

   * Designed for integration with IoT devices to enable live data streaming from power grids.
   * Can be deployed on edge devices for low-latency, on-site decision-making.
   * Future iterations aim to support smart self-healing grids and extend fault detection to renewable energy systems.
     
 **Impact of the Project**

* Improved Grid Stability : Accurate and fast fault classification minimizes downtime and protects infrastructure.
* Reduced Manual Effort : Automated ML workflows eliminate complex manual preprocessing and model selection steps.
* Industry Applicability : Can be adapted for industrial power systems, research purposes, and emerging smart grid applications.

