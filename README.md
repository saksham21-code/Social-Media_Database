# Social-Media_Database
Implemented a database for a simplified social media platform that stores user profiles, posts, comments, and friend connections. This project ensures efficient data storage and retrieval, facilitating seamless user interactions and content sharing on the platform.

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
