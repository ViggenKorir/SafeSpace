# SafeSpace

SafeSpace is a web platform meant to provide Mental Health Support in a secure manner.

## Overview

This CLI app is designed for user management and content interaction (posts and comments) with the following key features:

## Features:

#### 1. User Management:

Create user accounts with a unique username and email.
Log in and log out to manage sessions.

#### 2. Post Management:

Authenticated users can create posts.
Posts are linked to the logged-in user.

#### 3. Comment System:

Only logged-in users can comment on posts.
Comments are linked to both the post and the user who created the comment.

#### 4. Authentication:

Users must log in with their username to add comments or posts.

#### 5. Database:

The app uses SQLAlchemy ORM with Alembic for migrations.
Tables include users, posts, and comments.
