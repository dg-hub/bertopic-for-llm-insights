# Large Language Models (LLMs) Impact Analyzer using BERTopic

The Large Language Models Impact Analyzer is a powerful python repository designed to unveil the true potential of Large Language Models (LLMs) in your organisation. This repository contains Python scripts that leverage the power of state-of-the-art Natural Language Processing (NLP) models, particularly BERTopic to analyse user interactions, evaluate LLM adoption, and generate insightful reports allowing your organisation to understand where and how LLMs contribute to its performance.

## Main Features

- Detailed User Interaction: Analyze text-based interactions of your users with your LLMs.
- Identification of Key Themes using BERTopic: Identify General and specific Themes found in your Users’ interactions.
- Insights Generation: Generate actionable insights based on the obtained topics to optimise the use and adoption of LLMs in your organisation.
- Facilitate LLM Adoption: Monitor the adoption process and facilitate it based on the insights obtained.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

Following are some examples of how to use the scripts in this repository.

_Check the `notebooks` directory for more detailed examples._

### Analyzing user interactions with your LLM

```bash
python analyze_interactions.py --llm_logs_dir "./logs" --output_dir "./analyzed_data"
```

### Identifying key themes in user interactions using BERTopic

```bash
python run_bertopic.py --analyzed_data_dir "./analyzed_data" --output_dir "./themes"
```

### Generating insights to enhance the adoption of LLMs

```bash
python generate_insights.py --themes_dir "./themes" --output_dir "./insights"
```

## Contribution
Any contributions you make are **greatly appreciated**. Check the `CONTRIBUTING.md` for how to contribute to this project.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
_For any questions or concerns, please open an issue first for a discussion._

## Acknowledgments

We want to thank the developers of the following packages used in this project:

- [BERTopic](https://github.com/MaartenGr/BERTopic)
- [Scikit-Learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org)
- [Numpy](https://numpy.org)
- [Matplotlib](https://matplotlib.org)

---

> This project is an endeavour to bring LLMs closer to your workflow, more relevant, more useful, and easier to adopt. With your feedback and contributions, we can achieve this goal together!
