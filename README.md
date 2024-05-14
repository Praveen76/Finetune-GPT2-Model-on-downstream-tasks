# Finetune-GPT2-Model-on-downstream-tasks

This repository contains code and resources for fine-tuning the GPT-2 model on downstream tasks using the Hugging Face's transformers library. The project utilizes text data from "The Buddha's Path of Virtue: A Translation of the Dhammapada by F. L. Woodward", available through Project Gutenberg.

## Learning Objectives

By the end of this experiment, you will be able to:
- Load and pre-process data from a text file.
- Load and use a pre-trained tokenizer.
- Finetune a GPT-2 language model on a specific text dataset.

## Dataset Description

The dataset used in this project is taken from one of Project Gutenberg's eBooks named "The Buddha's Path of Virtue: A Translation of the Dhammapada by F. L. Woodward". This dataset includes a variety of teachings and philosophies attributed to Buddha, providing a rich linguistic resource for language modeling.

[Read more about the text and its source here.](https://www.gutenberg.org/ebooks/2017)

## How to Use

### Requirements
Before starting, ensure that you have Python installed on your system and the following Python packages:
- `transformers`
- `torch`
- `datasets`
- `tokenizers`

You can install these packages using pip:
```bash
pip install transformers torch datasets tokenizers
```

### Steps to Run

1. **Clone the Repository:**
```bash
git clone https://github.com/Praveen76/Finetune-GPT2-Model-on-downstream-tasks.git
cd Finetune-GPT2-Model-on-downstream-tasks
```

2. **Prepare the Data:**
   - Ensure that the dataset file `dhammapada.txt` is located in the `data/` directory.

3. **Training the Model:**
   - Run the training script:
   ```bash
   python finetune_gpt2.py
   ```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or improvements.


## License

This project is licensed under the [MIT License](LICENSE).

# Issues:
If you encounter any issues or have suggestions for improvement, please open an issue in the Issues section of this repository.

---
# Contact:
The code has been tested on Windows system. It should work well on other distributions but has not yet been tested. In case of any issue with installation or otherwise, please contact me on [Linkedin](https://www.linkedin.com/in/praveen-kumar-anwla-49169266/)

Happy coding!!

---
## **About Me**:
I’m a seasoned Data Scientist and founder of [TowardsMachineLearning.Org](https://towardsmachinelearning.org/). I've worked on various Machine Learning, NLP, and cutting-edge deep learning frameworks to solve numerous business problems.
