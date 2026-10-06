SYLVAN — App Store sample project

3200 × 2000 px / sRGB

The user's painted transitions, verdant grading and left-to-right landscape fade are preserved. All 15 non-text image/mask assets remain pixel-for-pixel identical to the user baseline. Subject is 18% larger; the three local adjustment-mask transforms were matched to the same scale and pivot after native group scaling left them in place.

Typography is reduced to three editable lines:
DOUBLE EXPOSURE — 70 px
SYLVAN — 245 px
A forest within. — 80 px
The previous small copy and rule remain as hidden editable layers.

Group transform:
Select the Subject folder's image thumbnail, press V, then use Scale in the top toolbar. Entering 118 applies a relative 18% enlargement; the group scale field returns to 100 after the operation. In the tested build, group scaling moved photo layers but did not move local adjustment masks; this project's masks have been synchronized manually. Unmasked global grading stays unchanged.

Saving and Git:
Cmd-S saves the .comp package. Exporting JPG or PNG alone does not save project edits. The user's JPG was previously excluded by .gitignore; it is now tracked. Save first, then git status can show mask, image and manifest changes.

Current exports:
Sylvan - App Store Sample.png — large subject, three-line layout
Sylvan - Poster.png — same artwork
Sylvan - Clean Artwork.png — without text
Sylvan - Double Exposure.jpg — untouched user reference
Sylvan - Cool Forest Poster.png — historical export from before the user's background/brushwork revision

Git tags:
sylvan-user-verdant-baseline — user's brushwork, grading and background before resizing
sylvan-app-store-ready — current verified delivery
