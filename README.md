# GitHub Marketplace

Just browsing the GitHub Marketplace this morning. There are a few things I want to do:

- Find and report on some trends with an API
- Scope out the development environment
- Find some apps that would genuinely benefit me
- Find some apps that might genuinely benefit you

*Here's what I found:*

GitHub maintains docmentation in a Git repo, as you might expect. I wish Atlassian did this.

When you start reading, though, things get dim. Fast.

"You are an expert software technical writer…"

https://github.com/github/docs/blob/main/content/search-github/searching-on-github/searching-github-marketplace.md

What I really want to do is search the Marketplace with their API.

If I want to use REST, my choices are limited to operations I won't use for this, even as a starting point.

These endpoints allow you to see which customers are using a pricing plan, see a customer's purchases, and see if an account has an active subscription.

- List plans
- List accounts for a plan
- Get a subscription plan for an account
- List subscriptions for the authenticated user

[Postman isn't much help.](https://www.postman.com/xe555/github-api/overview)

If I can get the app_slugs and do a lookup on those, I might be able to get some statistics back.
For now, I can only return responses for my own app_id/key pair.

You can do this too, by ptoviding your JWT and app_slug in the notebook.
