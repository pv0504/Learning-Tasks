# Learning-Tasks
This is a comprehensive summary of the network programming learning tasks you have collected, organized into a clear tabular format. Each entry includes a description of the task and the specific reference links you requested.

### **Network Programming: Learning Tasks & Datasets**

| Learning Task | Task Description | Relevant Dataset / Link |
| --- | --- | --- |
| **Network Intrusion Detection & DDoS Mitigation** | A supervised classification task using packet-level features (Layer 3 & 4) to distinguish benign behavior from volumetric floods and port scans. | [Kaggle: eBPF XDP Tracing](https://www.kaggle.com/datasets/ngoquy/ebpf-network-tracing-with-xdp-layer-3-and-4-only) |
| **Volumetric Flood Identification (DDoS)** | Focused specifically on identifying massive floods (SYN, UDP) in IoT and botnet environments using Cyber Range Lab traces. | [BoT-IoT Dataset](https://research.unsw.edu.au/projects/bot-iot-dataset) |
| **Traffic / Application Classification** | Identifying specific application types (e.g., YouTube vs. Zoom) by analyzing encrypted flow patterns and packet characteristics. | [UNIBS Traffic Traces](http://netweb.ing.unibs.it/~ntw/tools/traces/) |
| **Adaptive Bitrate (ABR) Prediction** | A learning task aimed at optimizing video streaming quality in real-time by predicting network throughput and buffer states. | [Stanford Puffer Results](https://puffer.stanford.edu/results/) |
| **QoS Class Identification** | Automatically categorizing traffic into priority "buckets" (VoIP, Chat, Streaming) based on behavior rather than simple port-based rules. | [ISCX VPN-nonVPN (2016)](https://www.unb.ca/cic/datasets/vpn.html) |
| **Network Event Classification** | Identifying the root cause of failures (hardware vs. software vs. attack) based on patterns in logs and headers. | [IEEE Failure Type Research](https://ieeexplore.ieee.org/document/9474482) |
| **Routing Decision Classification** | Moving beyond standard OSPF/BGP by using ML to select the "optimal" vs "non-optimal" path based on historical performance metrics. | [Kaggle: Multi-Criteria Routing](https://www.kaggle.com/datasets/ziya07/multi-criteria-network-routing-dataset) |
| **Congestion State Classification** | Categorizing the level of congestion (Transient Burst vs. Systemic Overload) to trigger proactive mitigation strategies. | *Task: Multi-class Classification* |
| **Queue Length Prediction** | A time-series regression task that predicts the number of packets in a switch buffer at  to prevent packet loss. | *Task: Regression* |

---

### **TRUSTEE Case Study Tasks**

These specific tasks are discussed in the **TRUSTEE** paper to evaluate if models are making trustworthy decisions or just finding "shortcuts."

| Use Case | Description | Source Dataset |
| --- | --- | --- |
| **VPN vs. Non-VPN** | Classifying encrypted traffic types to ensure QoS and security policies. | [ISCX VPN-nonVPN](https://www.unb.ca/cic/datasets/vpn.html) |
| **IDS (Heartbleed/DDoS)** | Identifying specific exploits like Heartbleed and volumetric DDoS attacks. | [CIC-IDS-2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html) |
| **Mirai Botnet Anomaly** | Unsupervised detection of botnet-style traffic behavior in IoT networks. | [Kitsune Mirai Dataset](https://archive.ics.uci.edu/ml/datasets/Kitsune+Network+Attack+Dataset) |
| **IoT Device Fingerprinting** | Learning to identify specific IoT devices based on their unique communication signatures. | [UNSW-IoT Dataset](https://iotanalytics.unsw.edu.au/unsw-iotraffic.html) |
| **Adaptive Bit-rate (ABR)** | Evaluating how deep learning models adjust video quality over cellular links. | [HSDPA Norway (Pensieve)](https://github.com/hongzimao/pensieve) |

Would you like me to create a **one-page summary slide** or a **PDF report** version of this table that you can print out for your submission?
