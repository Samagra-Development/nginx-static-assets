# Nginx Static Assets
- Create `.env` file & configure PORT (use `.sample.env`).
- Upload all asset files which are to be served in `static` folder
- Hit `docker-compose up -d --build`
- Assets will be available at http(s)://{host}:{port}/assets/{filename}; e.g. `http://127.0.0.1:8988/assets/sample-form-zip.zip`
