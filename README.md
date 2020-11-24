Elixir rate limiting library using ETS and Postgres

---
Here I'll separate and release as a library the rate limiting implemented here: https://github.com/santiment/sanbase2/pull/2329

At production we use in parallel nginx rate limiting but it cannot easily use the user subscriptions and different types of products/authorization.
Read the description of the linked PR for more information how it works.
