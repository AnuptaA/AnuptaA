```
    ___                        __           
   /   |  ____  __  ______  __/ /_____     
  / /| | / __ \/ / / / __ \/_  __/ __ `/    
 / ___ |/ / / / /_/ / /_/ / / / / /_/ /     
/_/  |_/_/ /_/\__,_/ .___/ /_/  \__,_/      
                  /_/                        
╔═══════════════════════════════════════════╗
║  CS @ Princeton University ('26)          ║
║  anupta@princeton.edu                     ║
╚═══════════════════════════════════════════╝
```
---

```python
$ cat student.py

class PrincetonStudent:
    def __init__(self):
        self.name = "Anupta Argo"
        self.university = "Princeton University"
        self.degree = {
            "major": "Computer Science (BSE)",
            "minor": "Statistics & Machine Learning",
            "graduating_class": 2026
        }
        self.current_research = ["distributed_systems"]
        self.locations = ["Philadelphia, PA", "Princeton, NJ"]
        
    def current_coursework(self):
        current = [
            "Computer Networks",
            "Distributed Systems Thesis", 
            "Human Computer Interaction",
        ]
        return {"current": current}

# Initialize student
student = PrincetonStudent()
print(f"Welcome to {student.name}'s profile!")
```
---

```bash
$ find /princeton/relevant_courses -name "*.completed" -exec basename {} .completed \;

Algorithms_and_Data_Structures
Reasoning_About_Computation
Economics_and_Computing
Algorithms_for_Computational_Biology
Advanced_Programming_Techniques
Intro_to_Programming_Systems
Distributed_Systems
Computer_Architecture
Contemporary_Logic_Design
Intro_to_Machine_Learning
Natural_Language_Processing
Intro_to_Data_Science
Multivariate_Statistics
Optimization
```
---
```bash
$ ssh anupta@contact-server

Last login: Sun Aug 17 12:34:56 2025 from princeton.edu

anupta@contact-server:~$ cat /etc/motd
===============================================
 Get in contact with me!
===============================================

anupta@contact-server:~$ ls -la /usr/local/bin/
total 16
-rwxr-xr-x 1 anupta anupta 4096 Aug 17 12:34 linkedin -> https://linkedin.com/in/anupta-argo
-rwxr-xr-x 1 anupta anupta 4096 Aug 17 12:34 leetcode -> https://leetcode.com/anupta
-rwxr-xr-x 1 anupta anupta 4096 Aug 17 12:34 portfolio -> https://anuptaa.github.io/portfolio
-rwxr-xr-x 1 anupta anupta 4096 Aug 17 12:34 email -> mailto:anupta@princeton.edu

anupta@contact-server:~$ exit
Connection to contact-server closed.
```
---
```bash
$ ls -la ~/languages/

total 42
drwxr-xr-x  7 anupta princeton  224 Aug 17 2024 .
drwxr-xr-x  3 anupta princeton   96 Aug 17 2024 ..

-rwxr-xr-x  1 anupta princeton 8.5K Aug 17 2024 java*
-rwxr-xr-x  1 anupta princeton 8.2K Aug 17 2024 python*
-rwxr-xr-x  1 anupta princeton 7.8K Aug 17 2024 cpp*
-rwxr-xr-x  1 anupta princeton 6.1K Aug 17 2024 go*
-rwxr-xr-x  1 anupta princeton 7.9K Aug 17 2024 javascript*
-rwxr-xr-x  1 anupta princeton 7.1K Aug 17 2024 typescript*
-rwxr-xr-x  1 anupta princeton 5.4K Aug 17 2024 r*
-rwxr-xr-x  1 anupta princeton 6.3K Aug 17 2024 sql*
-rwxr-xr-x  1 anupta princeton 4.2K Aug 17 2024 bash*
```
---
```bash
$ cat ~/tech_stack/frameworks.txt

Frontend Framework:
├── React
├── Next.js
├── Svelte
└── TailwindCSS

Backend & API Layer:
├── Node.js + Express
├── Flask
├── FastAPI
└── RESTful Design

Data & ML Pipeline:
├── TensorFlow
├── PyTorch
├── OpenCV
├── pandas + NumPy
├── Matplotlib
└── OpenCLIP

DevOps & Infrastructure:
├── Docker
├── AWS S3
├── Git/GitHub
├── Render
└── Aidbox
```
---
```bash
$ top -u anupta

PID    USER     %CPU  %MEM  TIME+    COMMAND
2847   anupta   23.7   8.4  15:23.45 systems_programming
2848   anupta   18.2   6.1  12:17.33 algorithm_optimization  
2849   anupta   15.9   5.7  09:42.18 weird_side_projects
2850   anupta   12.4   4.3  07:28.91 obscure_problem_solving
2851   anupta   10.8   3.9  06:15.47 ml_workflows
2852   anupta    8.3   2.1  04:32.12 network_programming
2853   anupta    6.7   1.8  03:21.05 resolving_race_conditions
2854   anupta    4.2   1.2  02:14.38 web_development
```
---
