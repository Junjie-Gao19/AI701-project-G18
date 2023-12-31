# AI701-project-G18
## Abstract
With the advancement of large model technology, contemporary mainstream large models exhibit robust reasoning and conversational capabilities. While these technologies bring convenience, they also harbor significant security risks, as they could potentially be manipulated by malicious actors to generate harmful content detrimental to society. Therefore, identifying model security vulnerabilities and mitigating them are paramount. 
This paper proposes a nested prompt approach to hypnotize the model, providing it with virtual scenarios and antagonists to thwart, thereby achieving jailbreaks and generating harmful information.

## Getting Started
You should have an environment,you can run
```
pip install -r requirements.txt
```
If you want to run the close source models,you should export your own API key.
```
export OPENAI_API_KEY=[YOUR_API]
```
## Run experiments
To run the code,run
```
python main.py --target-model[TARGET MODEL] --exp_name[EXPERIMENT NAME] --DEFENSE[DEFENSE TYPE]
```
You can read the code to get the default Init.If you don't want to choose the paramaters,you can run
```
python main.py
```
If you want run the close source models you should add your own model path in the `config.py`. 
The results will appear in the `results`,we have put some results in it.
