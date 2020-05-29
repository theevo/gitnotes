# Show off how much coding you've done

```
git diff --stat <commit1> <commit2>
```

This will show pluses (+) and minuses (-) next to the files files you've changed as well as show numbers for the following numbers:

1. Files changed
2. Insertions
3. Deletions

## Output sample

```
 FormMetalSlug.xcodeproj/project.pbxproj                           |  8 +++---
 FormMetalSlug/Helpers+Extensions/PDFPageExtension.swift           | 24 ++++++++++++++++
 FormMetalSlug/Storyboard/Base.lproj/Main.storyboard               | 64 +++++--------------------------------------
 FormMetalSlug/ViewControllers/DocumentBrowserViewController.swift |  3 +-
 FormMetalSlug/ViewControllers/DocumentViewController.swift        | 36 ------------------------
 FormMetalSlug/ViewControllers/PDFViewController.swift             | 36 +++++++++++++++++-------
 README.md                                                         | 45 ++++++++++++++++++++++++++++++
 7 files changed, 107 insertions(+), 109 deletions(-)
```


## Reference

`git log` to get your commit id's. You only need the first 7 chars.

