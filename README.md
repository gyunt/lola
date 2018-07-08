Learning with Opponent-Learning Awareness
=========================================

Implements the LOLA ([arXiv:1709.04326](https://arxiv.org/abs/1709.04326)) and LOLA-DiCE ([arXiv:1802.05098](https://arxiv.org/abs/1802.05098)) algorithms.


## Installation

To run the code, you need to pip-install it as follows:

```bash
$ pip install -e .
```

After installation, you can run different experiments using the run scripts provided in `scripts/`.
Use `run_lola.py` and `run_tournament.py` for running experiments from [arXiv:1709.04326](https://arxiv.org/abs/1709.04326).
Use `run_lola_dice.py` for reproducing experiments from [arXiv:1802.05098](https://arxiv.org/abs/1802.05098)
Check out `notebooks/` for IPython notebooks with plots.

*Disclaimer:* This is a research code release that has not been tested beyond the use cases and experiments discussed in the original papers.
Contributions to further enhance and improve LOLA are welcome.


## Citations

LOLA:
```bibtex
@article{foerster2017lola,
  title={Learning with Opponent-Learning Awareness},
  author={Foerster, Jakob N and Chen, Richard Y and Al-Shedivat, Maruan and Whiteson, Shimon and Abbeel, Pieter and Mordatch, Igor},
  journal={arXiv preprint arXiv:1709.04326},
  year={2017}
}
```

DiCE:
```bibtex
@article{foerster2018dice,
  title={DiCE: The Infinitely Differentiable Monte-Carlo Estimator},
  author={Foerster, Jakob N and Farquhar, Greg and Al-Shedivat, Maruan and Rocktäschel, Tim and Xing, Eric P and Whiteson, Shimon},
  journal={arXiv preprint arXiv:1802.05098},
  year={2018}
}
```

## License

MIT
