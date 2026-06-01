# Quantum Optimization Course Example

This repository contains a sample course for the qBraid platform.

## Structure
- `course.json`: Course configuration and metadata.
- `01_introduction.ipynb`: Introductory lesson with visualizations.
- `02_qaoa_algorithm.ipynb`: Technical lesson on QAOA using Qiskit.
- `images/`: Directory containing all image assets.
- `.github/workflows/deploy.yml`: GitHub Action to automatically deploy the course to qBraid.

## How to Deploy
1. Push this code to your GitHub repository.
2. Add your `QBRAID_API_KEY` to your GitHub repository secrets.
3. Ensure GitHub Actions has "Read and write permissions" in your repository settings.
4. The course will automatically deploy on push to the `main` branch.
