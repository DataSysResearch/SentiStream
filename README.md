# SentiStream

SentiStream is a co-training framework for adaptive online sentiment analysis
over continuously evolving data streams. This DataSys repository preserves the
paper artifact together with the earlier PLStream labeling pipeline used by the
project.

## Repository layout

- [`SentiStream/`](SentiStream/) contains the SentiStream implementation,
  datasets, experiment scripts, and detailed setup instructions.
- [`PLStream/`](PLStream/) contains the earlier Apache Flink and Redis polarity
  labeling pipeline.

## Publication

Yuhao Wu, Karthick Sharma, Chun Wei Seah, and Shuhao Zhang. "SentiStream: A
Co-Training Framework for Adaptive Online Sentiment Analysis in Evolving Data
Streams." *Proceedings of the 2023 Conference on Empirical Methods in Natural
Language Processing*, pages 6198-6212, 2023.

- Paper: https://doi.org/10.18653/v1/2023.emnlp-main.380
- Canonical repository: https://github.com/DataSysResearch/SentiStream

```bibtex
@inproceedings{wu-etal-2023-sentistream,
  title = {{SentiStream}: A Co-Training Framework for Adaptive Online Sentiment Analysis in Evolving Data Streams},
  author = {Wu, Yuhao and Sharma, Karthick and Seah, Chun Wei and Zhang, Shuhao},
  booktitle = {Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing},
  year = {2023},
  pages = {6198--6212},
  doi = {10.18653/v1/2023.emnlp-main.380},
  url = {https://aclanthology.org/2023.emnlp-main.380}
}
```

## Project status

This is a research artifact maintained for reproducibility. Start with the
component README that matches the experiment you intend to run.
