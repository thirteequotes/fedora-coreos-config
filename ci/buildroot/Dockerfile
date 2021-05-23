# This includes the build dependencies for some key packages
# such as ignition, rpm-ostree, libpod, systemd, and kernel.
# If you want another package in this list, submit a PR and
# we can probably add it.
#
# This image is used by CoreOS CI to build software like
# Ignition, rpm-ostree, ostree, coreos-installer, etc...
<<<<<<< HEAD
FROM registry.fedoraproject.org/fedora:33
=======
FROM registry.fedoraproject.org/fedora:34
>>>>>>> b6311a040e577e6d3642199342e7cade0dabd602
COPY . /src
RUN ./src/install-buildroot.sh && yum clean all && rm /src -rf  # nocache 20210426
