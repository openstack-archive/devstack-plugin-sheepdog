======================
 Enabling in Devstack
======================

1. Download DevStack

2. Add this repo as an external repository::

     cat > local.conf
     [[local|localrc]]
     enable_plugin sheepdog https://github.com/openstack/devstack-plugin-sheepdog.git

3. run ``stack.sh``
