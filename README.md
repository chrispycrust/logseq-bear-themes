# logseq themes

inspired by rcvd's original bear theme:  https://rcvd.github.io/logseq-bear-theme/

but focussing on reproducing my own favourite themes from Bear Pro (Solarized Light and Charcoal)

bulk of code that i modified was derived from this page: https://docs.logseq.com/#/all-pages

## original light theme view in Bear 

### Solarized Light

![Solarized Light theme screenshot](./images/solarized-light.png "Solarized Light theme viewed in Bear app")

### logseq solarized theme so far

![](./images/problem-1.png "Solarized Light theme viewed on Logseq app")

## dark theme

### original charcoal theme viewed in Bear

![Charcoal theme screenshot](./images/charcoal.png "Charcoal theme viewed in Bear app")

### logseq charcoal theme so far

![](./images/logseq-charcoal-progress.png "Charcoal theme viewed in Logseq app")

- minor colours still off (code inline and code colours)
- the menu font colour for settings is too light, it uses the same colour as the other menu links 

### style problems

- sidebar and blockquote font should be bigger than main text font 
- any favourited or recent pages should be indented to show clear folder structure
- unable to target:
    - reference links
        - hover makes background blue ... seems to be dependent on something else in the code that isn't visible in dev tools
        - get rid of auto brackets around reference links
        - preview of reference link is automatically set to incorrect colour making for uncomfortable reading
        ![tooltip problem](./images/problem-2.png "tool tip background uncomfortable colour")
    - dialogue pop up box in solarized theme for search function, settings etc. seems to be automatically set to `--ls-secondary-background-color`
    ![solarised dialogue box styling problem](./images/problem-3.png "uneapping search colour theme")
    - the hover background over the expanding sidebar menu "favourites" and "recent" in solarized theme is hard to read
    ![left side bar hover styling problem](./images/problem-4.png "problem")
    
### non-styling problems

- not sure where or how to host a css file directly so that myself and others can simply use `@import url('')` the way rcvd did it
- set up a more efficient testing environment for this type of modification
- ~~not sure how to make folders in github.~~
    - manual way: just drag the folder into the 'upload file' area on Github
    - still not sure why this problem was happening: i made a new repo directly on GitHub, then cloned a copy on github desktop, added folders directly to the cloned directly but when i pushed the changes, it stalled and wouldn't upload so i had to commit directly on github ... 
    - would also like to learn how to clone repos using the other methods via ssh and CLI

## what I've learnt

first time i've tried to read and build on someone else's code using dev tools extensively, but wasn't really systematic at first with finding out which parts of the interface they've associated with certain colours, didn't take the time to understand how they thought and organised their code. tbh i found their naming convention a bit confusing ... for example, "quarternary" for the fourth colour that (i'm guessing) is central to the theme

## to attempt in future 

- would like to try reproduce the tabler icons idea by nmartin84 in https://github.com/nmartin84/logseq-flow
- would be cool to also change logseq icon to suit theme selected, the way that Bear icon does :) 
- redo style for Olive Dunk, a brighter, fresher look than solarized 

![Olive Dunk theme screenshot](./images/olive-dunk.png "Olive Dunk theme viewed in Bear app")
