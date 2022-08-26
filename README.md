# Change Log

## [1.0.6] 2022-08-25
### Improvements

- Auth:
  - OAuth - Warn the user to provide an email
  - Session-Based login is possible user OR Email
  - Remove `old password` input for `change pass` option
- API via Flask-RestX
  - Path: `/api/` 
  - `Products`, `Sales` models   
- User profile   
  - Improved UX
  - Added `API Explorer` component
  - List the `API_KEY` (required in API usage)

## [1.0.5] 2022-08-01
### Improvements

- `Authentication`
  - Password checker (`registration` page) 
  - Change password
  - Self Account Deletion
  - Automatic suspension on failed logins 
- `Users Management` 
  - `Extended user profile`
  - Complete Users management (for `Admins`) 
  
## [1.0.4] 2022-06-28
### Improvements

- Bump UI to `Soft UI Dashboard PRO v1.0.8`
- Improved `Docker`
- Improved Codebase
- Page Compression via `Flask-Minify`

## [1.0.3] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

## [1.0.2] 2021-12-14
### Improvements

- Bump UI: Soft UI Dashboard PRO v1.0.5

## [1.0.1] 2021-12-04
### Improvements

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v2.0.0
  - Dependencies update (all packages) 
    - Flask==2.0.1 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update
  - Gulp Tooling  (SASS Compilation)
- Fixes:  
  - ImportError: cannot import name 'TextField' from 'wtforms'

## [1.0.0] 2021-06-25
### Initial release

- UI: Soft UI Dashboard PRO v1.0.1
- [Flask Codebase](https://github.com/app-generator/boilerplate-code-flask-dashboard): v1.0.6
