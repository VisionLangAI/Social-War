# Social Media Toxic Comments
## Overview

This dataset contains **5000 entries** labeled for online toxicity detection. It is balanced across **five categories** of toxic behavior commonly found in online communications:

- Rudeness
- Abusive Language
- Trolling
- Arguments
- Cyberbullying

Each category contains exactly **1000 distinct sentences** gathered to represent the corresponding label with no duplicates or missing values.

## Dataset Description

| Column Name | Description                          |
|-------------|------------------------------------|
| `Text`      | A unique sentence representing toxic or argumentative online behavior. |
| `Labels`    | The toxicity category label assigned to the text (one of the five classes). |

## Purpose

The dataset is designed for:

- Training and evaluating machine learning models for toxicity detection, hate speech recognition, or online abuse classification.
- Benchmarking natural language processing models on balanced and diverse toxicity data.
- Research and development of content moderation tools.

## Dataset Characteristics

- Total samples: 5000
- Labels: 5 (Rudeness, Abusive Language, Trolling, Arguments, Cyberbullying)
- Balanced: 1000 samples per label
- Unique sentences: All entries are distinct, with varied sentence structures and vocabulary.

## Usage

You can load the dataset using pandas:

```python
import pandas as pd

df = pd.read_csv('social_media_comments.csv')
print(df.head())
