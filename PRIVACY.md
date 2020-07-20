# Privacy Policy

This privacy policy documents what data Unibeautify CI has access to about its users and what Unibeautify CI does with it.
This policy covers the use of the [Unibeautify CI GitHub App](https://github.com/apps/unibeautify-ci).
This service is intended for use as is.

This page is used to inform users ("you") regarding the policies with the collection, use, and disclosure of personal information if anyone decided to use this service.

If you choose to use the app, then you agree to the collection and use of information in relation to this policy. The collected information is required for the service to work. It is neither stored nor shared with 3rd parties.

## Information collection and use

When installing the the app you grant it access to the following three scopes

1. **Read & write access to [content](https://developer.github.com/v3/apps/permissions/#permission-on-contents)**

   The app will read repository contents, format the code [as configured](https://unibeautify.com/docs/config-file), and write the result to a new branch (e.g. `unibeautify/previous-branch-name`).

2. **Read & write access to [pull requests](https://developer.github.com/v3/apps/permissions/#permission-on-statuses)**

   The app will read pull requests, format the code format the code [as configured](https://unibeautify.com/docs/config-file), and might create a new pull request with the respective changes.

3. **Read & write access to [checks](https://developer.github.com/v3/apps/permissions/#permission-on-checks)**

   The app uses [Checks API](https://developer.github.com/v3/checks/) to provide a status (e.g. success, failed, etc) and additional details on the results of formatting the code.

4. **Read & write access to [statuses](https://developer.github.com/v3/apps/permissions/#permission-on-statuses)**

   The app uses [repository statuses](https://developer.github.com/v3/repos/statuses/) to provide a status (e.g. success, failed, etc) on the results of formatting the code.

The app receives [CheckRun](https://developer.github.com/webhooks/event-payloads/#check_run), [CheckSuite](https://developer.github.com/webhooks/event-payloads/#check_suite), [Create](https://developer.github.com/webhooks/event-payloads/#create), [Push](https://developer.github.com/webhooks/event-payloads/#push), and [PullRequest](https://developer.github.com/webhooks/event-payloads/#pull_request) events from GitHub, but any data not required for the functionality of the app is discarded.

## Sharing of data with 3rd party services

The app is hosted on [AWS](https://aws.amazon.com/).
No user data is persisted besides storage of log files and analytics.

For the purpose of monitoring and error tracking, log data is shared with [Amazon CloudWatch](https://aws.amazon.com/cloudwatch/) for live monitoring and [Amazon S3](https://aws.amazon.com/s3/) for archiving ([Amazon Web Services Privacy Notice](https://aws.amazon.com/privacy/)).
Log data is retained for 14 days.

For the purpose of analytics, data is shared with [Google Analytics](https://analytics.google.com/) ([Google Privacy Policy](https://policies.google.com/privacy)).

## Security

We value your trust in providing your personal information, thus we are striving to use commercially acceptable means of protecting it. But remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable, and we cannot guarantee its absolute security.

## Changes to this privacy policy

We may update this privacy policy from time to time.
Thus, you are advised to review this page periodically for any changes.
We will notify you of any changes by creating a pull request on this repository and leaving it open for at least 14 days to give time for you to raise any concerns.
These changes are effective immediately after they are merged into the main branch.

## Contact

If you have any questions or suggestions about this Privacy Policy, do not hesitate to contact us at `support@unibeautify.com`.
