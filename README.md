<img src="banner.png" alt="Claire Li banner" style="width:100%;"/>

<table style="width: 100%; margin-top: 20px;">
  <tr>
    <td style="width: 180px; vertical-align: top;">
      <img src="pfp.png" width="160" style="border-radius: 50%; display: block; margin: auto;" alt="Claire Li" />
    </td>
    <td style="padding-left: 20px;">
      <h1 style="margin-bottom: 10px;">👋 Hi, I'm Claire Li!</h1>
      <p>
        🎓 <strong>Computer Science Student @ Columbia University</strong><br>
        🔒 Passionate about AI/ML, NLP, and Full-Stack Development<br>
        🌍 Building secure, intelligent software to solve real-world problems
      </p>
    </td>
  </tr>
</table>

---

## 🚀 About Me

I'm currently a CS student at Columbia with hands-on experience in **machine learning**, **cybersecurity**, and **software & web development**. I’ve worked on everything from training U-Net models for medical imaging to leading malware analysis investigations and building AI-enabled web apps. As is true for all my projects, I love combining **technical depth** with **real-world impact**.

Aside from CS, I love playing video games and board games, drawing, cubing, and traveling! Ask me about **Tetris** or my recent trip to **Peru**!

---

## 🛠️ My Tech Stack

**Languages:**  
`Python` | `Java` | `C` | `JavaScript` | `TypeScript` | `HTML/CSS` | `MIPS` | `Shell Script/Bash`

**Frameworks & Tools:**  
`React.js` | `Next.js` | `Node.js` | `Git` | `Tailwind CSS` | `Linux` | `SolidWorks` | `Autodesk CAD` | `MATLAB`

**ML & Data Science:**  
`PyTorch` | `Keras` | `Pandas` | `NumPy` | `Scikit-Learn` | `Matplotlib` | `Seaborn` 

**Cybersecurity Tools:**  
`Kali Linux` | `Wireshark` | `REMnux` | `Metasploit` | `Burp Suite` | `Zeek` | `Volatility` | `VirusTotal` | `Joe's Sandbox` | `WHOIS` | `Threatminer` | `AnyRun`

**Databases & APIs:**  
`MongoDB` | `REST APIs` | `OpenAI API`

---

## 🔬 Experience

### 💻 **Break Through Tech AI @ Cornell Tech**  
*May 2025 – August 2025*  
- Completed and received a certificate for Cornell University's ML Foundations course
- Preprocessed large datasets (windsorizing, filling missing data, one-hot-encoding, n-gram creation, lemmatization, stop word removal)
- Built and deployed classification and clustering models (KNNs, Decision Trees, Linear/Logistic Regression, CNNs etc.)
- Employed model selection, ensemble, and tuning methods to create more refined models (Cross-validation, Grid Search, Stacking, Random Forest, Gradient Boosting)
- Evaluated ML models' functionality by interpreting metrics and confusion matrices, AUC-ROC curves, etc.
- Built efficient NNs trained using stochastic gradient descent (Sentiment Analysis, Image Classification)

*August 2025 – May 2026*
- Will work with mentors in the industry along with a team of peers to apply ML knowledge to the real world in impactful ways (Project Pending)

### 🧠 **Research Assistant @ University of Minnesota CMMR Lab**  
*Jul 2024 – Dec 2024*  
- Built a U-Net model using PyTorch to denoise MRI images
- Used Matlab to preprocess and become familiar with the datasets
- Conducted training and testing on supercomputer through VNC
- Tools: Python, Linux, Matlab, Git, VNC

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

### 🕵️‍♀️ [Identifying Possible Systemic Gender Discrimination Using ML](https://github.com/2023lic14/breakthroughtechai) *(July 2025)*
Problem: Gender discrimination is a prominent issue in America. What is a way to show it exists?

Solution: By training a neural network on US census data, we could identify, based on the accuracy of the model, if there were statistically significant differences between gender using demographic data that are not directly relate to gender such as education, occupation, income, etc. Then, by identifying a difference, we are able to investigate* whether or not systemic discrimination is present

> *This project is exploratory and not intended to assign causality. Further investigation is necessary to interpret correlations ethically and accurately.*

- Faithfully followed the procedures of the ML lifecycle
- Preprocessed and conducted feature engineering on the 1994 US census data (windzorized all numerical columns, filled missing entries, one-hot encoded all categorical columns, removed irrelevant features, identified and addressed class imbalance, split train and test data, etc.)
- Trained using Tensorflow Keras' Sequential model with 3 hidden layers of 32, 16, and a 8 units fine-tuned to avoid over/underfitting and uses SGD to optimize performance
- After 100 epochs, accuracy testing resulted in a loss of 0.4567 and accuracy of 0.7775. Created confusion matrix identifying high count of Type II error

Conclusion: The model performed well, though not exceptionally, still signifying statistical correlation between demographic information and gender identity**


*It is important to conduct investigation as to which features are most strongly correlated with these results. Categories such as occupation and income may be correlated with gender in a non-discriminatory way. Next steps to do so include plotting features against the label to determine highest correlation.

