# Creating a Sentiment Analysis Web App
## Using PyTorch and AWS SageMaker
The notebook and Python files provided in this repository, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker.

## Resources
### Dataset
Dataset used for this project is [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/)
>Maas, Andrew L., et al. [Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~amaas/data/sentiment/). In Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies. Association for Computational Linguistics, 2011.
### SageMaker
- [SageMaker python SDK](https://sagemaker.readthedocs.io/en/stable/)
- [PyTorch](https://sagemaker.readthedocs.io/en/stable/frameworks/pytorch/index.html) framework on SageMaker

## SageMaker Configuration
Below [SageMaker ML instance types](https://aws.amazon.com/sagemaker/pricing/instance-types/) are used:
- Notebook: ml.t2.medium
- Training: ml.p2.xlarge
- Serving: ml.m4.xlarge

## Git Style Guide
[Udacity Git Commit Message Style Guide](http://udacity.github.io/git-styleguide/) is being used in this repository.

## License
The contents of this repository are covered under the [MIT License](https://github.com/ChandrakanthNethi/creating-a-sentiment-analysis-web-app-using-PyTorch-and-AWS-SageMaker/blob/master/LICENSE)
