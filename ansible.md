## Example

Format: `<type>(<scope>): <subject>`

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

Type: This categorizes the commit based on its purpose, such as 
- feat (new feature)
- fix (bug fix)
- docs (documentation)
- style (formatting, missing semi colons, etc.)
- refactor (code change that neither fixes a bug nor adds a feature)
- test (adding missing tests)
- and chore (maintenance tasks).

### More example
Adding a new role to install a web server:
```scss
feat(role): add nginx installation role
```
Fixing a bug in a playbook that deploys a web application:

```scss
fix(playbook): correct web app deployment task sequence
```
Updating documentation for a database role:

```scss
docs(role): update MySQL role README with new variables
```
Refactoring a task to use a newer Ansible module:

```scss
refactor(task): use ansible.builtin.copy module for file copies
```
Adding tests for a role:

```scss
test(role): add molecule tests for Postgres role
```
Performing maintenance or minor tasks that don't fit other types:

```scss
chore: update Ansible to latest version
```
