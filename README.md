# Langgraph POC
## Chatbot using langraph

## How To Use It

```
pip install -r requirments.txt
```

```
python langgraph_poc.py
```

Create .env file and fill up variable **GROQ_API_KEY**. Please check this section for getting api keys https://console.groq.com/keys

```
GROQ_API_KEY="****************"
```

## Example:
```
 python langgraph_poc.py 
<IPython.core.display.Image object>
User: write a for loop in java
dict_values([{'messages': AIMessage(content='```java\nfor (int i = 0; i < 10; i++) {\n  System.out.println("Iteration: " + i);\n}\n```\n\n**Explanation:**\n\n* **`for (int i = 0; i < 10; i++)`**: This is the header of the for loop. It consists of three parts:\n\n    * **`int i = 0;`**: This initializes a loop counter variable `i` to 0. This variable will be used to track the current iteration of the loop.\n    * **`i < 10;`**: This is the loop condition. The loop will continue to execute as long as the value of `i` is less than 10.\n    * **`i++;`**: This is the increment statement. After each iteration of the loop, the value of `i` is incremented by 1.\n\n* **`System.out.println("Iteration: " + i);`**: This is the body of the loop. This statement will be executed in each iteration of the loop.\n\n**Output:**\n\n```\nIteration: 0\nIteration: 1\nIteration: 2\n...\nIteration: 9\n```\n\n**Key Points:**\n\n* **Iteration:** Each execution of the loop body is called an iteration.\n* **Initialization:** The loop counter variable is initialized before the loop starts.\n* **Condition:** The loop continues to execute as long as the condition is true.\n* **Increment/Decrement:** The loop counter variable is updated after each iteration.\n\n**Variations:**\n\n* You can use different data types for the loop counter variable (e.g., `long`, `float`).\n* You can use any valid expression for the loop condition.\n* You can decrement the loop counter variable instead of incrementing it (`i--;`).\n\n\n\n', additional_kwargs={}, response_metadata={'token_usage': {'completion_tokens': 397, 'prompt_tokens': 15, 'total_tokens': 412, 'completion_time': 0.721818182, 'prompt_time': 0.001246079, 'queue_time': 0.087081693, 'total_time': 0.723064261}, 'model_name': 'Gemma2-9b-It', 'system_fingerprint': 'fp_10c08bf97d', 'finish_reason': 'stop', 'logprobs': None}, id='run--797c5b8b-a5b1-43c1-9af6-6423e5635e3d-0', usage_metadata={'input_tokens': 15, 'output_tokens': 397, 'total_tokens': 412})}])
content='```java\nfor (int i = 0; i < 10; i++) {\n  System.out.println("Iteration: " + i);\n}\n```\n\n**Explanation:**\n\n* **`for (int i = 0; i < 10; i++)`**: This is the header of the for loop. It consists of three parts:\n\n    * **`int i = 0;`**: This initializes a loop counter variable `i` to 0. This variable will be used to track the current iteration of the loop.\n    * **`i < 10;`**: This is the loop condition. The loop will continue to execute as long as the value of `i` is less than 10.\n    * **`i++;`**: This is the increment statement. After each iteration of the loop, the value of `i` is incremented by 1.\n\n* **`System.out.println("Iteration: " + i);`**: This is the body of the loop. This statement will be executed in each iteration of the loop.\n\n**Output:**\n\n```\nIteration: 0\nIteration: 1\nIteration: 2\n...\nIteration: 9\n```\n\n**Key Points:**\n\n* **Iteration:** Each execution of the loop body is called an iteration.\n* **Initialization:** The loop counter variable is initialized before the loop starts.\n* **Condition:** The loop continues to execute as long as the condition is true.\n* **Increment/Decrement:** The loop counter variable is updated after each iteration.\n\n**Variations:**\n\n* You can use different data types for the loop counter variable (e.g., `long`, `float`).\n* You can use any valid expression for the loop condition.\n* You can decrement the loop counter variable instead of incrementing it (`i--;`).\n\n\n\n' additional_kwargs={} response_metadata={'token_usage': {'completion_tokens': 397, 'prompt_tokens': 15, 'total_tokens': 412, 'completion_time': 0.721818182, 'prompt_time': 0.001246079, 'queue_time': 0.087081693, 'total_time': 0.723064261}, 'model_name': 'Gemma2-9b-It', 'system_fingerprint': 'fp_10c08bf97d', 'finish_reason': 'stop', 'logprobs': None} id='run--797c5b8b-a5b1-43c1-9af6-6423e5635e3d-0' usage_metadata={'input_tokens': 15, 'output_tokens': 397, 'total_tokens': 412}
Assistant: ```java
for (int i = 0; i < 10; i++) {
  System.out.println("Iteration: " + i);
}
```

**Explanation:**

* **`for (int i = 0; i < 10; i++)`**: This is the header of the for loop. It consists of three parts:

    * **`int i = 0;`**: This initializes a loop counter variable `i` to 0. This variable will be used to track the current iteration of the loop.
    * **`i < 10;`**: This is the loop condition. The loop will continue to execute as long as the value of `i` is less than 10.
    * **`i++;`**: This is the increment statement. After each iteration of the loop, the value of `i` is incremented by 1.

* **`System.out.println("Iteration: " + i);`**: This is the body of the loop. This statement will be executed in each iteration of the loop.

**Output:**

```
Iteration: 0
Iteration: 1
Iteration: 2
...
Iteration: 9
```

**Key Points:**

* **Iteration:** Each execution of the loop body is called an iteration.
* **Initialization:** The loop counter variable is initialized before the loop starts.
* **Condition:** The loop continues to execute as long as the condition is true.
* **Increment/Decrement:** The loop counter variable is updated after each iteration.

**Variations:**

* You can use different data types for the loop counter variable (e.g., `long`, `float`).
* You can use any valid expression for the loop condition.
* You can decrement the loop counter variable instead of incrementing it (`i--;`).




User: q
Good Bye
```

