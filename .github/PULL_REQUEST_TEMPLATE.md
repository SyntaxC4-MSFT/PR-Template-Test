# Azure Documentation Pull-Request

Congratulations on submitting your pull-request to the Azure Docs repository. Follow the documentation below to ensure that your work gets reviewed, approved and merged in a timely manner.

In this message:

1. [Before you begin](#before-you-begin)
1. [PR Merge Check-list](#pr-merge-check-list)

## Before you begin

We've noticed in the past that depending on how your branch was created, it could impact the success of your pull request.

Follow these steps to ensure that you are tracking the proper repository for your branch:

1. Set the upstream for your local branch

    `git branch --set-upstream-to MicrosoftDocs/<branch_name>`

    > `<branch_name>` is the name of the branch you will be merging into, such as `master` or a release-branch.

## PR Merge Check-list

- [x] Create a Work-in-Progress PR with new or newly modified `.md` file.
    - [ ] Update topic `ms.date` metadata value
    - [ ] Update topic `author` and/or `manager` metadata value (if required)

### Table of Contents and Service Landing Pages

- [ ] New Topic in Table of Contents (ToC)
- [ ] New Topic in Landing Page (Quickstart or Tutorial only) [[Open Ticket](https://MSDNHelp)]

### PR Acceptance Criteria

Your PR could be automatically merged, if you follow the [Automatic Acceptance Criteria](https://review.docs.microsoft.com/en-us/help/contribute/contribute-how-to-write-pull-request-etiquette?branch=master#in-a-hurry-submit-prs-that-can-be-accepted-automatically-microsoft-employees), otherwise complete the following:

- [ ] Acrolinx Score of 80 or higher
- [ ] Content is Free of [Blocking Issues](https://review.docs.microsoft.com/en-us/help/contribute/contribute-how-to-write-pull-request-quality-criteria?branch=master#blocking-content-quality-items)
- `Title` and `Description` follow the [SEO Guidelines](https://review.docs.microsoft.com/en-us/help/contribute/contribute-how-to-write-seo-basics?branch=master)

### Pre-Sign off Review

- [ ] APEX team member who is a SME
- [ ] APEX team member without expertise in this subject
- [ ] Product Group Review (Dev or PM)
- [ ] Peer Team Member for MVC Guidelines
- [ ] Marketing Team Member
- [ ] CSS (Support) Review
- [ ] (Large PRs) Request Pre-Approval from [Documentation PR Reviewers](mailto:azdocprs)

## Sign off

- [ ] Get Business Approval (Changes to Overview, Quickstart, Tutorial, or Samples ToC sections)
- [ ] Provide a `#sign-off` in the comments below

## Post Sign-off, Pre Publish

- [ ] Publish any external dependencies for your article:
    - [ ] Azure Samples Repository
    - [ ] Publish to the download center

## Post Publish

- [ ] Verify a successful publish to live
    - [ ] Ensure includes render
    - [ ] Ensure graphics are render
    - [ ] Ensure Code includes render
    - [ ] Review for Staging links
- [ ] Register article for social media amplification
- [ ] Sign up for LiveFyre [feedback notifications](http://aka.ms/skyeye/notification)
