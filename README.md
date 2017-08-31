# lernstick-package-management-wrapper
provides a wrapper script for package management tools

The wrapper script tries to gracefully shutdown the unattended upgrades, updates the package information and tries to recover from interrupted dpkg runs before running the actual graphical package management tool (e.g. synaptic).
