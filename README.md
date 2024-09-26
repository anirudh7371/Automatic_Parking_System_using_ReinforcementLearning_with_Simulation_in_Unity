# Automatic Parking System using Reinforcement Learning with Simulation in Unity

## Project Description
This project focuses on developing an **Automatic Parking System** using **Reinforcement Learning**. The system is trained to autonomously park a vehicle in a simulated environment built in Unity, leveraging Unity's **ML Agents** toolkit. The project aims to optimize parking accuracy and efficiency without human intervention, providing a smart solution for real-world parking challenges.

By simulating various parking scenarios, the model can learn to park in tight spaces, navigate obstacles, and adjust to different parking angles. The system has been trained using **PyTorch** and integrated with **C# scripts** in Unity for seamless simulation control.

## Technologies Used
- **PyTorch**: For training the reinforcement learning model.
- **Unity**: For creating a 3D simulation environment.
- **Unity ML-Agents Toolkit**: To bridge the machine learning model with the Unity simulation.
- **C# Scripts**: For managing Unity simulation and agent behavior.

## Project Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-repo/automatic-parking-system.git
cd automatic-parking-system
```

### 2. Install Dependencies
Make sure you have the following dependencies installed:
- **PyTorch**
- **Unity 2020.3 or later** with **ML-Agents Toolkit**
- **Python 3.6 or later**

To install Unity's ML-Agents toolkit:
```bash
pip install mlagents
```

### 3. Open the Unity Project
- Open Unity Hub, add the project folder, and launch it.
- Navigate to the `Scenes` folder and open the parking simulation scene.

### 4. Train the Model
You can initiate training using the command below:
```bash
mlagents-learn config/parking_config.yaml --run-id=parking_system_run
```
Ensure that the **parking_config.yaml** file has the appropriate hyperparameters for training your model.

### 5. Run the Simulation
Once the model is trained, run the Unity simulation to test the parking system by pressing the play button in the Unity Editor.


## Demo Video
[Watch the demo video here](https://drive.google.com/file/d/1KNuZn0s__RQFRLmdPLM1ncwvkyvCmBa8/view?usp=sharing)  


## Contributing
Contributions are welcome! Feel free to fork the repository, make enhancements, and submit pull requests.

---
