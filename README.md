# poe-run-helper

## Todo
- Signals handler
- Figure out Main UI
- Load layout images
- load area tips - http://poe-roadmap.com/

### run planner
use pob link n convert
- only main quests and get all skillpoints
- [ ] Base Webapp
    - [ ] choose start class
    - [ ] choose ascendency
    - [ ] choose quest rewards
- [ ] Other Webapp features
    - [ ] paste in build (optional)
    - [ ] choose when to get misc gems
    - [ ] share run plan with code
    - [ ] pob quickview option

For later
- map visualization
- data analysis
- level vs. time graph
- area & time graph
- tips reducing time for each area

### Setup

setup your virtual env

`pip install -r requirements.txt`

`python setup.py install` setup the app in env/bin

`python setup.py build_res` to build the resources

`python setup.py build_app` to build app (also runs `build_res`)
