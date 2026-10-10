# Credits & Licenses — Saber 3D v3 ("Saber-inspired" fan demo)

Non-commercial fan demo. **No official TYPE-MOON / Fate / FGO assets and no ripped game models are used.**
No freely licensed, faithful Saber (Artoria) model was found that could be legally redistributed on a public web page
(see "Rejected candidates" below), so the heroine is a licensed generic VRoid avatar restyled in code as a
*Saber-inspired* knight: gold hair recolour, hair pulled into a braided bun with blue ribbon and ahoge, green eyes,
blue dress, silver/gold plate armour, and an Excalibur-style sword, all made procedurally.

| File | Asset | Author | Source | License |
|---|---|---|---|---|
| assets/models/heroine.vrm | VRM1_Constraint_Twist_Sample (VRoid avatar; textures recoloured and hair geometry reshaped at runtime) | © 2022 pixiv Inc. | https://github.com/vrm-c/vrm-specification/tree/master/samples/VRM1_Constraint_Twist_Sample | VRM Public License 1.0 (https://vrm.dev/licenses/1.0/). Embedded meta: avatarPermission=everyone, commercialUsage=corporation, allowRedistribution=true, modification=allowModificationRedistribution, creditNotation=unnecessary, allowExcessivelyViolentUsage=true |
| assets/models/werewolf.glb | Werewolf (rigged version; simplified to ~90k tris, WebP textures, meshopt) | Grab3D (AI-assisted, Meshy base + Blender cleanup, per LICENSE.txt) | https://grab3d.com/models/creatures/werewolf/ | CC0 1.0 |
| assets/models/boulder.glb | Boulder 01 (simplified) | Poly Haven | https://polyhaven.com/a/boulder_01 | CC0 1.0 |
| assets/models/deadtree.glb | Dead Tree Trunk (simplified) | Poly Haven | https://polyhaven.com/a/dead_tree_trunk | CC0 1.0 |
| assets/models/tree.glb | Jacaranda Tree (simplified, meshopt) | Poly Haven | https://polyhaven.com/a/jacaranda_tree | CC0 1.0 |
| assets/hdri/meadow_2k.hdr | Meadow 2 HDRI, 2k | Poly Haven | https://polyhaven.com/a/meadow_2 | CC0 1.0 |
| assets/textures/grass_*.jpg | Aerial Grass Rock, 1k | Poly Haven | https://polyhaven.com/a/aerial_grass_rock | CC0 1.0 |
| assets/textures/metal_plate_*.jpg | Metal Plate, 1k (armour/sword roughness + normal detail) | Poly Haven | https://polyhaven.com/a/metal_plate | CC0 1.0 |
| vendor/three/ | three.js r169 + examples/jsm addons (incl. meshopt_decoder) | three.js authors | https://github.com/mrdoob/three.js | MIT |
| vendor/three-vrm.module.min.js | @pixiv/three-vrm 3.5.5 | pixiv Inc. | https://github.com/pixiv/three-vrm | MIT |

Made in code: cuirass, tassets, pauldrons, gauntlets, greaves, sleeves, collar, skirt (all fitted to the measured body
surface), hair bun/braid/ribbon/ahoge, the sword, IK sword choreography, werewolf idle/hit/death motion, grass, flowers,
slash trail and sparks.

## Rejected "faithful Saber" candidates (checked 2026-10-10)

| Candidate | URL | License shown | Why not used |
|---|---|---|---|
| [Saber] Artoria Pendragon S3 Fate — 20062020year | https://sketchfab.com/3d-models/saber-artoria-pendragon-s3-fate-c7c68d9c23264c5eb95d5e3e7f415a4b | CC BY | Uploader states "I don't know where I downloaded this model" → provenance unknown, likely not their work / possibly ripped; download also requires a Sketchfab login |
| Saber Artoria Pendragon — stylo0 | https://sketchfab.com/3d-models/saber-artoria-pendragon-93a4e4b18d35480896d5145973d92e18 | Sketchfab Free Standard + NoAI | Standard license does not allow redistributing the model file itself (a web page ships the file); login required |
| Artoria Pendragon (Saber) — JustNerro | https://sketchfab.com/3d-models/artoria-pendragon-saber-4a8acbc2128c40a6aa9a78551323571a | CC BY | Low-detail (13.9k tris, 512px textures); Sketchfab download requires login (itch.io page has no download/license) |
| Saber Lily figure scans — FrankHuang | https://sketchfab.com/3d-models/saber-lily-distant-avalon-figure-c0427506b6434c89b709bafffbe23273 | CC BY-NC / CC BY | Photogrammetry of a commercial Good Smile figure (third-party sculpt), 750k tris; login required; wrong outfit |
| Saber Alter Shinjuku — ArtLeaving | https://sketchfab.com/3d-models/saber-alter-shinjuku-version-767b95a793c54b7eb432f1e45e51ec56 | CC BY-NC | Different character variant; 75 MB; login required |
| Saber 01 — 3d Anime Girls Collection | https://sketchfab.com/3d-models/saber-01-67ecec4b208b4920ae278b9ad28f1233 | Paid store | Paid |
| Fate/Staynight-Saber — Atsushi Tamaki | https://sketchfab.com/3d-models/fatestaynight-saber-5f57038b5f0b4082a658b7698db3630d | not downloadable | Not downloadable |
| Excalibur models (Yogensia CC BY-NC-SA, betabel CC BY, Terallis CC BY) | https://sketchfab.com/3d-models/fatestay-night-excalibur-updated-dc4e601857e94a2b9c3acbd856943581 | CC BY / BY-NC-SA | Require Sketchfab login to download; a procedural Excalibur-style sword was built instead |
| MMD / Booth Saber models, official FGO assets | — | distributor-specific terms / proprietary | MMD/Booth terms typically forbid redistribution of model files and usually require login/purchase; official game assets are proprietary (ripping not allowed) |

TYPE-MOON fan-work note: this is a free, non-commercial fan demo; it ships no TYPE-MOON artwork, logos or game data.
