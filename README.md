# Audit Tracker

This application will trace through the pull requests of the repositories of an organization and evaluates if they are viable for security audits.

### What can you do with this application?

For all the operations below, you need to first authorize this application to use data of your repositories through github app. Once you have allowed access to read/write to your organization's repositories, you will be able to fully use this application features.

Below are the features provided by this application:

1. View all pull requests(PRs) throughout your organization in one place.
2. List all PRs that can be chosen for security audits within organization and selected repositories.
3. View all the PRs that can be edited automatically to be able to use for listing in security audits.

### Technology and Dependencies

This package is based on Node v18. The technologies used are:

1. React v18.3
2. Vite v5.4

### Start Server

```sh
yarn dev
```

### Build production

```sh
yarn build
```