**This type of ML model has the potential to be used unethically. That is not the intention of this project.

### 🔢 [Neural Network From Scratch](https://github.com/2023lic14/Neural-Network-From-Scratch) *(June 2025)* 
Created a convolutional neural network from scratch inside kaggle using no ML libraries, only linear algebra using NumPy, Pandas, and MatPlotLib
- Trained on the MNIST dataset, the model was able to achieve above an 80% accuracy rate, further training may allow better performance
- Yielded similar results to a model I created using Keras on the same dataset 

### 🧱 [A* NxN Rubik’s Cube Solver](https://github.com/coms2132-sp25/final-project-2023lic14) *(May 2025)*  
After cubing for 10+ years and still not being able to achieve a sub-20 second solve on the 3x3, I began wondering if I could create a a Python-based solver using A* that would find better solves than me. 
- Implemented an A* search algorithm using a priority queue with a custom heuristic
- Avoids redundant moves and optimizes for efficiency by using a pruning algorithm
- Uses a max height variable that corresponds to the NxN cube's God's number (the maximum number of moves needed to solve any given cube state in the least rotations)

### 🌐 [SNAP for Students](https://github.com/jaysonedu/devfest2025) *(Feb 2025)*
Problem: A study by UC Davis found that 19% to 56% of U.S. college students struggle with food insecurity. Many students would assume they don’t qualify, and the NYC online SNAP application is outdated and difficult to navigate. 

Solution: We created a website, SNAP for students, to make the process more digestible. Our site is a full-stack website to simplify SNAP benefits access for students  
- Built the frontend using React.js, Next.js, TypeScript, Tailwind CSS, HTML, and JavaScript
- Designed and implemented a MongoDB-powered forum with comment-liking, upvoting/downvoting, post sorting, and reply features and utilized Node.js for backend functionality 
- Integrated an OpenAI-powered chatbot with prompt engineering and eligibility quiz to help users determine SNAP qualification

### 🧾 HTTP 1.0 Web Server in C *(Dec 2024)*  
Built a TCP-based HTTP server from scratch in C  
- Handles static + dynamic content, error handling, and logging 
- Implements directory traversal protection and IP tracking
- Manages all memory manually using malloc() and free(), demonstrating in-depth understanding of memory allocation.
- Runs on command line, demonstrating high level understanding of low level code, file reading/writing, TCP sockets, stdin/stdout/stderr, REST API etc.

### 🗣️ Semantic Role Labeling with BERT *(Nov 2024)* 
 - Developed a deep learning model in Python using PyTorch and Hugging Face's Transformers library to perform Semantic Role Labeling
 - Fine-tuned a BERT model on OntoNotes 5.0 dataset, using contextual embeddings for sequence labeling
 - Implemented tokenization and BIO-tag alignment, ensuring accurate mapping of subwords to semantic roles
 - Trained and evaluated the model, achieving high accuracy and F1-score

### 🔤 Anagrams Finder *(May 2024)*  
Created a Java program to find anagrams using advanced data structures  
- Built Hashmaps, Red-Black Trees, and Linked Lists from scratch to create 3 different ways to find anagrams
- Took user input for data structure and word, and produced all anagrams from a dictionary.txt file

### 🌱 [Eco Escape](https://github.com/2023lic14/Eco-Escape) *(Feb 2024)* 
Created a simple environment-themed puzzle game that combines my love for escape rooms with environmental awareness
- Programmed using Python Kivy and hosted as a website on Google Cloud Platform with a bucket and load balancer
- Illustrated all visual elements

### 🎰 Handheld Slot Machine *(Sep 2023 - Nov 2023)* 
Created a fully functional handheld slot machine that had working lights, music, a gear system, and laser coin detection to be presented at Columbia's Art of Engineering fair
- Designed, 3D-printed, and laser-cut parts
- Wired and programmed multiple Arduino Uno R3

### 🚀 Miniature Rocket *(Sep 2023)* 
Created a launchable ~16” rocket with an engine and extendable glider, designed parts using SolidWorks, 3D printed and laser cut parts
- Launch height ~70 feet
- Landed well with no damage to the rocket

---

## 💼 Leadership & Activities

- 📣 Event Coordinator – Women in Computer Science (WiCS)  
- 🚀 Columbia Space Initiative
- 👩🏻‍💻 Columbia App Development Initiative  
- 🎮 Team Leader – Columbia Tetris League
- 📚 Math Tutor – Reading Team Math

---

## 📫 Connect With Me

📧 Email: [ccl2180@columbia.edu](mailto:ccl2180@columbia.edu)  
🌐 GitHub: [github.com/2023lic14](https://github.com/2023lic14)  
👥 LinkedIn: [https://www.linkedin.com/in/claire-li-178152272/](https://www.linkedin.com/in/claire-li-178152272/)

---

## ☕ Fun Fact

Always down for a **Maiko Matcha Soft Serve** and always looking to talk about my super cool (albeit not very large) **Charizard Pokémon card collection**!

---

_Thanks for stopping by! 🚀_
