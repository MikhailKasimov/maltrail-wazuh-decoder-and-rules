## maltrail-wazuh-decoder-and-rules
Maltrail decoder and rules for Wazuh Open Source Security Platform.

## Initial pull request

https://github.com/wazuh/wazuh/pull/7031

## Adding Maltrail rules and decoders

```0510-maltrail_decoders.xml``` should be placed to ```/var/ossec/etc/decoders/``` folder of Wazuh Open Source Security Platform.

```pcre2_0510-maltrail_decoders.xml``` is the variant of initial ```0705-maltrail_rules.xml``` file, but with PCRE2 regex.

Thank you words go to Alfon 🎸 Seguridad y Redes (https://twitter.com/seguridadyredes) guy!

```0705-maltrail_rules.xml``` should be placed to ```/var/ossec/etc/rules/``` folder of Wazuh Open Source Security Platform.


Ref: https://documentation.wazuh.com/current/user-manual/ruleset/custom.html

**NOTE**: IDs ```0510``` and ```0705``` are the original ones from https://github.com/wazuh/wazuh/pull/7031 .

You must use your own IDs for Maltrail rules and decoder in Wazuh implementations you have in the range from 100000 to 120000 due to Wazuh's requirements: [Adding new decoders and rules](https://documentation.wazuh.com/current/user-manual/ruleset/custom.html#adding-new-decoders-and-rules).

For example, https://github.com/socfortress/Wazuh-Rules/tree/main/Maltrail integration uses ID 100630.

## Authors

* Michael Muenz
* Julián Morales

## Thank you

Alfon 🎸 Seguridad y Redes (https://twitter.com/seguridadyredes)

## Links

[Maltrail Project](https://github.com/stamparm/maltrail)

[Wazuh Project](https://github.com/wazuh/wazuh)
