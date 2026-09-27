# NTU RGB+D

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FNTU--RGB--PlusD-181717?logo=github)](https://github.com/biometric-community/NTU-RGB-PlusD)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://rose1.ntu.edu.sg/dataset/actionRecognition/)

**NTU RGB+D** — tbiom catalog packaging for `ntu-rgbd` (pose3d; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/NTU-RGB-PlusD
- **Upstream source**: https://rose1.ntu.edu.sg/dataset/actionRecognition/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `ntu-rgbd` |
| Category | `pose3d` |
| Access | `register` |
| Upstream homepage | https://rose1.ntu.edu.sg/dataset/actionRecognition/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: NTU RGB+D 60/120 action recognition.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/NTU-RGB-PlusD.git
cd NTU-RGB-PlusD
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_ntu_rgbd.sh
```

Place licensed archives under `projects/datasets/ntu-rgbd/` (gitignored).

## Dataset structure

```text
NTU-RGB-PlusD/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://rose1.ntu.edu.sg/dataset/actionRecognition/
- Packaging: https://github.com/biometric-community/NTU-RGB-PlusD/issues
