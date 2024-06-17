# ADWiFi

This project is based on [mowa-wifi-sensing](https://github.com/oss-inc/mowa-wifi-sensing)

<br>

## Team Members
| 김다연 | 김유정 | 김원우 | 김주호 | 황고은 |
|----------------|------------------|------------------------|-------------------------|-------------------------|

<br>

## Activity Classes
- Empty (default)
- Fall
- Sit
- Stand
- Walk

---

### 1. Server
**Computing environment**
- Window11
- Python 3.8

---

### 2. Extractor
**Computing environment**
- Rasbian 2022-01-28-raspios-bullseye-armhf
- Raspberrypi 3B+, RaspberryPi 4B
  
---

<br>

## Process
#### Data Processing
- Collect CSI data from Raspberry Pi Wi-Fi chips using the Nexmon CSI Extractor. 
- The collected CSI data is delivered to the server via socket communication

<br>

#### Model Design
Supervised Learning (SVL)
- A Supervised-learning-based model, trained using pre-labeled data.
Few-Shot Learning (FSL)
- It is a Meta-learning-based model that can quickly perform learning on new classes with a small amount of data



