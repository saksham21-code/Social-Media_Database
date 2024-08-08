# Social-Media_Database

This project contains the schema for a simplified social media platform database using PostgreSQL.

## Database Schema

The database includes the following tables:

- Users
- Posts
- Comments
- Likes
- Followers

## Setup

1. Install PostgreSQL.
2. Create a new database:

    ```sh
    createdb social_media_db
    ```

3. Apply the schema:

    ```sh
    psql -d social_media_db -f schema.sql
    ```

## Schema

The schema is defined in `schema.sql`.
