# Edison

Edison is a RAG + LLM-based pipeline used to generate answers to student questions on large course discussion forums.

## Routes

This repo is focused on the `/miloh` Flask route only. No other HTTP routes are supported.

## Dependencies

This repo uses split dependency files to keep the deployed Flask app slim while still supporting local notebooks/scripts.

- `requirements.txt`: Production dependencies for the Flask app and API services. Use this for Azure deployment.
- `requirements-dev.txt`: Full local/dev stack (includes Jupyter, notebooks, and related tooling). Use this when running the processing notebooks or local analysis scripts.

### Running the app

Production-style install:
```
pip install -r requirements.txt
```

Local/dev install (for notebooks/scripts):
```
pip install -r requirements-dev.txt
```

## 🚀 FOR UC BERKELEY STUDENTS ONLY

If you are interested in joining this project and/or have some ideas of your own to contribute, please fill this out:

📌 [Application Form](https://docs.google.com/forms/d/e/1FAIpQLSc5qf4a_T4Utp_L27Bmbta1pVjR7pniE3IjDnmL8GyDds83Rw/viewform?usp=sharing)
