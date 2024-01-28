# 🛡️ PII Data Detection Project

## 🌟 Project Overview

This project focuses on developing automated techniques to detect and remove Personally Identifiable Information (PII) from educational data 📚. Our aim is to lower the cost of releasing educational datasets while ensuring student privacy. This initiative is critical for supporting learning science research and the development of educational tools 🛠️.

## 📚 Background

PII in educational datasets poses significant challenges. Currently, manual review is the most reliable method for screening PII, but it's costly and limits scalability. Our project aims to develop more efficient, automated solutions for PII detection 🕵️‍♂️.

## 🏆 The Challenge

We are participating in a competition hosted by Vanderbilt University and The Learning Agency Lab to create a model that effectively identifies various types of PII in student essays. This involves processing a dataset of approximately 22,000 essays from a massively open online course, with the aim to annotate PII found within these texts.

## 📋 PII Types

We are focusing on detecting the following seven types of PII:

- **NAME_STUDENT:** Full or partial student names, excluding instructors or authors.
- **EMAIL:** Student email addresses 📧.
- **USERNAME:** Student usernames on any platform 🖥️.
- **ID_NUM:** Identifiable numbers like student ID or social security numbers 🔢.
- **PHONE_NUM:** Student-associated phone numbers 📞.
- **URL_PERSONAL:** URLs that could identify a student 🔗.
- **STREET_ADDRESS:** Student-associated street addresses 🏠.

## 📄 Data Format

The data is provided in JSON format and includes:

- **Document Identifier:** Unique ID for each essay.
- **Full Text:** UTF-8 representation of the essay.
- **Tokens:** List of string tokens, tokenized using SpaCy.
- **Trailing Whitespace:** Boolean for whitespace following each token.
- **Labels (Training Data Only):** Token labels in BIO format.

## 📊 Competition Dataset

- `{test|train}.json`: Test and training data.
- `sample_submission.csv`: Example of the submission format.

## 🎯 Project Goals

1. **Automate PII Detection:** Develop a reliable, automated PII detection method 🤖.
2. **Support Educational Research:** Enable the safe release of cleansed educational datasets 🔍.
3. **Enhance Data Scalability:** Reduce costs and time for manual PII screening 🚀.

## 👥 Contributing

Contributions are welcome! If you're interested in contributing to this project, please check our contribution guidelines 📃.

---

*Note: This project is focused on enhancing data privacy in educational research.* 💡
