> [!WARNING]
> **This repository has been archived**
> 
> IBM Legacy Public Repository Disclosure: All content in this repository including code has been provided by IBM under the associated open source software license and IBM is under no obligation to provide enhancements, updates, or support.
> IBM developers produced this code as an open source project (not as an IBM product), and IBM makes no assertions as to the level of quality nor security, and will not be maintaining this code going forward.


# cics-policy-samples

Sample CICS policy system rule to monitor system health.

The policy will result in a CICS message DFHMP3009 being written when the number of active tasks in your CICS regions goes above 90% of your MXT value.

`DFHMP3009 07/05/2017 11:39:27 IYK2Z3B1 Task 00252 (STRT) has triggered a taskThreshold system rule goes_above_90_percent_of_MXT FROM=90, TO=91) defined by policy mySystemRules in bundle CICSDEV_system_rule.`

The article [Using CICS policy system rules to monitor system health](https://developer.ibm.com/cics/2017/07/04/using-cics-policy-system-rules-monitor-system-health/) describes the steps to create this policy using CICS Explorer.

For a full list of the types of policies, an how to define them in CICS bundles, and install them in CICS see [CICS Policies](https://www.ibm.com/support/knowledgecenter/SSGMCP_5.5.0/fundamentals/policies/policies.html).

## Pre-requisites

* CICS TS V5.1 or later.

## License

This project is licensed under [Apache License Version 2.0](LICENSE).
