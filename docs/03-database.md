# Database

## Overview

TaskFlow uses Firebase as its backend service.

## Services

- Firebase Authentication
- Cloud Firestore

## Initial Collections

### users

Stores user information.

Example:

```
users
 └── uid
      ├── name
      ├── email
      └── createdAt
```

### tasks

Stores user tasks.

Example:

```
tasks
 └── taskId
      ├── title
      ├── description
      ├── completed
      ├── priority
      ├── dueDate
      └── userId
```

Future collections may be added as the project evolves.