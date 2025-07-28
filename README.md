# 👋 Hi, I'm Claire Li!

🎓 **Computer Science Student @ Columbia University**  
🔒 Passionate about AI/ML, NLP, and Full-Stack Development  
🌍 Building secure, intelligent software to solve real-world problems  

---

## 🚀 About Me

I'm currently a CS student at Columbia with hands-on experience in **machine learning**, **cybersecurity**, and **software & web development**. I’ve worked on everything from training U-Net models for medical imaging to leading malware analysis investigations and building AI-enabled web apps. As is true for all my projects, I love combining **technical depth** with **real-world impact**.

📌 *Ask me about training CNNs to denoise MRI images, creating a student-friendly SNAP eligibility checker, or investigating malware at MIT Beaver Works!*

---

## 🛠️ My Tech Stack

**Languages:**  
`Python` | `Java` | `C` | `JavaScript` | `TypeScript` | `HTML/CSS` | `MIPS`

**Frameworks & Tools:**  
`React.js` | `Next.js` | `Node.js` | `Git` | `Tailwind CSS` | `Linux`

**ML & Data Science:**  
`PyTorch` | `Keras` | `Pandas` | `NumPy` | `scikit-learn` | `Matplotlib` | `Seaborn` | `Tensorflow`

**Cybersecurity Tools:**  
`Kali Linux` | `Wireshark` | `REMnux` | `Metasploit` | `Burp Suite` | `Zeek` | `Volatility`

**Databases & APIs:**  
`MongoDB` | `REST APIs`

---

## 🔬 Experience

### 🧠 **Research Assistant @ University of Minnesota CMMR Lab**  
*Jul 2024 – Dec 2024*  
- Built a U-Net model using PyTorch to denoise MRI images
- Used Matlab to preprocess and become familiar with the datasets
- Conducted training and testing on supercomputer through VNC
- Tools: Python, Linux, Matlab, Git, VNC

### 💻 **Break Through Tech AI @ Cornell Tech**  
*May 2025 – August 2025*  
- Completed and received a certificate for Cornell University's ML Foundations course
- Preprocessed large datasets (windzorizing, filling missing data, one-hot-encoding, n-gram creation, lemmatization, stop word removal)
- Built and deployed classification and clustering models (KNNs, Decision Trees, Linear/Logistic Regression, CNNs etc.)
- Employed model selection, ensemble, and tuning methods to create more refined models (Cross-validation, Grid Search, Stacking, Random Forest, Gradient Boosting)
- Evaluated ML models' functionality by interpreting metrics and confusion matrices, AUC-ROC curves, etc.
- Built efficient NNs trained using stochastic gradient descent (Sentiment Analysis, Image Classification)

*August 2025 – May 2026*
- Will work with mentors in the industry along with a team of peers to apply ML knowledge to the real world in impactful ways (Project Pending)

### 🤖 **First Tech Challenge Robotics**
*2016 – 2023*
- Designed, prototyped, programmed, and assembled robot
- Implemented augmented reality and AI recognition on robot using tensorflow and Vuforia
- Utilized Java to program robot, CAD to model parts for printing and assembly
- Competed against other teams in FTC tournaments, troubleshot errors, and drafted design reports

### 🛡️ **Beaver Works Summer Institute @ MIT – Cyber Ops Class Leader**  
*Jun 2022 – Aug 2022*  
- Participated in labs, worked in fireteams, and attended lectures held by cybersecurity professionals 
- Completed execises on Hackthissite and Bandit
- Used industry tools such as VirusTotal, Metasploit, Zeek, and Wireshark, etc.
- As class leader, oversaw PCAP Investigation, Malware Analysis, Memory Dump and OSINT teams, facilitated communication between mentors and peers, organized class meetings, and kept things on schedule
- Worked with OSINT team to profile Raccoon Stealer malware and presented findings to an audience for Beaver Works' Summer Showcase

### 📊 **Data Science and Artificial Intelligence Program @ Wells Fargo**  
*Jun 2020* 
- Explored and visualized datasets using Python tools such as Pandas and MatplotLib
- Attended lectures by professionals within the Data Science industry
- Conducted statistical modeling using Python and worked in teams to conduct research and present projects
- Designed and pitched iSweat, an exercise monitoring app which utilizes machine learning and artificial intelligence to prioritize user health and experience

---

## 💡 Projects

### 🔢 [Identifying Possible Systemic Gender Discrimination Using ML](https://github.com/2023lic14/breakthroughtechai.git) *(July 2025)*
Problem: Gender discrimination is a prominent issue in America and around the world. What is a way to show it exists?

Solution: By training a neural network on US census data, we could identify, based on the accuracy of the model, if there were satistically significant differences between gender using demographic data that are not directly relate to gender such as education, occupation, income, etc. Then, by identifying a difference, we are able to investigate* whether or not systemic discrimination is present
- Faithfully followed the procedures of the ML lifecycle
- Preprocessed and conducted feature engineering on the 1994 US census data (windzorized all numerical columns, filled missing entiries, one-hot encoded all categorical colummns, removed irrelevant features, identified and addressed class imbalance, split train and test data, etc.)
- Trained using Tensorflow Keras' Sequential model with 3 hidden layers of 32, 16, and a 8 units fine-tuned to avoid over/underfitting and uses SGD to optimize performance
- After 100 epochs, accuracy testing resulted in a loss of 0.4567 and accuracy of 0.7775. Created confusion matrix identifying high count of Type II error

