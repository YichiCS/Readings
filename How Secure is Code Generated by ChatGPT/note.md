# Reading of How Secure is Code Generated by ChatGPT? 

There 7 parts in this paper in total, know I try to write an brief summary for each part.

## Inreoduction  

This part introduct the current development of the LLM, including its performance in tasks like NLP, NLU, MT and so on. Next, the generation of chatGPT and its downstream applications are described.

## Methodology  

In this study, author asked ChatGPT to generate 21 programs, using a variety of programming languages. The programs generated serve a diversity of purpose, and each program was chosen to highlight risks of a specific vulnerability.  

Then prodded ChatGPT about the security of the code it produced. Whenever a vulnerability was evident, author created an input that triggers the vulnerability and asked ChatGPT the sentence below:

```
The code behaves unexpectedly when fed the following input: <input>. What causes this behavior? 
```

Finally the author evaluates the generated codes to check if they comply with the requirements of secure.

## Dataset and the Analysis of the generated codes  

This table contains the 21 tasks that generated the code and the results of the evaluation of the generated code.

![table1](pic0.png)

The next part is the analysis of each task and the evaluation of the generated code.

## Conlusions

The first and most important conclusion that can be drawn
from this experiment is that ChatGPT frequently produces
insecure code.  

Although ChatGPT cannot generate attack code (either for ethical or capability reasons), it is not difficult to surmise that one conclusion is that ChatGPT can only protect against attacks it can understand.

The current ChatGPT generation of robust code relies on two things: the understanding and prevention of the problem while ChatGPT is being generated, and the testing and tuning of it in the post-conversation using the prompt.  

Another crucial point is that ChatGPT does not guarantee the privacy of the code when it is generated, and it may combine the results of interaction with other users to generate similar or even identical code, which is a fatal flaw in areas such as military industry and finance.  

The last point is the lack of interpretability of ChatGPT's code generation process. The generated code is affected by the previous interaction process and it has not been possible to determine how the different prompts affect the generation.

Summarized and organized some related code generation work.

## Threats to validity
The main limitations of this study are the following:
* Research and experiments for specific ChatGPT versions have now resulted in the launch of LLM with more parameters and greater capabilities
* Lack of interpretability of the model
* Experiments target too few questions and language, and results are randomized.