HUMBOLDT WEED EATERS — PUBLIC DEPLOYMENT PACKAGE

This package is configured for online Python hosting such as Render.

IMPORTANT: The website is NOT public just by downloading this ZIP. To publish:
1. A parent/guardian should help you create/manage any required hosting account.
2. Create a private GitHub repository and upload the contents of this folder (app.py, requirements.txt, Procfile, render.yaml, static/lawn-path.png).
3. On Render, create a new Web Service and connect the GitHub repository.
4. Use build command: pip install -r requirements.txt
5. Use start command: gunicorn app:app
6. Deploy and wait until the service reports Live.
7. Open the public *.onrender.com URL assigned by the host.
8. The QR code displayed on the live website will then point to that public URL and work for people on their own Wi-Fi/mobile data.

Local test:
py -m pip install -r requirements.txt
py app.py
then open http://127.0.0.1:5000

The public address is assigned by the host; no custom domain is required. The project is not deployed by this ZIP alone.
