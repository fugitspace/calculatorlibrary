## Testing CircleCI
--

#### Checklist
- [x] Create repo
- [x] Make sure you have an environment set: (package.json, venv, etc)
- [x] create .circleci directory under project roor
- [x] create .cicleci/config.yml file
-- Pay attention to indentation. It consumed my whole 30 minutes fixing indentantion until 4 spaces came to the rescue
- [x] add project in circleci (assuming you have an account that's already linked with github/gitlab)
- [x] run build
- [x] everytime something is pushed to branch, circleci runs the build automagically and gives results.
- [x] this is how Continuos Integration is useful. Know of any bugs with every commit.
- [x] Take some popcorn and enjoy 

#### Checklist: .circleci/config.yml
- [] Specify the version 