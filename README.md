# AareCast

Forecasting the Aare water temperature in Bern 24 hours ahead, so you know tonight whether tomorrow evening's swim will be warm enough.

Semester project for MLOps (HSLU, HS26). The system follows the FTI architecture: a feature pipeline pulls live BAFU river data (via Aare.guru / existenz.ch) and MeteoSwiss forecasts, a training pipeline retrains and registers the model, and an inference pipeline serves hourly forecasts in a web UI.

- Proposal: [docs/proposal.pdf](docs/proposal.pdf)
- Status: MS1 (proposal). Pipelines follow in the next milestones.

Data: river data © [BAFU](https://www.hydrodaten.admin.ch), via [Aare.guru](https://aare.guru) and [existenz.ch](https://api.existenz.ch).
