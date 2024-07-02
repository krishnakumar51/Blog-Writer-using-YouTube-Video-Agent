# Blog Writer Based on Video

This project leverages AI agents to create blog content from YouTube videos. It utilizes the CrewAI framework to orchestrate agents performing research and writing tasks, resulting in a comprehensive blog post based on video content from a specified YouTube channel.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/agent.git
    cd agent
    ```

2. **Set up a virtual environment:**

    ```bash
    python3 -m venv env
    `env\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. Create a .env file in the root directory and add your OpenAI API key:

```plaintext
OPENAI_API_KEY=your_openai_api_key_here
```
5. Ensure the following environment variables are set:

```plaintext
OPENAI_API_KEY=your_openai_api_key_here
OPENAI_MODEL_NAME=gpt-3.5-turbo
```

## Output
The final blog content will be generated and saved in new-blog-post.md.

## License
This project is licensed under the MIT License.



Feel free to modify the details as necessary to better fit your specific use case or project requirements.

