# Description Generator

This application uses GPT-3 to generate personal descriptions for users using their GitHub usernames. Simply provide the username, and the application will generate a description of the user based on their public profile and activity on GitHub.

## How to use

To use the application, you will need to install the required dependencies and obtain an API key for GPT-3.

```python
from description_generator import description_generator
key="openai api key"

description = description_generator(key,"octocat")
```

| Input   | Output                                                                                                                                                                                                                                                                                        |
| ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| octocat | Octocat is a fun-loving individual who loves open source and helping others. They are a active member of the GitHub community, often helping others with their code and projects. Octocat is also known for their love of cats, often sharing photos and stories of their own feline friends. |

## Dependencies

| Dependency | Version |
| ---------- | ------- |
| Python     | 3.7+    |
| OpenAI     | 0.11.0  |
| Requests   | 2.25.1  |

## Disclaimer

Please note that the descriptions generated by this model are based on the public information available on GitHub and may not always be accurate. Use the generated descriptions at your own risk.
