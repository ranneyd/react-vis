# react-vis-updated

A fork of (react-vis)[https://github.com/uber/react-vis] that has
- a new NPM build that includes all the bug fixes since April 18th (why haven't they made a new build?!)
- A fix to the ChartLabel component, which should subtract margins from the full width, not add them (understandably confusing since the value passed to it as `innerWidth` is really `outerWidth`. Same goes for the height)

Changes are minimal, so I encourage you to look at the git history. There you can see that I only added what I said above (and no spyware).