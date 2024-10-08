[![Tests](https://github.com/NorwegianRefugeeCouncil/ckanext-tracking/workflows/Tests/badge.svg?branch=main)](https://github.com/NorwegianRefugeeCouncil/ckanext-tracking/actions)

# CKAN tracking extension

CKAN extension to track users activities on the site through the CKAN API.

## Requirements

Compatibility with core CKAN versions:

| CKAN version    | Compatible?   |
| --------------- | ------------- |
| 2.10            | in progress   |
| 2.11            | not yet       |


## Installation

To install ckanext-tracking:

Install the package:

    pip install -e "git+https://github.com/NorwegianRefugeeCouncil/ckanext-tracking.git@main#egg=ckanext-tracking"
    pip install -r https://raw.githubusercontent.com/NorwegianRefugeeCouncil/ckanext-tracking/main/requirements.txt

or clone the source and install it on the virtualenv

    git clone https://github.com/NorwegianRefugeeCouncil/ckanext-tracking.git
    cd ckanext-tracking
    pip install -e .
	pip install -r requirements.txt

3. Add `tracking` to the `ckan.plugins` setting in your CKAN
   config file (by default the config file is located at
   `/etc/ckan/default/ckan.ini`).

4. Restart CKAN.

## Config settings

None at present

## License

[AGPL](https://www.gnu.org/licenses/agpl-3.0.en.html)
