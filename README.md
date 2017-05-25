Project Janus is a platform to help unsatisfied tenants to find better accomodation near they current place of stay. They can also find poetntial roommates to bunk in with.

This application is built using Ruby in Rails.

## Coding Style

1. Ruby

	We use [Rubocop](https://github.com/bbatsov/rubocop) to perform static analysis of the code according to rules defined in `.rubocop.yml`. Basically, it follows [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide) and [Rails Style Guide](https://github.com/bbatsov/rails-style-guide).

	```bash
	# Run rubocop
	bundle exec rubocop
	```

2. Slim - [Slim-Lint](https://github.com/sds/slim-lint)

  ```bash
  # Run slim-lint
  slim-lint .
  ```

3. SCSS - [SCSS-Lint](https://github.com/brigade/scss-lint)

  ```bash
  # Run scss-lint
  scss-lint
  ```

## Branch Policy

We follow the [Github Flow](https://guides.github.com/introduction/flow/) when developing the application, and name our branches as follow:

- `master` is the active development branch

Local development branch naming:

- `feature/<your-branch-name>` for substantial new feature or function
- `enhance/<your-branch-name>` for minor feature or function enhancement
- `bugfix/<your-branch-name>` for bug fixes
