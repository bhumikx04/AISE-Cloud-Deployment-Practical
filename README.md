# AISE Cloud Deployment Practical

## Files
- `app.py`: Streamlit application from the Unit 5 practical guide.
- `requirements.txt`: Python dependency list.

## Run locally on macOS
From this folder, run:

```bash
python3 -m pip install -r requirements.txt
python3 -m streamlit run app.py
```

Then open the local URL shown in the terminal (usually http://localhost:8501).

## Deploy
1. Create a GitHub repository named `AISE-Cloud-Deployment-Practical`.
2. Push `app.py` and `requirements.txt` to the repository's `main` branch.
3. Sign in at https://share.streamlit.io/ using GitHub.
4. Create an app using that repository, branch `main`, and main file path `app.py`.
5. Deploy and test the generated `streamlit.app` URL.

Never commit passwords, API keys, or private data.
