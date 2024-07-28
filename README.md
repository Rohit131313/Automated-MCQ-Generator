# Automated MCQ Generator


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/Rohit131313/Automated-MCQ-Generator.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mcq python=3.8 -y
```

```bash
conda activate mcq
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone credentials as follows:

```ini
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


### Run the following command
```bash
streamlit run StreamLitAPP.py --server.port 8000
```

Now,
```bash
open up localhost:8000
```



