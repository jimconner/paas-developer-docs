# Government PaaS Developer Docs



This project uses [MkDocs][]. It is automatically built and hosted by [Read
the Docs][] at the following URL:

- https://government-paas-developer-docs.readthedocs.io/en/latest/

[MkDocs]: http://www.mkdocs.org/
[Read the Docs]: https://readthedocs.org/

## Setup

You need the following things installed:
- pip
- libjpeg  (libjpeg-dev on ubuntu/Debian)

It is recommended that you use [virtualenv][] if you want to run the build
process locally.

[virtualenv]: https://virtualenv.pypa.io/en/latest/

To install the dependencies:

    pip install -Ur requirements.txt

## Preview

To preview your changes locally run:

    mkdocs serve

Then visit:

- http://127.0.0.1:8000
