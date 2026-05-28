# IRS-Urban-Tracking-System

## AI-Driven Urban User Tracking and Communication Optimization Using Intelligent Reflecting Surfaces (IRS)

---

## Overview

This project presents a mobility-aware urban wireless communication and user tracking framework using Intelligent Reflecting Surfaces (IRS) and Integrated Sensing and Communication (ISAC) concepts.

The system simulates dynamic urban user movement, LOS/NLOS propagation conditions, IRS-assisted communication, beam steering, and SNR optimization in a realistic road-grid environment.

The objective is to improve communication reliability and tracking performance in dense urban scenarios.

---

## Key Features

- Urban road-grid mobility model
- Dynamic moving users/targets
- IRS-assisted wireless communication
- Beam steering optimization
- LOS/NLOS environment modeling
- SNR improvement analysis
- Outage probability evaluation
- IRS vs Non-IRS comparison
- Real-time visualization and animation
- Mobility-aware communication system
- Multi-user support framework

---

## System Architecture

The communication environment consists of:

- Base Station (BS)
- Intelligent Reflecting Surfaces (IRS)
- Mobile users/targets
- Urban obstacles/buildings
- Dynamic wireless channels

IRS units are strategically placed at selected urban intersections to improve signal quality and communication coverage.

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

---

## Simulation Components

### 1. User Mobility
- Grid-based urban movement
- Random directional mobility
- Dynamic trajectory generation

### 2. Wireless Communication
- Direct BS-user communication
- IRS-assisted reflected communication
- Path loss modeling
- Fading effects

### 3. Beam Steering
- Adaptive phase optimization
- Signal enhancement using IRS reflection control

### 4. Performance Metrics
- Signal-to-Noise Ratio (SNR)
- Mean SNR
- Outage Probability
- Communication reliability

---

## Results

The simulation demonstrates:

- Improved SNR using IRS
- Enhanced communication coverage
- Better signal reliability
- Reduced outage probability
- Efficient user tracking in urban environments

---

## Visualization

The project includes:

- Real-time user movement animation
- IRS and BS visualisation
- LOS/NLOS communication paths
- Live SNR plotting
- Performance comparison graphs

---

## Project Structure

```text
IRS-Urban-Tracking-System/
│
├── notebooks/
│   ├── simulation.ipynb
│
├── results/
│   ├── SNR, Throughput and Effective gain with and without IRSs.png
│   ├── result-simulation.mp4
│   ├── tracking-error.png
│   ├── tracking-result.png
│
├── presentation/
│   ├── Final_presentation.pptx
│
├── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Pankajsarawat/IRS-Based-Urban-Tracking-System.git
```

Move into the project directory:

```bash
cd IRS-Urban-Tracking-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Run the Jupyter notebook:

```bash
jupyter notebook
```

Open:

```text
simulation.ipynb
```

---

## Future Improvements

- Deep Reinforcement Learning (DRL)-based beam optimization
- Real-world mobility datasets
- Multi-IRS deployment
- Vehicular communication integration
- 6G-oriented ISAC framework
- Advanced channel estimation techniques

---

## Research Domains

- Wireless Communication
- Intelligent Reflecting Surfaces (IRS)
- ISAC
- Smart Cities
- Mobility-aware Networks
- Beamforming
- Urban Communication Systems

---

## Authors

- Pankaj Saraswat
- Jitendra Kumar Dubey

---

## License

This project is developed for academic and research purposes.
