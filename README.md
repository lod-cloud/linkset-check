Produces a report of dataset linkages in the `lodcloud` group on [datahub.io](http://datahub.io/). This is useful as a validation step in producing the [LOD Cloud diagram](http://lod-cloud.net/).

# Requirements

* Ability to run PHP scripts (PHP 5) via the `php` command line app

# Usage

````
php report.php
````

This produces a file called `index.html` in the project directory. Open that in a browser to see the report.

# Installation from GitHub

````
git clone https://github.com/lod-cloud/linkset-check.git
git submodule update
````

# Installation without git

* Download and uncompress https://github.com/lod-cloud/lod-cloud/archive/master.zip
* Download and uncompress https://github.com/cygri/Ckan_client-PHP/archive/master.zip
# Move the uncompressed `Ckan_client-PHP-master` directory to `lod-cloud-master/Ckan_client-PHP`

# TODO

* This fetches each dataset individually. That's unnecessary with today's CKAN API.
