# test_autogithubrelease

To create a release and trigger the github action:

- create a new branch
- make modifications doing whatever you want simply respect the commitizen tool rules
- merge with `main` (if the merge is squashed only the title of the squash commit needs to respect the commitizen convention)
- back on main execute:
  - `cz bump`
  - `git push`
  - `git push origin vx.x.x`
- watch the magic in actions: https://github.com/12rambau/test_autogithubrelease/actions
