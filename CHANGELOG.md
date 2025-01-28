# Changelog

All notable changes to `Deploy to Pantheon Action` will be documented in this file.

## 2.0.0 - 2025-01-28

- Default `destination_directory` is now `wp-content/` instead of `.` to match repository structure.
- Default `exclude_list` is now `.git, .gitmodules, .pantheon, uploads` (added `uploads` to exclude list).

## 1.0.0 - 2024-01-08

- Initial stable release

## 0.0.2 - 2023-11-09

- The configuration option name has been changed from `ssh_key` to `ssh-key`. This change affects the SSH key used for remote repository authentication in upstream action [deploy-to-remote-repository](https://github.com/marketplace/actions/deploy-to-remote-repository-action)

## 0.0.1 - 2023-11-09

- Initial release
