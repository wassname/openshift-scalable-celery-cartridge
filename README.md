STATUS: NOT YET WORKING!

# OpenShift Python Cartridge
This cartridge is forked from the openshift python cartridge with celery added.

# Install

rhc cartridge-add https://raw.github.com/wassname/openshift-scalable-celery-cartridge/master/metadata/manifest.yml -a "appname"

# Config

To configure edit the celeryconfig.py file and put it in you $OPENSHIFT_DATA_DIR. Or use another name and set ${OPENSHIFT_CELERY_CONFIG}=othername.py.
