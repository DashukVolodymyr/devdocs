---
group: software-update-guide
title: Introduction
functional_areas:
  - Upgrade
---

The Safe Upgrade Tool (SUT) is a command line (CLI) tool that checks a Magento instance against a specific version by analyzing all the non-Magento modules installed in it.

The SUT identifies potential problems that must be fixed in your custom code before attempting to upgrade to a newer version of Magento.

The tool returns a list of errors and warnings that you must address before upgrading to a new version of Magento.

This tool is distributed as a composer package with every release of a Magento version. See [Developer]({{site.baseurl}}/safe-upgrade-tool/developer.html) topic for more information.

Refer to the [Install]({{site.baseurl}}/safe-upgrade-tool/install.html) for first steps with SUT.
