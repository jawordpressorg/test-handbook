# How to Write a Call for Testing

When a feature is ready for a beta audience, post a call for testing to [make/core](https://make.wordpress.org/core/wp-admin/post-new.php). Use this handy template and checklist when creating your post. Or, skip all of this. Publishing anything and tagging it [#needs-testing](https://make.wordpress.org/test/tag/needs-testing/) is sufficient and better than not posting.

## Template

### What is it?

Describe the feature. Include screenshots. Describe any goals and gating criteria, such as parity requirements.

### Where is it?

Describe how to get to the feature. Direct links are good.

### What to test

Describe the primary flows to test. Consider using bulleted flow or a visual record.

### What to expect

List known issues and shortcomings (bug tracker links are helpful). Set expectations.

### How to report

Provide trac or github links, include the component.

### Timeline for testing

Express urgency and priority. If there are target dates, provide them.

## Checklist

*   Introduce yourself.
*   Explain the feature or update.
*   Link to the feature.
*   List known issues.
*   Provide a short list of testing steps.
*   Mention how to provide feedback.
*   Include a date for the completion of the testing.
*   Include screenshots from multiple devices.
*   Keep a beta testing audience in mind.
*   Tag the post [#needs-testing](https://make.wordpress.org/test/tag/needs-testing/).

## Gutenberg

Gutenberg calls for testing are posted on [make/test](https://make.wordpress.org/test/) and typically follow this format:

*   Short summary of the type of update.
*   Written statement about the goal of Gutenberg.
*   Download button.
*   Link to [Get Setup for Testing](https://make.wordpress.org/test/handbook/get-setup-for-testing/) in the handbook.
*   Any notes about which WP version to test with (i.e. latest stable vs trunk).
*   List of suggested testing steps.
*   Deprecation notes.
*   Mention where to file bugs or feedback.
*   Invitation to get more involved and ask questions in WP Slack.

To come up with the list of suggested testing steps, review the changelog for the release being tested or look at the corresponding milestone in GitHub. Go through each pull request and decide which ones would be most relevant to test. Write a short line explaining how to test the issue and include a link to the pull request for more detail. Typically, the steps are ordered by most important things to test at the top. Generally, it’s good to limit the list to 7 to 12 items and try not to go over 20. If there are a lot of items or a set of items that make sense to break out then you can put those in another section (e.g. Accessibility, Mobile, i18n, Plugins, or a Bonus section with things that are a bit more difficult to test). See [posts tagged “call for testing” on make/test](https://make.wordpress.org/test/tag/call-for-testing/) for examples.