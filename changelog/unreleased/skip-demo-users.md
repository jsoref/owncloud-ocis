Enhancement: Demo users and groups won't be generated unless requested

We've added a new environment variable to decide whether we should generate the demo users and groups or not. This environment variable is false by default, so the demo users and groups won't be generated by default.
There are still some users and groups automatically generated: for users: Reva IOP, Kopano IDP, admin; for groups: sysusers and users.

https://github.com/owncloud/ocis/pull/2495