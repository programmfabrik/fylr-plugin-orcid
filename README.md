# fylr-plugin-orcid

This fylr plugin connects users to the [ORCID (Open Researcher and Contributor ID) website](https://orcid.org/). Each user can store an ORCID id in the user account. This links the user to a persistent identifier for their researcher profile.

## Configuration

The plugin needs no base configuration. It adds a tab "ORCID" to the user editor in the user management. The tab is only shown for users of the type "easydb".

The tab has these fields:

* **ORCID**: the ORCID id of the user, for example `0000-0002-1825-0097`.
* **URL**: a link to the ORCID profile of the user. If the entered id does not match the ORCID format, a hint with details about the format is shown instead.

The id is saved in the custom data of the user account.
