## Commands needs to follow

## Below command is for windows(CMD)

```
mkdir <project_folder_name>
```

```
cd <project_folder_name>
```

```
code .
```

## This is for conda env setup

```
conda create -p <env_name> python=3.10 -y
```

```
conda activate <path_of_the_env>
```

```
pip install -r requirements.txt
```

## git commands(this commands is for the later uses)

```
git init
```

```
git add .
```

```
git commit -m "<write your commit message>"
```

```
git push
```

## For cloning repo use this command
```
git clone https://github.com/sunnysavita10/document_portal
```
### Minimum requirement for this project
Using these we will create a RAG pipeline.

1. LLM Model ## you can load it from groq(free), openai(paid), gemini(15 days free), claude(paid), huggingface(free), ollama (local setup, you need good configuration)

2. Embedding model ## openai, hf, gemini

3. Vectordatabase ## inmemory  ## ondisk ## cloudbased (aws bedrock)


### AWS secret manager - secret vault, similar to Azure keybolt
For deployment we use AWS, not .env

### .env to store the key values - Environment variables
it is in .gitignore, we will store confidential informations, cannot be shared.
