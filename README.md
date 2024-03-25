# Langchain-GPT-Multilingual-Templating
This repo is for using Langchain to work with GPT. A simpler process to prompt GPT for multiple languages.

Using LLMs for translations can provide more flexible and smarter interpretation of the translation prompts as opposed to machine translations. 
In business settings for example, machine translations can tend to miss out on the right vocabulary, tone and terminology or use suboptimal style for the translations.

In this project, the prompting template was written such that based on the input_language and output_language, the translations are output.

Ofcourse, recommendations for a GPT translation application to have optimum performance in comparison to machine translators depend on proper tuning. In the case of parameter tuning for this application, a low to medium value for the parameters 'Temperature' and 'Top_p' nucleus sampling are to be preferred.
The above range of values ensures, for this use case specifically, more predictable and accurate translations with less probability of creativity and drift out of relevance boundaries of the translations.
