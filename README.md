---
license: cc-by-sa-4.0
---

<div style="width: 800px; margin: auto;">

<h2>Model Description</h2>
<p>“Luna AI Llama2 Uncensored” is a Llama2 based Chat model <br />fine-tuned on over 40,000 long form chat discussions <br />
  This model was fine-tuned by Tap, the creator of Luna AI. <br /> 
  The result is an enhanced Llama2 7b model that rivals ChatGPT in performance <br />across a variety of tasks.</p>
<p>This model stands out for its long responses, low hallucination rate, and absence of censorship mechanisms. <br />
  The fine-tuning process was performed on an 8x a100 80GB machine.</p>

<h2>Model Training</h2>
<p>The model was trained almost entirely on synthetic outputs. <br />
  This includes data from diverse sources such as Orca, GPT4-LLM,<br /> and a custom unreleased dataset.<br /> 
  The total volume of data encompassed over 40,000 high quality instructions.</p>
<p>Huge shoutout and acknowledgement is deserved for all the dataset creators who generously share their datasets openly.</p>

<h2>Prompt Format</h2>
<p>The model follows the Vicuna 1.1/ OpenChat format:</p>

```
USER: I have difficulties in making friends, and I really need someone to talk to. Would you be my friend?

ASSISTANT: Of course! Friends are always here for each other. What do you like to do?

```


<h2>Future Plans</h2>
<p>The model is currently being uploaded in FP16 format, <br />and there are plans to convert the model to GGML and GPTQ 4bit quantizations.</p>

<h2>Benchmark Results</h2>

||||||
|---:|---:|---:|---:|---:|
|Task|Version| Metric |Value |Stderr|
|arc_challenge|0|acc_norm|0.5512|0.0146|
|hellaswag|0||||
|mmlu|0||||
|truthfulqa_mc|1|mc2|0.4716|0.0155|
|Average|-|-|0.5114|0.0150|

<h2>Ethical considerations</h2>
<p>The data used to train the model is collected from various sources, mostly from the Web. <br /> 
  As such, it contains offensive, harmful and biased content. <br />We thus expect the model to exhibit such biases from the training data.</p>

<h2>Human life</h2>
<p>The model is not intended to inform decisions about matters central to human life, <br />and should not be used in such a way.</p>

<h2>Risks and harms</h2>
<p>Risks and harms of large language models include the generation of harmful, offensive or biased content. <br /> 
  These models are often prone to generating incorrect information, sometimes referred to as hallucinations. 
  <br /> We do not expect our model to be an exception in this regard.</p>

</div>


