**What is MLOps?**

MLOps stands for machine learning operations. From a high level, it's a set of practices that streamline the processes of training, deploying, and monitoring models. MLOps platform is a software platform that offer different components (tools and services) to let you practice MLOps. You'll learn more about MLOps as the course progresses.


| Purpose              | Using Conda                              | Using pip/venv                                                                |
| -------------------- | ---------------------------------------- | ----------------------------------------------------------------------------- |
| Create environment   | `conda env create -f environment.yaml`   | `python -m venv venv`                                                         |
| Activate environment | `conda activate env_name`                | `source venv/bin/activate` (Linux/macOS) or `venv\Scripts\activate` (Windows) |
| Install packages     | Listed in `.yaml` file (auto-installed)  | `pip install -r requirements.txt`                                             |
| Package manager      | Conda (manages Python + non-Python deps) | pip (Python packages only)                                                    |


For your interest, cPouta and ePouta are the IaaS cloud services at CSC, known as Finnish IT center for science. The cPouta cloud is the public cloud which is easily accessible via the Internet. The ePouta cloud is a virtual private cloud designed to meet the security requirements of handling sensitive data. Both the cPouta and ePouta clouds run on the OpenStack cloud software. The Pouta cloud services are suitable for most kinds of computational workloads and any other supporting services these workloads might need. More information can be found from CSC's documentations of the Pouta services.
