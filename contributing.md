## Contributing to the Spring Cloud Data Flow for Kubernetes documentation

We use GitHub [Pull Requests on forked repos](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) for contributions.

#### To make changes changes locally

- Fork this repo on Github.
- Clone down the forked repo.
- `git checkout -b your-branch`
- Make changes, commit locally.
- `git push --set-upstream origin your-branch`
- Create a PR following the instructions at https://help.github.com/articles/creating-a-pull-request-from-a-fork/

#### To preview the content locally

The following steps assume that you have rbenv installed and ruby v2.3.3 is already available locally. If not see https://github.com/rbenv/rbenv.

```
cd docs-book
bundle install
bundle exec bookbinder watch
```

Point your browser to http://localhost:4567/scdf/index.html
