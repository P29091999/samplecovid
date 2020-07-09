# Covid 19 Interactive Dashboard
[![Awesome](https://awesome.re/badge.svg)](https://github.com/soroushchehresa/awesome-coronavirus#applications-and-bots)
[![Gitter chat](https://img.shields.io/badge/Chat-Gitter-ff69b4.svg?label=Chat&logo=gitter)](https://gitter.im/ncov-dashboard/community)
[![Build Status](https://img.shields.io/travis/TheAlgorithms/Python.svg?label=Travis%20CI&logo=travis)](https://travis-ci.com/github/BrianRuizy/covid19-dashboard)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Made with Pthon](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)


## About

> Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus.
> At this time, there are no specific vaccines or treatments for COVID-19. The best way to prevent and slow down transmission is be **well informed** about the COVID-19 virus. [who.int](https://www.who.int/health-topics/coronavirus#tab=tab_1)

The goal of this project is not to build *just another dashboard*. But, to focus on collaborative plot ideas, and a mobile friendly UI/UX. Feel free to open an issue requesting a type of plot, table, or any feature for that matter. Join the repo's [Gitter chat](https://gitter.im/ncov-dashboard/community?utm_source=share-link&utm_medium=link&utm_campaign=share-link).

## Getting Started

### Prerequisites

* Python; [pyenv](https://github.com/pyenv/pyenv) recommended
* Pip

### Installing

Get the project up and running locally in just 5 easy steps.

1. Create a personal [Fork](https://github.com/login?return_to=%2FBrianRuizy%2Fcovid-19-dashboard) of this repository.

2. **Clone** the fork with HTTPS, using your local terminal to a preferred location, and **cd** into the project.

```bash
git clone https://github.com/your_username/covid-19-dashboard.git

Cloning into 'covid-19-dashboard'...
remote: Enumerating objects: 113, done.
remote: Counting objects: 100% (113/113), done.
remote: Compressing objects: 100% (80/80), done.
Receiving objects: 100% (2845/2845), 12.52 MiB | 5.21 MiB/s, done.

cd covid-19-dashboard/
```

3. Create your virtual environment, and activate it.

```bash
python -m venv env

source env/bin/activate  # Linux/Mac
env/Scripts/activate  # Windows
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

5. Run local server, and **DONE**!

```bash
python manage.py runserver

May 06, 2020 - 11:22:23
Django version 3.0.6, using settings 'core.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```

## Deployment

Heroku app is already configured to this repository for *automatic deploys* from any push to the **master** branch. Create a pull request containing your respective changes and wait for merge.

## Built With

* [Django](https://www.djangoproject.com/) Django is a high-level Web framework that encourages rapid development and clean, pragmatic design.
* [Plotly](https://plotly.com/) The leading front-end for ML & data science models in Python, R, and Julia.
* [Appseed](https://appseed.us/)
* [Bootstrap](https://getbootstrap.com/)

## Data Sources

* Johns Hopkins University: [CSSE](https://systems.jhu.edu/) 2019-ncov data repository, found [here](https://github.com/CSSEGISandData/COVID-19).
* Our World in Data: [OWID](https://ourworldindata.org/) Github Data repository, found [here](https://github.com/owid/covid-19-data/tree/master/public/data).
# sample-covid
# samplecovid
