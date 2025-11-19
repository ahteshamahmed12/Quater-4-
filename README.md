# Quater-4-
Prompt and Context Engineering


prompt and context engineering

prompt is usesful when both agent and user will understand.

telling your ai agent and your LLM what to do and how to do.

prompt : to provide instruction to LLM

context: to provide the background or relevant information to LLM.

pillars of prompt engineering

1. Markdown (standard)
            create login function with username and password
   XML 
   JSON 

   NLP(Natural Language Process)

2. WSL (windows subsystem for Linux) for universal code development enviorment.

3. AI CLI of Gemini 
 4.1 Codex CLI  (20$ per month)
 4.2 Gemini CLI (1000 request free) 
 4.3 QWEN CLI (2000 request free)
 4.4 Claude CLI (20$ per month )

4. Plugins , AI CLI'S MCP Server 

5. Test Driven Development 
       

6. Spec Driven Development
        define the step for out business development

7. Deployment
        cluster : gather of computer
        Digital Ocean 
        Azure 

software's to learn 

1. Docker  
2. Kubernetes
3. Dapper
4. Ray only for Linux

Sophisticated Autocomplete System

Top K 

Top-K: Limits choices to top K most likely tokens
Top K is static 
K represent any one number
Top_k = 10

Aj weather bohot 

Acha ha 
bura ha
garam ha
thanda ha

Top_P  (0.8%)

Top P is a dynamic

Aj weather bohot 

Acha ha  (50%)
bura ha  (30%)
garam ha
thanda ha

Top-P: Limits choices based on cumulative probability 
Thresold (means exceed to a certain number )
In Top_p we set the thresold
When selecting a next word combine probbaility will be choosen from the thresold will be nominated


Conservative: Temperature 0.1, Top-P 0.9, Top-K 20
Balanced: Temperature 0.2, Top-P 0.95, Top-K 30
Creative: Temperature 0.9, Top-P 0.99, Top-K 40


1-> Conservative: 
Temperature =  0.1 = Low  (preference temprature supreme controller)
Top-P  = 0.9 = High  (2nd preference)
Top-K  = 20 = Low    (Least preference)

Fundamental Prompting Techniques

Shot means example

1. Zero-Shot Prompting

The simplest approach—just ask directly without examples.
When to use:
Simple, well-defined tasks
When the model has clear knowledge of the domain
Quick one-off requests

2. One-Shot Prompting

Provide a single example to guide the response format.

3. Few-Shot Prompting

Provide multiple examples to establish a clear pattern.
Best practices:
Use 3-5 examples for most tasks
Include diverse examples
Mix up the classes in classification tasks
Ensure examples are high-quality and consistent

4. System Prompting

Set overall context and behavior guidelines.

5. Role Prompting

Assign a specific character or expertise to the AI.
Effective roles:
Subject matter expert (doctor, lawyer, teacher)
Creative roles (writer, designer, poet)
Analytical roles (data analyst, consultant)
Communication styles (friendly tutor, formal advisor)

6. Contextual Prompting
Provide specific background information relevant to the task.

Role + system Prompting can be used together


