alinous-cartridge
=================

This is Alinous-Core cartridge for the Openshift cloud.

Alinous-Core Official Site
http://alinous.org

How to Install
==========

Type command like below with terminal

```
rhc create-app [your appname] https://raw.githubusercontent.com/alinous-core/alinous-cartridge/master/metadata/manifest.yml
```

How to Deploy developed application
==========

Clone the application's template from the gear after you install the cartridge. After that, copy your application's "ALINOUS_HOME" to the template's "ALINOUS_HOME".

Finally, git commit and git push. Then you application will be uploaded to the gear.

