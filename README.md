# Hi, I'm Dushyant Rajpurohit

**I build ML models, measure them honestly, and ship them as apps people can use.**

Aspiring data scientist and ML engineer from India, open to ML, data science and backend roles and internships.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dushyant-singh-0793a036a/)
[![Email](https://img.shields.io/badge/Email-dushyantrajpurohit5412%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dushyantrajpurohit5412@gmail.com)

## Featured projects

### [indian-anpr](https://github.com/DushyantRajpurohit/indian-anpr) · [live demo](https://dushyantrajpurohit.github.io/indian-anpr/)
Reads Indian number plates live in the browser, on your own camera, with nothing uploaded.
- Fine-tuned YOLO26n detector finds **98.8%** of test plates; a 0.69M-parameter CRNN reader trained **only on synthetic plates** gets **50.1%** of plates exactly right, up from 18.8% for an off-the-shelf detector + EasyOCR
- Found and fixed leaks that inflate the usual scores: the same car repeated across splits, and Roboflow augment copies spread over train and test
- Runs at about 5 frames/s on a CPU-only laptop via onnxruntime-web

`PyTorch` `YOLO` `ONNX` `Next.js` `TypeScript`

### [paysim-fraud-detection](https://github.com/DushyantRajpurohit/paysim-fraud-detection) · [illustrated story](https://dushyantrajpurohit.github.io/paysim-fraud-detection/)
Shows that PaySim, the standard fraud dataset, can be solved with one equality check, then builds a model that works without that shortcut.
- Signature-free LightGBM: **0.634 PR-AUC** on a time-ordered test set, catching 77% of frauds and **96% of the money**
- Alert threshold chosen by cost, per-prediction SHAP explanations
- FastAPI scoring service, Docker, CI

`Python` `LightGBM` `SHAP` `FastAPI` `Docker`

### [VillageLab](https://github.com/DushyantRajpurohit/villagelab) · [live app](https://villagelab.vercel.app)
Progress tracking, upgrade planning and war analytics for Clash of Clans.
- Queue-based ingestion so no user request hits the rate-limited game API directly
- Hand-checked dataset of 2,500+ upgrade levels, read by a parser that refuses to guess
- Postgres snapshot history answers questions the API can't (trends, churn); 931 tests, runs on free hosting

`Next.js` `TypeScript` `PostgreSQL` `Vitest`

### [f1-telemetry](https://github.com/DushyantRajpurohit/f1-telemetry)
Compares any two Formula 1 drivers using real car telemetry: speed traces, live time delta, track dominance map and tyre strategy. Includes a lap simulator fitted to real laps, so you can see what grip, downforce or power are worth in lap time.

`Python` `FastF1` `NumPy` `pytest`

## Tech stack

- **ML and data:** PyTorch · TensorFlow · scikit-learn · LightGBM · OpenCV · Pandas · NumPy
- **Backend:** Python · FastAPI · Flask · Node.js · PostgreSQL · Docker
- **Frontend:** TypeScript · React · Next.js · Tailwind CSS
