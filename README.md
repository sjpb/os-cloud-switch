# os-cloud-switch

Select between openstack clouds.yaml files in `~/.config/openstack`.

Requires a venv active containing `python-openstackclient`, e.g.

    python3 -m venv venv
    . venv/bin/activate
    pip install -U pip
    pip install python-openstackclient

Usage:

    . os-cloud-switch

It will show your available clouds.yml files, ask which one to use, then print the name
of the project which is now active.
