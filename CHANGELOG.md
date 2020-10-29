## 0.8.3 (2020-10-29)

### Refactor

- **automator.py**: remove unecessary prints

### Fix

- **get_all_droplets**: Fix no pagination handling

## 0.8.2 (2020-10-25)

### Refactor

- removed unused imports

## 0.8.1 (2020-10-24)

### Refactor

- **.gitignore**: add .vscode

### Fix

- **droplet.py**: vpc_uuid is now optional

## 0.8.0 (2020-10-24)

- Add auto-bump

## 0.7.0 (2020-10-21)

### Feat

- **droplet.py**: add tags field to droplet model

## 0.6.0 (2020-10-20)

### Feat

- **automator.py**: Destroy droplet feature

### Fix

- **pyproject.toml**: Fix importlib module required for some python versions (not native)

## 0.5.0 (2020-10-19)

### Feat

- **automator.py**: turnoff_droplet

### Refactor

- **test_assign_floating_ip.py**: fixed typo

### Fix

- **test_automator.py**: Stash mocks after each use

## 0.4.0 (2020-10-04)

### Feat

- **Automator**: Add get_all_droplets to Automator

## 0.3.1 (2020-09-29)

### Refactor

- **anti-patterns**: Fixed anti-patterns

## 0.3.0 (2020-09-29)

### Feat

- **automator.py**: assign floating ip to droplet

## 0.2.0 (2020-09-29)

### Feat

- **project**: Added commitizen for following commit convention

### Fix

- added .env.sh

## 0.1.3 (2020-09-28)

### Fix

- importing submodules

## 0.1.2 (2020-09-28)

### Fix

- updated version and readme
- ignoring setup.py for code coverage
- codecov yaml typo
- codecov and setup.py
- remove unused import
- Chained comparison PYL-R1716
- unused var
- fixing attrib op
