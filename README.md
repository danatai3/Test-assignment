# Test-assignment

# Instagram Real Estate Post Generator

This project generates Instagram posts for a real estate account using the OpenAI GPT-3.5 Turbo API. The posts are based on random entries from the Housing Prices Dataset.

## Solution Description

The solution involves utilizing the OpenAI GPT-3.5 Turbo API to generate engaging real estate content for Instagram posts. The Housing Prices Dataset is used as a source of random entries, providing diverse content for the posts. The code is structured in a Google Colab notebook, making it accessible and easy to run.

## Mimicking Instagram Post Styles

To mimic the style of successful Instagram posts, I focused on crafting prompts that encapsulate the language and tone commonly found in real estate captions on Instagram. By analyzing existing posts, I identified key phrases, adjectives, and structuring patterns that contribute to a captivating style. These elements were incorporated into the prompts to ensure that the generated content aligns with the desired Instagram aesthetic.

## Prompt Engineering Techniques

To enhance the quality of generated posts, prompt engineering techniques were employed. This includes experimenting with different prompt structures, adjusting temperature and max tokens parameters, and fine-tuning the prompt for specific details such as property features, location, and lifestyle. Iterative testing and refinement were performed to find the optimal combination that produces high-quality and varied content.

## Preventing Model from Inventing Extra Features

To prevent the model from inventing extra features, the prompts were carefully crafted to focus on the information present in the dataset. Explicit instructions and constraints were provided in the prompts to guide the model's creativity towards generating content relevant to the given property's price and area. Continuous monitoring of generated posts helped identify and address any instances where the model introduced unnecessary or unrealistic details.

