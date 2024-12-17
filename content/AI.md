---
aliases:
  - Machine Learning
  - ML
  - Artificial Intelligence
---

## What?
- Teach a computer to perform tasks without explicitly programming all the rules. (🧠 "Learn by Example").
	- Sometimes, we're trying to teach the computer even though we [[Algorithm Distillation|know all of the rules]].
- Works by finding patterns in data (***Generalisation***).
- ***Core objective***: Minimise error on unseen data (***Accuracy*** vs ***Overfitting***).
- Encompasses [[Supervised Learning]], [[Unsupervised Learning]], [[Reinforcement Learning]].

### Core Concepts:
1. **Training Data**: A dataset of inputs (features) and outputs (labels or structure). 
   - Assumes the data is representative of the problem space. 
   - Data quality directly impacts performance (***Garbage In, Garbage Out***). 
2. **Model**: A mathematical [[Neural Networks as Function Finders|function]] mapping inputs to outputs (e.g., [[Linear Regression|Linear]] or [[Neural Networks]]).
   - **Hypothesis Space**: All possible functions the model can explore. Relates to [[Computability]]
3. **Learning Algorithm**: Finds the best function by iteratively minimising a loss function. Typically [[Backpropagation]]
4. **Loss Function**: Quantifies how far the model’s predictions are from the truth.
   - Examples: [[Estimators|MSE]] (for regression), [[Cross-Entropy Loss]] (for classification).
5. **Evaluation**: Use metrics (e.g., [[Precision vs Recall]]) on a hold-out dataset to test generalisation.

> [!caution] Just Saying!
> There's a lot of dead links on this page. I'm working on it. 
---
### Types of Machine Learning:
1. [[Supervised Learning]]
2. [[Unsupervised Learning]]
3. [[Reinforcement Learning]]

---

### How It Works:
1. Prepare a dataset (cleaning, normalising, splitting into [[Train-Test Split]]).
2. Choose a model based on the task (e.g., [[Decision Trees]], [[Support Vector Machines]]).
3. Train the model: Minimise the loss function using an optimisation method like [[Gradient Descent]].
4. Evaluate and tune (e.g., [[Hyperparameter Optimisation]]).
5. Deploy the trained model for predictions. 

---

### Challenges:
- **Bias and Variance Trade-off**: Models too simple (high bias) vs too complex (high variance).
- **Overfitting**: Performs well on training data but poorly on new data. (Solution: [[Regularisation]], early stopping, or more data.)
- **Underfitting**: Model fails to capture patterns in data. 

### Security Concerns:
- **Adversarial Attacks**: Small, deliberate changes to input can mislead a model (e.g., fooling an image classifier).
- **Data Poisoning**: Injecting corrupted data during training to bias the model.
- **Privacy**: Sensitive data in training might be reverse-engineered.

---

## *"How Do I Learn AI?"*:

> [!caution] Hol' Up
> This is by no means the most efficient way of learning ML. It's adjacent to how I learned it. Ruthlessly [[Learning|ask questions]] and follow every rabbit whole you encounter.

1. Dive into the world first. 
	1. Watch / Read:
		1. [AI 2041](https://www.penguin.co.uk/books/445514/ai-2041-by-qiufan-kai-fu-lee-and-chen/9780753559024)
		2. [Machine of Loving Grace](https://darioamodei.com/machines-of-loving-grace)
		3. [Leopold Aschenbrenner](https://www.youtube.com/watch?v=zdbVtZIn9IM) on Dwarkesh Patel
	3. Follow:
		1. [Hackernews](https://news.ycombinator.com), 
		2. [AI Explained](https://www.youtube.com/@aiexplained-official), 
		3. [[Andrej Karpathy|Andrej]] [Karpathy](https://x.com/karpathy), 
		4. [Noam Brown](https://x.com/polynoamial)
	4. There's so many more to even list.
3. Learn how to code with Pandas. If you don't know how:
	1. ***Do not use [[ChatGPT in Education|ChatGPT]] for the following.***
	2. Spin up a Google CoLab for Python. 
	3. Watch this entire [YouTube video](https://youtu.be/rfscVS0vtbw?si=-FbeXP0X9NdubI6W) in full. Watch it in 2x. 
		1. Build something you want to build as you watch the video. (EG. Terminal based calculator, a dummy authentication service (bonus points if you learn about and implement [[Cryptographic Hash Functions|hashing]], etc.). The point here is creativity and building something you really want to build). 
4. Watch the following:
	1. [3Blue1Brown DeepLearning Series](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
	2. Watch and Do Andrej Karpathy's tutorials / videos ([here](https://www.youtube.com/watch?v=zjkBMFhNj_g), [here](https://www.youtube.com/watch?v=kCc8FmEb1nY), [here](https://youtu.be/zduSFxRajkE?si=P8X9-ClP4bT3ni5z))
5. Pick something you're interested in the [[AI]] (Eg [[Computer Vision]], [[Language]], etc.)
	1. Take vision for example. 
	2. Decide to be able to detect if your face, live on your webcam, is happy, or sad or whatever. 
	3. Look online for blogs of people doing this and showing how they did it. 
6. Do [[EdinburghAI|EdinburghAI's]] workshops (available [here](https://github.com/EdinburghAI/workshops)). Instructions are available on the ReadMe. For the theory, watch YouTube videos (we've unfortunately not made the videos live lol). 
7. Pick a dataset from [Kaggle](https://www.kaggle.com/datasets). 
	3. Ask a question about the data and try to answer it programmatically. EG:
		1. Given a dataset on English movie reviews and whether they were positive or negative, could you come up with a model that takes a review and says if it's positive or negative?
		2. Given a dataset of different countries, their GDP, average years schooling, average BMI etc, make a bunch of graphs that compares 2 different criteria. Eg. Average BMI vs Life Expectancy
			1. As an additional step, could you come up with a model that given an average BMI (and all of the other factors), you predict their life expectancy.
8. If you've just done everything here, you've simply dipped your toes in. Every step you take, ask "*why?*" until you're stopped by the laws of physics. Follow every question you have. Commit to [[Personal Projects|building]] something before you even know how to build it. 

### Some of My Notes:

> I don't actively add to this list, so there's a lot more notes on ML that aren't here.


- [[Reinforcement Learning from Human Feedback (RLHF)]]
- [[Algorithm Distillation]]
- [[Turing Test]]
- [[Large Language Models (LLMs)]]
- [[AlphaGo]]
- [[Attention (AI)]]
- [[Autonomous Vehicles]]
- [[AV's Modelling People - A Pro Or Con]]
- [[Constitutional AI (RLAIF)]]
- [[Containment]]
- [[Data Imbalance in Machine Learning]]
- [[Google DeepMind]]
- [[EdinburghAI]]
- [[Exploratory Data Analysis]]
- [[For The Love Of Machines]]
- [[Intelligence]]
- [[MAYA]]
- [[Neural Network]]
- [[Reinforcement Learning]]
- [[Segmenting Speech or Language]]
- [[SLAM]]
- [[Transformer]]
- [[Wicklephones]]