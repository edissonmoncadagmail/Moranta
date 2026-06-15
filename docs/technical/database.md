# Database Architecture

## Recommended Platform

Supabase

Reasons:

- PostgreSQL
- authentication
- storage
- vector support
- realtime capabilities

---

# Core Entities

## User

Fields:

- id
- email
- preferences
- settings
- created_at

---

## Dream

Fields:

- id
- user_id
- title
- content
- emotions
- symbols
- created_at

---

## Reflection

Fields:

- id
- user_id
- content
- mood
- created_at

---

## Affirmation Session

Fields:

- id
- user_id
- title
- intention
- created_at

---

## Meditation Session

Fields:

- id
- user_id
- type
- duration
- completed_at

---

# Privacy Requirements

Sensitive data should:

- remain user-owned
- support deletion
- support export

Users must control their data.