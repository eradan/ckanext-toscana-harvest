
# ckanext-toscana-harvest
CKAN extension for harvest dataset on SpodCkan and Metarepo

## Contents

- [Overview](#overview)
- [License](#license)
- [Requirements](#requirements)
- [Installation](#installation)
- [Development Installation](#development-installation)
- [Contributing](#contributing)
- [Support, Communication and Credits](#support-communication-and-credits)


## License

**ckanext-toscana-harvest** is Free and Open Source software and is licensed under the GNU Affero General Public License (AGPL) v3.0 whose full text may be found at:

http://www.fsf.org/licensing/licenses/agpl-3.0.html

## Overview 

This extension provides plugins that allow CKAN to  harvest datasets from SpodCkan endpoint and Metarepo application

## Requirements

The ckanext-toscana-harvest extension has been developed for CKAN 2.6 or later.

## Installation

1. Go into your CKAN path for extension (like /usr/lib/ckan/default/src):
 
    `git clone https://github.com/eradan/ckanext-toscana-harvest.git`

    `cd ckanext-toscana-harvest`

    `pip install -e .`

6. Add ``toscana_harvest`` ``spod_harvester`` and  ``metarepo_harvester`` to the ``ckan.plugins`` setting in your CKAN
   config file (by default the config file is located at ``/etc/ckan/default/production.ini``).

7. Restart CKAN. For example if you've deployed CKAN with Apache on Ubuntu:

     `sudo service apache2 reload`
   

## Contributing

We welcome contributions in any form:

* pull requests for new features
* pull requests for bug fixes
* pull requests for documentation
* funding for any combination of the above

## Support, Communication and Credits
This work has been performed by [Hyperborea](http://www.hyperborea.com) with funding provided by Regione Toscana.

The work is provided as is and no warranty whatsoever is provided. 

