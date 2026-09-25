# Gitignore Explanation

## 1. Why should `.env` be ignored?

`.env` files may contain sensitive information such as passwords, API keys, database credentials, and tokens. They should not normally be committed to Git.

## 2. Why should `node_modules/` generally be ignored?

The `node_modules` directory contains installed dependencies. It can become very large and can normally be recreated using the project's package configuration.

## 3. What is `.DS_Store`?

`.DS_Store` is a file automatically created by macOS Finder to store folder display information. It is not part of the application and normally does not need to be tracked.

## 4. Why may log files be ignored?

Log files can contain temporary debugging information and can grow continuously. They usually do not belong in the source repository.

## 5. Additional pattern

The additional pattern used is:

```text
*.tmp