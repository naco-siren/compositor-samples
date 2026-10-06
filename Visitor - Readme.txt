WINDOW GUEST / 窗外有客 — Compositor Study 02

3200 × 2000 px / sRGB / 144 ppi

An oversized red-headed bird peers sideways through a real old-town window. Its beak nearly meets the left frame; the right frame hides most of its body. The close view leaves its feet and perch below the canvas, while the roofs establish the deliberately impossible scale.

Editable structure:
Outside — original town photograph and cool daylight curve
Visitor — original red-headed bird photograph, editable head/body mask, daylight curve and a soft lower-body shade curve
Window — foreground window photograph, aperture mask and room curve
Typography — five editable text layers using Baskerville and Helvetica

The project embeds its source pixels and masks. It can be opened without the Assets folder. Hide Typography for artwork without lettering. Select the bird image thumbnail to move it; select its mask thumbnail to refine the cutout. Save the .comp before checking Git: export alone does not save project edits.

Photo sources supplied by the user:
Bird: Enrique Hidalgo / Pexels photo 38982994
Assets/Animals/pexels-enrique-hidalgo-1230661389-38982994.jpg
Window and old town: Mr Yin / Pexels photo 17098031
Assets/Towns - China/pexels-mr-yin-586337898-17098031.jpg
The window source was reduced to 4096 × 3072 for the embedded layers; the bird source retains its original 2880 × 3600 pixels and is placed at 145% scale. Its eye, beak and head feathers are sharper than those in the previous source. The previously enlarged bird is recoverable through Git.

The bird's starting mask uses the same local Apple Vision foreground-selection model as Compositor's Remove Background tool, followed by a slight inward edge shift. Fine feather-edge finishing remains available on the editable mask. All scene pixels come from the two photographs; the generated concept sketch is not used as a layer.

Git:
visitor-composition-baseline — recoverable initial composition
visitor-first-demo — first completed native demo, matching previews and download package
visitor-before-red-bird — user's enlarged original bird and matching reference before replacement
visitor-red-bird-v1 — close-up replacement with photo 38982994

Verified delivery:
The .comp opens and renders in Compositor with 16 layers, and the replacement was saved in the app. Typography is visible. The current 3200 × 2000 PNG previews were rendered from the saved layer hierarchy using Compositor's curve interpolation and embedded sources; they are not claimed as native exports. Native PNG/JPEG save dialogs currently show a disabled Save button. The editable project is ready for native export once that dialog issue is resolved.

Files:
Visitor - Window Guest.comp — editable native project
Visitor - Window Guest.png — complete preview with lettering
Visitor - Clean Artwork.png — same preview without lettering
Visitor - Window Guest.zip — portable project package and this readme, suitable for a repository download

The generation/refinement helpers in Workfiles are development tools, not required to open the project. Do not rerun the builder over later user edits; preserve a Git baseline first.
