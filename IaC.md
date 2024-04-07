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
- feat (new feature): Adding new roles, playbooks, or tasks that introduce new capabilities to the infrastructure. For example, provisioning a new type of server, implementing a backup solution, or adding a load balancer configuration.
- fix (bug fix): Resolving issues that prevent the infrastructure code from executing as intended, such as fixing incorrect task sequences, remedying idempotency issues, or addressing misconfigurations that affect infrastructure stability or performance.
- docs (documentation)
- style (formatting, missing semi colons, etc.)
- refactor (code change that neither fixes a bug nor adds a feature): Modifying roles, playbooks, or tasks to improve readability, reusability, or efficiency, such as consolidating tasks, improving variable usage, or adopting newer Ansible features for cleaner code, without introducing new functionality.
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
