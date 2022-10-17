# 🛒 Community Shop Partnership Project

## 📋 About this Project

This project is a collaboration with the social enterprise [Community Shop](https://www.companyshopgroup.co.uk/community-shop-our-social-enterprise) to assess the impact of their model on their members' health. We are very grateful for Community Shop for sharing their data with us. The project is made up of five strands:
* Exploratory data analysis
* Longitudinal analysis of purchasing patterns
* Impact of the introduction of the 20p fruit and vegetable price
* Market basket analysis
* Comparison with non-member purchasing data

## :hammer_and_wrench: Installation

**Step 1.** Check that you meet the data science cookiecutter [requirements](http://nestauk.github.io/ds-cookiecutter). In brief, you should:

- Install the following components:
  - [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html)
  - [gh](https://formulae.brew.sh/formula/gh), GitHub command line tool
  - [direnv](https://formulae.brew.sh/formula/direnv#default), for using environment variables
  - [git-crypt](https://github.com/AGWA/git-crypt/blob/master/INSTALL.md#installing-on-mac-os-x), tool for encryption of sensitive files
- Have a Nesta AWS account, and install and configure your [AWS Command Line Interface](https://docs.aws.amazon.com/polly/latest/dg/setup-aws-cli.html)

**Step 2.** Run the following command from the repo root folder:

```
make install
```

This will configure the development environment:

- Setup the conda environment with the name `ahl_community_shop`
- Configure pre-commit actions (for example, running a code formatter before each commit)
- Configure metaflow

**Step 3.** Activate the newly created conda environment and you're good to go!

```shell
$ conda activate ahl_community_shop
```

## :handshake: Contributor guidelines

[Technical and working style guidelines](https://github.com/nestauk/ds-cookiecutter/blob/master/GUIDELINES.md)

---

<small><p>Project based on <a target="_blank" href="https://github.com/nestauk/ds-cookiecutter">Nesta's data science project template</a>
(<a href="http://nestauk.github.io/ds-cookiecutter">Read the docs here</a>).
</small>