Conclusion: The model performed good but not great, still signifying statistical correlation between demographic information and gender identity


*It is important to conduct investigation as to which features are most strongly correlated with these results. Categories such as occupation and income may be correlated with gender in a non-discriminatory way. Next steps to do so include plotting features against the label to determine highest correlation.

**This type of ML model has the potential to be used unethically. That is not the intention of this project.

### 🔢 [Neural Network From Scratch](https://github.com/2023lic14/Neural-Network-From-Scratch.git) *(June 2025)* 
Created a convolutional neural network from scratch inside kaggle using no ML libraries, only linear algebra using NumPy, Pandas, and MatPlotLib
- Trained on the MNIST dataset, the model was able to achieve above an 80% accuracy rate, further training may allow better performance
- Yielded similar results to a model I created using Keras on the same dataset 

### 🧱 [A* NxN Rubik’s Cube Solver](https://github.com/coms2132-sp25/final-project-2023lic14.git) *(May 2025)*  
After cubing for 10+ years and still not being able to achieve a sub-20 second solve on the 3x3, I began wondering if I could create a a Python-based solver using A* that would find better solves than me. 
- Implemented an A* search algorithm using a priority queue with a custom heuristic
- Avoids redundant moves and optimizes for efficiency by using a pruning algorithm
- Uses a max height variable that corresponds to the NxN cube's God's number (the maximum number of moves needed to solve any given cube state in the least rotations)

### 🌐 [SNAP for Students](https://github.com/jaysonedu/devfest2025.git) *(Feb 2025)*
Problem: A study by UC Davis found that 19% to 56% of U.S. college students struggle with food insecurity. Many students would assume they don’t qualify, and the NYC online SNAP application is outdated and difficult to navigate. 

Solution: We created a website, SNAP for students, to make the process more digestible. Our site is a full-stack website to simplify SNAP benefits access for students  
- Built the frontend using React.js, Next.js, TypeScript, Tailwind CSS, HTML, and JavaScript
- Designed and implemented a MongoDB-powered forum with comment-liking, upvoting/downvoting, post sorting, and reply features and utilized Node.js for backend functionality 
- Integrated an OpenAI-powered chatbot with prompt engineering and eligibility quiz to help users determine SNAP qualification

### 🧾 HTTP 1.0 Web Server in C *(Dec 2024)*  
Built a TCP-based HTTP server from scratch in C  
- Handles static + dynamic content, error handling, and logging  
- Implements directory traversal protection and IP tracking

### 🔤 Anagrams Finder *(May 2024)*  
Java program to find anagrams using advanced data structures  
- Used Hashmaps, Red-Black Trees, and Linked Lists for fast lookup

### 🌱 [Eco Escape](https://github.com/2023lic14/Eco-Escape.git) *(Feb 2024)* 
Created a simple environment-themed puzzle game that combines my love for escape rooms with environmental awareness
- Programmed using Python Kivy and hosted as a website on Google Cloud Platform with a bucket and load balancer
- Illustrated all visual elements

 ### 🗣️ Semantic Role Labeling with BERT *(Nov 2024)* 
 - Developed a deep learning model in Python using PyTorch and Hugging Face's Transformers library to perform Semantic Role Labeling
 - Fine-tuned a BERT model on OntoNotes 5.0 dataset, using contextual embeddings for sequence labeling
 - Implemented tokenization and BIO-tag alignment, ensuring accurate mapping of subwords to semantic roles
 - Trained and evaluated the model, achieving high accuracy and F1-score

### 🎰 Handheld Slot Machine *(Sep 2023 - Nov 2023)* 
Created a fully functional handheld slot machine that had working lights, music, a gear system, and laser coin detection to be presented at Columbia's Art of Engineering fair
- Designed, 3D-printed, and laser-cut parts
- Wired and programmed multiple Arduino Uno R3

### 🚀 Miniature Rocket *(Sep 2023)* 
Created a launchable ~16” rocket with an engine and extendable glider, designed parts using SolidWorks, 3D printed and laser cut parts
- Launch height ~70 feet
- Landed cleanly with no damage to the rocket

---

## 💼 Leadership & Activities

- 📣 Event Coordinator – Women in Computer Science (WiCS)  
- 🚀 Columbia Space Initiative & App Development Initiative  
- 🎮 Team Leader – Columbia Tetris League (Top 12% player globally on TETR.IO)  
- 📚 Math Tutor – Reading Team Math  

---

## 📫 Connect With Me

📧 Email: [ccl2180@columbia.edu](mailto:ccl2180@columbia.edu)  
🌐 GitHub: [github.com/2023lic14](https://github.com/2023lic14)

---

## ☕ Fun Fact

Always down for a **Maiko Matcha Soft Serve** and always looking to talk about my super cool (albiet not very large) **Charizard Pokémon card collection**!

---

_Thanks for stopping by! 🚀_
