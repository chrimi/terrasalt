# Terraform + Salt integration module

This module will install salt on a newly created host and also connect that minion to a saltmaster via an asynchronnous saltapi wheel command invocation. If the host is being destroyed it will unregister the minion from the salt master via an asynchronnous saltapi wheel command invocation. For more details please see the [Readme](../../../README.md) in the root level of this repository.
