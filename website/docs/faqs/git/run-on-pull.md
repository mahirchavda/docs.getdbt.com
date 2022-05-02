---
title: Why is Run on Pull request grayed out?
---

If you're unable to enable Run on Pull requests, you'll want to make sure your existing repo was not added via the Deploy Key auth method.

If it was added via a deploy key method, you'll want to use the [GitHub auth method](https://docs.getdbt.com/docs/cloud-installing-the-github-application) to enable CI in dbt Cloud.

In order to enable Run on Pull requests, you'll want to remove dbt Cloud from the Apps & Integration on GitHub and re-integrate it again via the GitHub app method.

If you've tried the workaround above and are still experiencing this behavior - reach out to the Support team at support@getdbt.com and we'll be happy to help!

</File>
