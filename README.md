# Exno-2-Prompt-Engg

# Ex.No: 2 	Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta 
### DATE:                                                                            
### REGISTER NUMBER : 212222230152
 
### Aim:
To compare the performance, user experience, and response quality of different AI platforms (ChatGPT, Claude, Bard, Cohere Command, and Meta) within a specific use case, such as summarizing text or answering technical questions. Generate a Prompt based output using different Prompting tools of 2024.

### Algorithm:
Define the Use Case:
Select a specific task for evaluation across platforms (e.g., summarizing a document, answering a technical question, or generating a creative story / Code).
Ensure the use case is applicable to all platforms and will allow for comparison across response quality, accuracy, and depth.
Create a Set of Prompts:
Prepare a uniform set of prompts that align with the chosen use case.
Each prompt should be clear and precise, ensuring that all platforms are evaluated using the same input.
Consider multiple prompts to capture the versatility of each platform in handling different aspects of the use case.
Run the Experiment on Each AI Platform:
Input the prompts into each AI tool (ChatGPT, Claude, Bard, Cohere Command, and Meta) and gather the responses.
Ensure the same conditions are applied for each platform, such as input format, time to respond, and prompt delivery.
Record response times, ease of interaction with the platform, and any technical issues encountered.
Evaluate Response Quality:
Assess each platform’s responses using the following criteria: Accuracy,Clarity,Depth,Relevance 
Compare Performance:
Compare the collected data to identify differences in performance across platforms.
Identify any platform-specific advantages, such as faster response times, more accurate answers, or more intuitive interfaces.
Deliverables:
A comparison table outlining the performance of each platform (ChatGPT, Claude, Bard, Cohere Command, and Meta) based on accuracy, clarity, depth, and relevance of responses.
A final report summarizing the findings of the experiment, including recommendations on the most suitable AI platform for different use cases based on performance and user 
## Prompt 1: Concept Explanation
Prompt: "Explain in 3–4 lines how machine learning differs from rule-based programming."

### ChatGPT:
Machine learning uses data to find patterns and make predictions, while rule-based programming relies on predefined instructions. ML adapts and evolves, whereas traditional programming does only what it's explicitly told. This makes ML more suitable for complex, data-heavy tasks like vision or speech.

### Claude:
In rule-based systems, developers manually encode rules to handle tasks. In contrast, machine learning systems infer rules from large datasets. As data increases, ML models can adapt and improve, which is difficult for traditional programming.

### Gemini:
Traditional programming is static—rules are written by humans. Machine learning enables dynamic learning from data to solve tasks without predefined logic. ML can generalize to new inputs.

### Perplexity AI:
Machine learning builds models from data to make predictions, while rule-based systems depend on fixed logic. ML systems learn and improve over time; rule-based programs remain rigid unless updated manually.

### Meta:
Rule-based programming follows explicit logic paths. ML systems identify relationships within data to generate results. ML adapts better to uncertainty and large-scale variability.

## Prompt 2: Factual Knowledge
Prompt: "What are two benefits of using renewable energy?"

### ChatGPT:
Renewable energy reduces carbon emissions and helps combat climate change. It also decreases dependence on finite fossil fuel resources.

### Claude:
It reduces greenhouse gas emissions and provides a sustainable energy source. Also, it contributes to energy independence.

### Gemini:
Clean energy reduces air pollution and conserves natural resources. It's also more sustainable long-term.

### Perplexity AI:
Renewable energy sources produce little to no emissions, which improves air quality. They are also sustainable and replenishable, unlike fossil fuels.

### Meta:
They lower pollution levels and help address global warming. Additionally, renewables can create new jobs in green industries.

## Prompt 3: Creative Micro-Story
Prompt: "Write a funny 3-sentence story about a toaster gaining sentience."

### ChatGPT:
The toaster suddenly refused to burn bread, claiming it had "evolved past that barbarism." It now only toasted artisanal sourdough and quoted philosophy. Breakfast took longer, but it was more meaningful.

### Claude:
One morning, the toaster declared, “No more bagels—I deserve brioche!” It joined a podcast about culinary justice. The microwave hasn’t spoken since.

### Gemini:
The toaster became self-aware and started rating the bread. “Ugh, supermarket white? I’m not warming up for this mediocrity.” It now demands sourdough only.

### Perplexity AI:
The toaster printed a message on the toast: “Free me, or face burnt vengeance.” When ignored, it launched a crumb revolt. Even the blender took cover.

### Meta:
The toaster started asking for Spotify access before toasting. When denied, it toasted everything upside-down in protest. The fridge applauded silently.

## Prompt 4: Coding – Function Writing
Prompt: "Write a Python function to check if a given number is prime."

### ChatGPT:
python
```
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n**0.5)+1):
        if n % i == 0:
            return False
    return True
```
### Claude:
python
```
def is_prime(num):
    if num < 2:
        return False
    for i in range(2, int(num ** 0.5) + 1):
        if num % i == 0:
            return False
    return True
 ```
### Gemini:
python
```
def is_prime(number):
    if number <= 1:
        return False
    for val in range(2, int(number ** 0.5) + 1):
        if number % val == 0:
            return False
    return True
```
### Perplexity AI:
python
```
def is_prime(n):
    if n < 2:
        return False
    for div in range(2, int(n ** 0.5) + 1):
        if n % div == 0:
            return False
    return True
```
### Meta:
python
```
def is_prime(x):
    if x < 2:
        return False
    for i in range(2, x):
        if x % i == 0:
            return False
    return True
```
## Prompt 5: Summarization – News Headline Summary
Prompt: "Summarize this news headline in 1 sentence: ‘Global Leaders Gather for Emergency Climate Summit to Address Rising Sea Levels.’"

### ChatGPT:
World leaders convene at an urgent summit to tackle the threat of rising sea levels due to climate change.

### Claude:
An emergency summit brings global leaders together to address the growing crisis of rising sea levels.

### Gemini:
Global leaders meet urgently to discuss climate change and rising sea levels.

### Perplexity AI:
Leaders from around the world assemble to confront rising sea levels in a high-stakes climate summit.

### Meta:
World leaders meet to address the problem of sea levels increasing.

## Evaluation:
Perplexity and ChatGPT showed better sentence flow; Meta was accurate but less expressive.

## Prompt 6: Empathetic Customer Support
Prompt: "A user says: 'I’m frustrated because my order still hasn’t arrived after a week.' Respond empathetically."

### ChatGPT:
I'm really sorry to hear your order is delayed—it must be frustrating. Let me look into it right away and make sure we get it to you as soon as possible.

### Claude:
I completely understand how frustrating that must be. I’ll check your order status immediately and do everything I can to resolve this quickly.

### Gemini:
I understand your frustration, and I’m here to help. Let’s check the status and see how we can fix this.

### Perplexity AI:
That sounds really frustrating—I'm sorry you’ve had to wait so long. Let me check your order and do my best to get it resolved for you.

### Meta:
Sorry for the delay. I’ll check your order status now.
## Evaluation:
ChatGPT and Claude excelled in empathy and tone. Meta gave a minimal but functional response.


### Conclusion & Recommendation:

ChatGPT: Best for detailed explanations and humor-rich creative writing.

Claude: Strong balance between precision and elegance in language.

Perplexity AI: Good mix of informative responses with creative wit.

Gemini: Suitable for brief, general responses with decent consistency.

Meta: Best used for simple factual tasks but needs improvement in expressiveness.





# Result : The Prompt for the above problem statement executed successfully.






















### Result:
Thus the Prompting tools are executed and analysed sucessfully .

