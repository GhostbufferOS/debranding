Packages that need debranding changes:

abrt 	See here 	DONE
anaconda 	See here 	DONE
apache-commons-net 	AppStream module with elevating branch names 	NO CHANGES REQUIRED
basesystem 	(does not require debranding, it is a skeleton package) 	NO CHANGES REQUIRED
cloud-init 	See here 	DONE - NEEDS REVIEW IN GITLAB (Rich Alloway)
cockpit 	See here 	DONE
compat-glibc 		NOT IN EL 8
dhcp 	See here 	DONE, NEEDS REVIEW IN GITLAB (Rich Alloway)
firefox 	See here – Still requires a distribution.ini ID 	MOSTLY DONE (Louis)
fwupdate 		NOT STARTED
glusterfs 	Changes don’t appear to be required 	NO CHANGES REQUIRED
gnome-settings-daemon 	No changes required for now. 	NO CHANGES REQUIRED
grub2 	(secureboot patches not done, just debrand) See here 	DONE, NEEDS REVIEW IN GITLAB AND SECUREBOOT (Rich Alloway)
httpd 	See here 	DONE
initial-setup 	See here 	DONE
ipa 	This is a dual change: Logos and ipaplatform. Logos are taken care of in rocky-logos and the ipaplatform is taken care of here. See here 	DONE
kabi-yum-plugins 		NOT IN EL 8
kernel 	See here for a potential example 	NOT STARTED
kde-settings 		NOT IN EL 8
libreport 	See here 	DONE
oscap-anaconda-addon 	See here 	DONE Requires install QA
PackageKit 	See here 	DONE
pcs 		NO CHANGES REQUIRED
plymouth 	See here 	DONE
redhat-lsb 		NO CHANGES REQUIRED
redhat-rpm-config 	See here 	DONE
scap-security-guide 	QA is likely required to test this package as it is 	NO CHANGES REQUIRED, QA REQUIRED
shim 		NOT STARTED
shim-signed 		NOT STARTED
sos 	See here 	DONE
subscription-manager 	See here 	DONE, NEEDS REVIEW
system-config-date 		NOT IN EL8
system-config-kdump 		NOT IN EL8
thunderbird 	See here 	DONE
xulrunner 		NOT IN EL 8
yum 		NO CHANGES REQUIRED
(end of CentOS list) 		
nginx 	Identified changes, in staging 	(ALMOST) DONE


Packages that need to become other packages:

We will want to create our own versions of these packages. The full “lineage” is shown, from RHEL -> CentOS -> Rocky (Where applicable)
Package 	Notes
redhat-indexhtml -> centos-indexhtml -> rocky-indexhtml 	Here
redhat-logos -> centos-logos -> rocky-logos 	Here
redhat-release-* -> centos-release -> rocky-release 	Here
centos-backgrounds -> rocky-backgrounds 	Provided by logos
centos-linux-repos -> rocky-repos 	Here
centos-obsolete-packages 	Here


Packages that Exist in RHEL, but not in CentOS:

insights-client
Red_Hat_Enterprise_Linux-Release_Notes-8-*
redhat-access-gui
redhat-bookmarks
subscription-manager-migration
subscription-manager-migration-data
