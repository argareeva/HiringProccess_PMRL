# undergraduate_thesis

Undegraduate Thesis is devoted to the analysis of the hiring process using the methods of Process Mining and Reinforcement Learning algorithms. 

The project uses real data converted into the required format. The analysis consists of constructing a process graph, identifying bottlenecks and modeling various scenarios for its optimization.

## Libraries installation and running the project

To start a project, you need to:

1. Install Python 3.10

`brew install python@3.10`

`python3.10 --version`

3. Create a virtual environment

`python3.10 -m venv venv`

`source venv/bin/activate  # Linux/macOS`

`.\\venv\\Scripts\\activate  # Windows`

`pip install --upgrade pip setuptools wheel`

4. Install necessary libraries

`pip install sberpm streamlit pandas numpy matplotlib graphviz gymnasium`

5. Download and unzip the archive from the link [https://github.com/argareeva/undergraduate_thesis].

6. Launch the application by going to the desired folder on your device:

`cd / .. /app`

`streamlit run app.py`

7. Go to browser at local address

8. Download test data. Available in the current repository named HR_log_obezlich.csv.
