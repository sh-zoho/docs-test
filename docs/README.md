# API Reference

## Base URL

All API requests are made to:

{% embed url="https://api.acme.com/v1" %}

{% include ".gitbook/includes/api-warning.md" %}

## Endpoints

### GET /users

Returns a list of all users in your account.

**Parameters:**

* `limit` (integer) — Maximum number of results. Default: 20
* `offset` (integer) — Pagination offset. Default: 0

### POST /users

Creates a new user.

**Request body:**

* `name` (string, required) — Full name
* `email` (string, required) — Email address
* `role` (string) — User role. One of: admin, editor, viewer

### DELETE /users/{id}

Deletes a user by ID.

{% include ".gitbook/includes/api-warning.md" %}
