# Alwrity - AI Generator for Copywriting PAS Formula

Alwrity is a web application built with Streamlit that utilizes OpenAI's GPT-3.5 model to generate marketing copy using the PAS (Problem-Agitate-Solution) formula. This application enables users to create persuasive marketing content by inputting key details about their brand, identifying the problem faced by their target audience, agitating the problem, and presenting their product or service as the solution.

## PAS Copywriting Formula

PAS stands for Problem-Agitate-Solution. It's a copywriting formula that involves:

1. **Problem**: Identifying a problem faced by the audience.
2. **Agitate**: Agitating the problem by making it clear how it affects them.
3. **Solution**: Presenting your product or service as the solution.

The PAS formula is effective in capturing the audience's attention, engaging them emotionally, and offering a solution to their problem.

### PAS Copywriting Formula: Simple Example

**Problem**: Are you tired of waking up tired every morning?
**Agitate**: Imagine struggling through the day, constantly battling fatigue and low energy levels.
**Solution**: Our energy-boosting supplement provides a natural solution to help you feel revitalized and refreshed every day.

## Features

- **PAS Formula**: Utilizes the Problem-Agitate-Solution copywriting formula to guide users in creating persuasive marketing copy.
- **AI-Powered**: Employs OpenAI's GPT-3.5 model to generate high-quality marketing content based on user inputs.
- **User-Friendly Interface**: Offers an intuitive interface for users to input campaign details and view generated copy.
- **Retry Logic**: Implements retry logic using the Tenacity library to handle potential errors when communicating with the OpenAI API.

## How to Use

1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Set up your OpenAI API key as an environment variable named `OPENAI_API_KEY`.
4. Run the `app.py` file

## Dependencies

- Streamlit
- OpenAI
- Streamlit Lottie
- Tenacity

## Acknowledgements

- Special thanks to OpenAI for providing access to the GPT-3.5 model.
- This project was inspired by the need for efficient and effective marketing copy generation.
