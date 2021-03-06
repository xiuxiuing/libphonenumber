# Contributing to libphonenumber

Thanks for contributing to libphonenumber!

Please read the following before filing an issue. **Note that we are _not_
accepting pull requests for validation or formatting metadata updates at this
time.**

## Checklist before filing an issue

Please check the following:
*   Has the issue already been discussed in the
    [issues](http://github.com/googlei18n/libphonenumber/issues) or [discussion
    group](https://groups.google.com/group/libphonenumber-discuss)? If so, you
    may want to comment on an existing discussion.
*   Is the issue reproducible using the
    [demo](http://libphonenumber.appspot.com/)? If not:
    *   Your issue may be resolved by upgrading to the latest version of the
        library.
    *   If you are using a
        [port](http://github.com/googlei18n/libphonenumber#third-party-ports),
        issues should be reported against that project.
    *   If you are using the library through a front-end or wrapper, issues
        should be reported against that project.

## Filing a metadata issue

Please copy this template into your report and answer the questions to the best of your ability.
For acceptable evidence, [see below](#provide-supporting-evidence).

``` nomarkdown
*   Country/region affected (e.g., "US"):
*   Example number(s) affected ("+1 555 555-1234"):
*   The phone number range(s) to which the issue applies ("+1 555 555-XXXX"):
*   The type of the number(s) ("fixed-line", "mobile", "short code", etc.):
*   The cost, if applicable ("toll-free", "premium rate", "shared cost"):
*   Supporting evidence (for example, national numbering plan, announcement from mobile carrier, news article):
```

### Provide supporting evidence

Ideally, change requests for ranges should be accompanied by authoritative
evidence such as official government or public carrier documents.

If the evidence is publicly available online, please provide the link.

If the evidence is not publicly available online, make sure that you have the
rights to share this with us, and confirm this by reading and signing the
appropriate Contributor License Agreement (CLA).

See https://cla.developers.google.com/about to determine whether you need to
sign a Corporate or Individual CLA.

**By signing the CLA, you confirm that you have the rights to share the
information with us, and that we may use, modify, reproduce, publicly display,
and distribute the information in accordance with the library's [open source
license](http://github.com/googlei18n/libphonenumber/blob/master/LICENSE).**

*   [Corporate CLA](http://developers.google.com/open-source/cla/corporate?csw=1):
    *   See https://cla.developers.google.com/about and follow the instructions.
    *   Once you are all set up, either create a validation issue for your
        request, or go to the relevant open issue.
    *   Comment on the issue, using the GitHub account that's already set up for
        your Corporate CLA, with "I signed the CLA."
    *   If you're set up correctly, someone from the team will update you on the
        issue, with instructions for sending private documentation to our closed
        mailing list. Only the core libphonenumber team has access to view
        emails sent to this address.

*   [Individual CLA](http://cla.developers.google.com/about/google-individual?csw=1):
    *   See https://cla.developers.google.com/about to ensure that an Individual
        CLA is what you need to sign, and for help with troubleshooting.
    *   When signing the Individual CLA, use the same GitHub username you used
        (or will use) to file the corresponding issue.
    *   If the email address you use in the Individual CLA is not already
        associated with that GitHub account, [add
        it](https://help.github.com/articles/adding-an-email-address-to-your-github-account/).
    *   If you need to modify an Individual CLA signature, such as to change the
        GitHub username, go to https://cla.developers.google.com/clas and click
        on "Edit Contact Information".
    *   Once you are all set up, either create a validation issue for your
        request, or go to the relevant open issue.
    *   Comment on the issue, using the GitHub account that's already set up for
        your Individual CLA, with "I signed the CLA."
    *   If you're set up correctly, someone from the team will update you on the
        issue, with instructions for sending private documentation to our closed
        mailing list. Only the core libphonenumber team has access to view
        emails sent to this address.

## Filing a code issue

When filing a code issue, include the specifics of your operating system and
provide as much information as possible that helps us reproduce the problem.

Please be advised that metadata updates are prioritized over code changes,
except for bug fixes. In addition, we work with a limited number of build
systems and may not be able to support every setup.

In particular, we don't actively maintain windows builds but would be able to
accept a PR provided someone else in the open-source community could test it out
and would be able to help with the review. One way to look for such
collaborators would be to email the [discussion
group](https://groups.google.com/group/libphonenumber-discuss). Also see the
[known Windows issues](FAQ.md#what-about-windows).
