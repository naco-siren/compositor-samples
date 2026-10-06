SYLVAN — App Store sample project

3200 × 2000 px / sRGB

The current milestone preserves the user's final brushwork: the Fog Forest mask clears the nose bridge, the portrait edge is smoother, and local curve masks coordinate the subject. The verdant canopy and left-to-right landscape fade are retained. Subject remains 18% larger than the earlier user baseline.

The three primary editable lines are:
DOUBLE EXPOSURE — Baskerville, 70 px
SYLVAN — 245 px
A forest within. — 96 px
The user repositioned the heading/title and restored the two-line description and bottom-left footer. Corner captions, description and footer use 36 px type. The fine rule is retained as a hidden editable layer. All seven text layers are visible and editable.

Group transform:
Select the Subject folder's image thumbnail, press V, then use Scale in the top toolbar. Entering 118 applies a relative 18% enlargement; the group scale field returns to 100 after the operation. In the tested build, group scaling moved photo layers but did not move local adjustment masks; this project's masks have been synchronized manually. Unmasked global grading stays unchanged.

Saving and Git:
Cmd-S saves the .comp package. Exporting JPG or PNG alone does not save project edits. The user's JPG was previously excluded by .gitignore; it is now tracked. Save first, then git status can show mask, image and manifest changes.

Current exports:
Sylvan - Double Exposure.jpg — user's current 3200 × 2000 export, reviewed against the saved project preview and the open app
The old App Store Sample, Poster and Clean Artwork PNGs were removed by the user; this milestone preserves those deletions. Earlier exports remain recoverable from their Git revisions.
Sylvan - Cool Forest Poster.png — historical export from before the user's background/brushwork revision

Design review, 2026-10-05:
No blocking visual issue was found for use as the demo artwork in the first App Store screenshot. Review covered the full image, face and neck at source resolution, and a 640 × 400 reduction. Portrait/canopy continuity, the cleared nose-bridge background, headline hierarchy and overall composition are sound. Secondary small copy becomes decorative at thumbnail size; minor pale edge remnants at close inspection do not distract at the intended display scale. The final listing composition with app chrome and marketing copy has not been reviewed here.
The saved package contains 23 layers with all referenced image and mask assets present and readable. No design changes were made during this review.

Git tags:
sylvan-user-verdant-baseline — user's brushwork, grading and background before resizing
sylvan-app-store-ready — initial large-type delivery
sylvan-serif-details — previous serif-heading delivery
sylvan-app-store-milestone — reviewed user-polished project and matching JPG export
