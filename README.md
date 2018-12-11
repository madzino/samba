Add DOMAIN in ifcfg-eth0 file to avoid NETWORKER changing the resolve.conf.

Disable SELINUX

vi /etc/selinux/config and edit the file. 

Reboot

Install dependencies

yum -y yum install attr bind-utils docbook-style-xsl gcc gdb krb5-workstation \
       libsemanage-python libxslt perl perl-ExtUtils-MakeMaker \
       perl-Parse-Yapp perl-Test-Base pkgconfig policycoreutils-python \
       python2-crypto gnutls-devel libattr-devel keyutils-libs-devel \
       libacl-devel libaio-devel libblkid-devel libxml2-devel openldap-devel \
       pam-devel popt-devel python-devel readline-devel zlib-devel systemd-devel \
       lmdb-devel jansson-devel gpgme-devel pygpgme libarchive-devel wget

