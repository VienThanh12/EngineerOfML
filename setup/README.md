**What is MLOps?**

MLOps stands for machine learning operations. From a high level, it's a set of practices that streamline the processes of training, deploying, and monitoring models. MLOps platform is a software platform that offer different components (tools and services) to let you practice MLOps. You'll learn more about MLOps as the course progresses.


| Purpose              | Using Conda                              | Using pip/venv                                                                |
| -------------------- | ---------------------------------------- | ----------------------------------------------------------------------------- |
| Create environment   | `conda env create -f environment.yaml`   | `python -m venv venv`                                                         |
| Activate environment | `conda activate env_name`                | `source venv/bin/activate` (Linux/macOS) or `venv\Scripts\activate` (Windows) |
| Install packages     | Listed in `.yaml` file (auto-installed)  | `pip install -r requirements.txt`                                             |
| Package manager      | Conda (manages Python + non-Python deps) | pip (Python packages only)                                                    |
