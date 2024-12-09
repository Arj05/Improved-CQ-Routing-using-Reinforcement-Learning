# Routing Optimization with Deep Q-Network (DQN)

## **Overview**
Reinforcement learning approach to route optimization using Deep Q-Network for solving location routing problems.

## **Features**
- **Deep Q-Network** for route optimization
- **Dynamic routing environment**
- **Adaptive exploration strategy**
- **Performance evaluation metrics**

## **Prerequisites**
- Python 3.8+
- PyTorch
- NumPy
- Pandas
- Matplotlib

## **Installation**
```bash
git clone https://github.com/yourusername/routing-optimization.git
pip install -r requirements.txt
```

## **Usage**
1. Prepare dataset in `.intra` format
2. Run `main()` function 
3. Upload `weights-dist.tar` file when prompted

## **Dataset Requirements**
- Columns: Origin, Destination, Weight
- Supports location names with spaces/special characters

## **Key Components**
- `RoutingEnvironment`: Manages routing simulation
- `DQNAgent`: Implements reinforcement learning logic
- `train_routing_model()`: Trains the routing model
- `evaluate_model()`: Assesses model performance

## **Performance Metrics**
- Average Reward
- Reward Standard Deviation
- 95% Confidence Interval

## **Visualization**
Generates plots showing:
- Training Rewards
- Evaluation Rewards Distribution

## **License**
MIT License
