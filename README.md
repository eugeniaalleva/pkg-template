# Python Package Template

To use this template change:
- folder name to your pkg name
- `makefile` line 14 to your pkg name
- `LICENCE` line 3 with your name/your licence
- `pyproject.toml` line 5-17 with info and dependencies

To active github workflow for automatic publishing upon new 
version push on main branch do
`cp -r workflows/.github .`
Then change line 25 of `.github/workflows/publish.yml` with
with your python version. Link pending project on [pypi](`https://pypi.org/manage/account/publishing/`).
