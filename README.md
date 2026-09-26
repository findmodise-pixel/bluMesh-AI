# bluMesh-AI

MeshGen AI is an intelligent, edge-powered monitoring and predictive maintenance system designed for multi-node backup generator clusters in commercial and industrial facilities. Leveraging decentralized Bluetooth Mesh networking and Edge AI analytics, the system tracks critical mechanical and electrical health metrics locally without relying on fragile Wi-Fi or costly cellular data.
​

The Problem:
​Commercial facilities and factories increasingly rely on parallel clusters of backup generators to ensure continuous operations during grid instability. However:
​Unexpected mechanical failures (such as bearing wear or thermal strain) often go unnoticed until a total blackout occurs.
​Traditional monitoring systems rely on vulnerable cloud infrastructure or expensive wired SCADA setups.

​The Solution
​MeshGen AI deploys localized edge nodes across generator arrays to provide real-time telemetry, local anomaly detection, and peer-to-peer mesh alerts.
​
Key Features
​Bluetooth Mesh Networking: Self-healing local communication topology connecting multiple generator nodes across a facility floor.
​Edge AI Anomaly Detection: Real-time processing of engine vibrations and thermal patterns to predict mechanical degradation before failure occurs.
​Comprehensive Telemetry: Continuous tracking of engine wear, electrical load, and fluid consumption metrics.


​Bill of Materials (BOM)
​1. Core Processing & Communication Layer
​Primary Controller: Nordic nRF54LM20 DK (featuring integrated Axon NPU and native Bluetooth Mesh/LE support).
​2. Sensing Layer
​Vibration & Motion: 3-axis Accelerometer (e.g., ADXL345 / MPU6050) mounted to the engine block for mechanical health analysis.
​Thermal Monitoring: Waterproof digital temperature sensor / thermocouple (for cylinder head and exhaust monitoring).
​Electrical Output: Non-invasive Current Transformer (CT) clamp (e.g., SCT-013) for load and amperage tracking.
​Fluid Level: Ultrasonic distance sensor or liquid level sensor for real-time fuel tracking.
​Target Deployment
​Industrial and commercial backup power clusters requiring resilient, decentralized local monitoring.
