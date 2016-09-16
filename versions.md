# Kazoo versions.

* You might want to check out the information on "upgrading" as well.

*  Install 3.22 at this point
  * 3.22 Spring 2016
  * 3.21 (fall 2015)
  * 3.20 (summer 2015)
  * 3.19 March 2015 (being retired as of May 10, 2015)
  * 3.18 was short lived before it 3.19 arrived
  * 3.16 and before are not worth starting a new install

* Versions 15B, 16B, 17, 18 etc.
  * This refers to the version of Erlang underneath Kazoo.
  * As of Feb 2015
    * 15B is stable/running 
    * 16B is broken
    * 17.5 skip
    * 18+ is the next target Erlang relese for Kazoo 4.0

* Kamaillio 4.0 vs 4.2
 * Kamaillio flipped from 4.0 to 4.2 in the 3.18 to 3.19 version bump
 
* Freeswitch
 * mature voip project, use the canned stuff!
 * No reason to maintain local changes unless you are a developer

```# rpm -qa | grep -i 'kaz\|monster' | sort```

* Monster or Kazoo-UI versions vs Kazoo versions.
  * These are loosely coupled..
  * Having a consistent Kazoo itself is the starting point
  * then you can worry about your monster versions.


* 3.22-63
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-configs-3.22-18.el6.noarch
kazoo-freeswitch-R15B-1.4.26-0.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-kamailio-4.3.4-8.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64
kazoo-prompts-3.22-0.el6.noarch
kazoo-R15B-3.22-63.el6.x86_64

monster-ui-accounts-3.22-7.el6.noarch
monster-ui-core-3.22-34.el6.noarch
monster-ui-numbers-3.22-3.el6.noarch
monster-ui-pbxs-3.22-6.el6.noarch
monster-ui-voip-3.22-15.el6.noarch
monster-ui-webhooks-3.22-3.el6.noarch
```

* 3.22-56
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-configs-3.22-15.el6.noarch
kazoo-freeswitch-R15B-1.4.26-0.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-kamailio-4.3.4-8.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64
kazoo-prompts-3.22-0.el6.noarch
kazoo-R15B-3.22-56.el6.x86_64

monster-ui-accounts-3.22-7.el6.noarch
monster-ui-core-3.22-26.el6.noarch
monster-ui-numbers-3.22-3.el6.noarch
monster-ui-pbxs-3.22-4.el6.noarch
monster-ui-voip-3.22-13.el6.noarch
monster-ui-webhooks-3.22-3.el6.noarch
```

* 3.22-51
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-prompts-3.22-0.el6.noarch
kazoo-configs-3.22-15.el6.noarch
kazoo-kamailio-4.3.4-8.el6.x86_64
kazoo-freeswitch-R15B-1.4.26-0.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64
kazoo-R15B-3.22-51.el6.x86_64
```

* 3.22-50
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64

kazoo-prompts-3.22-0.el6.noarch
kazoo-configs-3.22-15.el6.noarch
kazoo-kamailio-4.3.4-8.el6.x86_64
kazoo-freeswitch-R15B-1.4.26-0.el6.x86_64
kazoo-R15B-3.22-50.el6.x86_64
```

* 3.22-5 composite files
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64

kazoo-prompts-3.22-0.el6.noarch
kazoo-kamailio-4.3.1-5.el6.x86_64
kazoo-freeswitch-R15B-1.4.23-0.el6.x86_64
kazoo-configs-3.22-2.el6.noarch
kazoo-R15B-3.22-5.el6.x86_64
```

* 3.21-44 composite files
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64

kazoo-prompts-3.21-1.el6.noarch
kazoo-configs-3.21-4.el6.noarch
kazoo-R15B-3.21-44.el6.x86_64

??kazoo-kamailio-4.2.3-16.el6.x86_64 [last 4.2.3]
??kazoo-freeswitch-R15B-1.4.15-3.el6.x86_64
```

* 3.21-36 composite files
```
kazoo-prompts-3.21-1.el6.noarch
kazoo-configs-3.21-3.el6.noarch
kazoo-json-c-master-0.el6.x86_64
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64
kazoo-kamailio-4.2.3-16.el6.x86_64
kazoo-R15B-3.21-36.el6.x86_64
kazoo-freeswitch-R15B-1.4.15-3.el6.x86_64
```

* 3.21-33 composite files..
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64

kazoo-prompts-3.21-1.el6.noarch
kazoo-configs-3.21-3.el6.noarch
kazoo-R15B-3.21-33.el6.x86_64
kazoo-freeswitch-R15B-1.4.15-3.el6.x86_64
kazoo-kamailio-4.2.3-16.el6.x86_64
```

* 3.20-35 composite files
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64

kazoo-prompts-3.20-0.el6.noarch
kazoo-configs-3.20-4.el6.noarch

kazoo-R15B-3.20-35.el6.x86_64
kazoo-freeswitch-R15B-1.4.7-11.el6.x86_64
kazoo-kamailio-4.2.3-16.el6.x86_64
```

* 3.20-12 composite files
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64

kazoo-prompts-3.20-0.el6.noarch
kazoo-configs-3.20-3.el6.noarch

kazoo-R15B-3.20-12.el6.x86_64
kazoo-freeswitch-R15B-1.4.7-11.el6.x86_64
kazoo-kamailio-4.2.3-16.el6.x86_64
```

* 3.22-0 composite files
```
kazoo-bigcouch-R15B-0.4.x-1.el6.x86_64
kazoo-json-c-master-0.el6.x86_64
kazoo-librabbitmq-master-1.el6.x86_64

kazoo-prompts-3.22-0.el6.noarch
kazoo-kamailio-4.3.1-5.el6.x86_64
kazoo-configs-3.22-0.el6.noarch
kazoo-freeswitch-R15B-1.4.23-0.el6.x86_64
kazoo-R15B-3.22-0.el6.x86_64
```

stormqloud.ca
