# Early VR Tech Demos — A Curated Archive

A community collection of the experimental, homebrew, and showcase **VR tech demos** from
the early PC-VR era — the vibrant Oculus Rift DK2 days of 2014–2016 — plus a few later
free experiences that carry the same spirit. Think photorealistic room/apartment scans,
architectural walkthroughs, "interesting spaces," and small showcase experiences that
people built and shared for the joy of it.

> **Scope:** Free (or formerly free) tech demos for **any PC-compatible headset** — Oculus
> Rift (DK1/DK2/CV1), HTC Vive, Valve Index, and Quest via Link. This repo curates **links
> only**; we don't host any files. Where an original download is gone, we point to the
> Internet Archive or Wayback Machine capture.

## How to read the tables

- **Link status:** ✅ live · 🟡 archive/Wayback only · ⚪ store page (still available) · ❌ dead (listed for reference)
- Most DK2-era demos need a **legacy Oculus runtime (0.5–0.8)**; modern headsets generally
  need a wrapper like **[Revive](https://github.com/LibreVR/Revive)** or
  **[OpenComposite](https://gitlab.com/znixian/OpenOVR)**. See [Running these today](#running-these-today).

---

## Room / scan / architectural demos (the "interesting spaces" core)

| Demo | Creator | What it is | Link(s) | Status | Notes for today |
|---|---|---|---|---|---|
| **4th Floor Studio** | Brendon Coyle (QuiteNice) | Photorealistic 3D scan of a real studio apartment — the classic "presence" demo | [Wayback page w/ downloads](http://web.archive.org/web/20190919042904/https://www.quitenice.co/blog/2014/8/3/4thflrstudio) · [Dropbox (SDK 0.7)](https://www.dropbox.com/s/nxxjwwt0qsc700f/4thFlrStudioVR%28SDKv0.7.0.0%29.zip?dl=0) · [Vive edition](https://www.dropbox.com/s/u2te1115smb9aac/4thFlrStudioVR%28ViveEdition%29.zip?dl=0) · [Quest APK](https://www.dropbox.com/s/vooug7fuodnt20w/QuiteNice_4thFlrStudio.apk?dl=0) | 🟡/✅ | 215 MB. Has a DK2 (SDK 0.7), a Vive, and a standalone Quest build. |
| **Unreal Paris** | Benoît Dereau | Famous photorealistic Paris apartment arch-viz in UE4 | [Official site](https://www.benoitdereau.com/) · [Wayback (1.3 w/ Oculus build)](http://web.archive.org/web/20150403090140/http://www.benoitdereau.com:80/unrealparis.html) | 🟡/✅ | Original had Windows / Oculus / Android builds. 2018 update supports Rift + Vive. |
| **Arch Virtual — Residential Condo** | Arch Virtual | Explorable condo arch-viz with material/color config, built in Unity 5 (Immerse) | [Blog + DK2 download](https://archvirtual.com/2015/11/10/architectural-visualization-virtual-reality/) · [Demo page](https://archvirtual.com/architectural-visualization-demo/) | ⚪ | DK2 build. Studio later shipped *Arch Virtual HQ* free on Steam. |
| **Realities** | Realities.io | Modern photogrammetry walkthroughs of real-world scanned locations — the spiritual successor to the scan demos | [Steam (free)](https://store.steampowered.com/app/420170/Realities/) · [realities.io](https://realities.io) | ⚪ | Vive/Rift/Index. Free. The best modern parallel to 4th Floor Studio. |

---

## Classic showcase, ride & "first VR moment" demos

| Demo | Creator | What it is | Link(s) | Status | Notes |
|---|---|---|---|---|---|
| **Tuscany** | Oculus VR | The original villa + garden showcase; everyone's first VR memory | [archive.org (DK1/DK2)](https://archive.org/details/ovr_unity_0.4.3.1_demo_win) | 🟡 | Bundled with old Oculus Unity integration. |
| **Sixense Tuscany (Razer Hydra)** | Sixense | Tuscany with motion-controller hands added | [archive.org](https://archive.org/details/sixense-tuscany-demo) · [RoadToVR](https://www.roadtovr.com/oculus-rift-razer-hydra-tuscany-demo-download-sixense/) | 🟡 | Needs a Razer Hydra. |
| **UE4 Rollercoaster** | community (UE4) | The quintessential "show your friends" coaster ride | [archive.org](https://archive.org/details/ue-4-rollercoaster) | 🟡 | DK2, 0.x runtime. |
| **SPAG Rollercoaster** | SPAG | Another early coaster ride demo | [archive.org](https://archive.org/details/spagrollercoaster) | 🟡 | DK1. |
| **Couch Knights** | Epic Games | Epic's UE4 demo showing off DK2 positional tracking — toy knights on a coffee table | [Rev3 hands-on (video)](https://archive.org/details/Rev3Games_Previews_235) | 🟡 | Original exe hard to find; widely documented. |
| **Welcome to Oculus 2.0** | Oculus VR | The official DK2 intro/onboarding experience (recovered "lost" software) | [archive.org](https://archive.org/details/welcome_to_oculus_2_0) | 🟡 | Good period piece. |

---

## Arcade / exploration / atmospheric tech demos

| Demo | Creator | What it is | Link(s) | Status | Notes |
|---|---|---|---|---|---|
| **SightLine: The Chair** | Tomáš "Frooxius" Mariančík | Gaze-driven reality-shifting demo — a benchmark "wow" experience | [v1.3](https://archive.org/details/SightLineChair13) · [v1.5](https://archive.org/details/SightLineChair15) · [v1.10 OpenVR](https://archive.org/details/SightLineChair110) · [RoadToVR](https://www.roadtovr.com/sightline-the-chair-oculus-rift-dk2-vr-reference-demo/) | 🟡 | v1.10 is OpenVR (works on Vive/modern via SteamVR). |
| **SightLine VR Jam Prototype** | Frooxius | The earlier prototype that started it all | [v1.1.1](https://archive.org/details/SightLineVRJamProto111) · [v1.3](https://archive.org/details/SightLineVRJamProto13) · [Playground 0.1](https://archive.org/details/SightLinePlayground01) | 🟡 | |
| **Proton Pulse** | Justin Moravetz (ZeroTransform) | Head-controlled brick-breaker; a go-to first-timer demo | [KickStarter builds](https://archive.org/details/proton-pulse-kick-starter-win-v-1.1-build) · [Rift demo](https://archive.org/details/proton-pulse-rift-demo) · [RoadToVR](https://www.roadtovr.com/proton-pulse-back-better-ever-oculus-rift-dk2-ready-demo/) | 🟡 | |
| **Cyber Space** | community | Atmospheric explorable cyber environment | [archive.org (0.8 runtime)](https://archive.org/details/cyber-space-0.8-runtime) | 🟡 | DK2, runtime 0.8. |
| **AaaaaAAaaaAAAaa... CULUS!!!** | Dejobaan/Owlchemy | The VR demo of the falling/proximity game | [archive.org](https://archive.org/details/aaaaa-aaaaa-aaaaa-aaaaa-culus) | 🟡 | DK2. |
| **Dreadhalls** | White Door Games | Original 2013 VR Jam horror maze prototype | [Official demo page](https://www.dreadhalls.com/demo) · [Old builds](https://archive.org/details/dreadhalls-old-builds) | ✅/🟡 | Builds for DK1/DK2 across runtimes 0.7/0.8. Full game on Steam. |
| **Elevator Horror** | community | Short jump-scare elevator ride | [archive.org](https://archive.org/details/elevator-horror) | 🟡 | DK2. |
| **Affected: The Horror Experience** | Fallen Planet | Early build of the popular VR horror walk | [archive.org (v1.62)](https://archive.org/details/affected-v-1.62_202604) | 🟡 | DK2. |
| **Cyberphobia** | community | Atmospheric horror demo | [archive.org](https://archive.org/details/cyberphobia-pc) | 🟡 | DK2. |
| **The Apparition Within The Rift** | community | Horror experience | [archive.org](https://archive.org/details/the-apparition-within-the-rift-pc) | 🟡 | DK2. |
| **Mental Torment — Ep. 1 / Ep. 2** | community | Episodic horror | [Ep.1](https://archive.org/details/mtsetup_202604) · [Ep.2 demo](https://archive.org/details/mt-2-demo) | 🟡 | DK2. |
| **Doors of Silence** | community | Atmospheric horror | [archive.org](https://archive.org/details/doors-of-silence-1.11) | 🟡 | |
| **Hollow** | community | Exploration demo w/ Leap Motion hands | [archive.org](https://archive.org/details/hollow_20260524) | 🟡 | DK2 + Leap Motion. |
| **Flying in Dreams** | community | Serene flight experience | [archive.org](https://archive.org/details/flyingindreams) | 🟡 | DK1/DK2. |
| **7 Nanocycles** | community | Sci-fi exploration demo | [archive.org](https://archive.org/details/7-nanocycles-pc) | 🟡 | DK2. |
| **Adventure Time: Magic Man's Head Games** | Cartoon Network | Official licensed DK2 demo | [archive.org](https://archive.org/details/adventure-time-magic-man-s-head-games) | 🟡 | DK2. |
| **HoloFEZ** | 0x0ade | FEZ rendered as a holographic diorama | [archive.org (GitHub mirror)](https://archive.org/details/github.com-0x0ade-HoloFEZ_-_2017-08-21_13-26-37) | 🟡 | |
| **Reset (Greenlight demo)** | community | Atmospheric demo | [archive.org](https://archive.org/details/reset-greenlight-demo) | 🟡 | |
| **Yunalus** | illusion | Stylized experience | [archive.org](https://archive.org/details/yunalus-vr) | 🟡 | |

---

## Still-free modern PC VR experiences (same spirit, any headset)

These run on current hardware via SteamVR — great for the "interesting spaces / show a
friend" vibe without legacy-runtime hassle.

| Experience | Creator | What it is | Link | Status |
|---|---|---|---|---|
| **The Lab** (incl. *Aperture Robot Repair*) | Valve | Portal-universe demo collection; Robot Repair is the legendary tech showcase | [Steam (free)](https://store.steampowered.com/app/450390/The_Lab/) | ⚪ |
| **Google Earth VR** | Google | Fly anywhere on Earth in VR | [Steam (free)](https://store.steampowered.com/app/348250/Earth_VR/) | ⚪ |
| **Accounting** | Crows Crows Crows / Squanch | Comedic surreal VR experience | [Steam (free)](https://store.steampowered.com/app/518580/Accounting/) | ⚪ |
| **theBlu** | Wevr | Underwater encounters (free trial / demo) | [Steam](https://store.steampowered.com/app/451520/theBlu/) | ⚪ |
| **Colosse: A VR Fairytale** | Fire Panda | Animated VR short | [Steam (free)](https://store.steampowered.com/app/541050/Colosse_A_VR_Fairytale/) | ⚪ |
| **Senza Peso** | Kite & Lightning | Operatic cinematic VR (early DK2 standout) | [Official](https://kiteandlightning.la/senza-peso/) | ⚪ |
| **Arch Virtual HQ** | Arch Virtual | Free arch-viz showcase from the Residential Condo makers | [Steam (free)](https://store.steampowered.com/app/608980/Arch_Virtual_HQ/) | ⚪ |

---

## The motherlode: archive.org preservation collection

Internet Archive uploader **`acedrecordsprofessional@gmail.com`** has preserved ~34 DK1/DK2
demos as downloadable software — most entries above with 🟡 links come from here. Browse the
full set:

- **All items:** [archive.org/search?query=uploader:(acedrecordsprofessional@gmail.com)](https://archive.org/search?query=uploader%3A%28acedrecordsprofessional%40gmail.com%29)

Additional preserved DK1 titles in that collection worth a look: *Zelda OoT Kokiri Forest*,
*TerroRift*, *Wraith — Haunted Halls*, *The Visitor*, *Deep Down in Space*, *Deep Down Dark*,
*Dark Dreams Ep.1*, *Alone*, *Dumpy: Going Elephants*, *Maere: When Lights Die*,
*Experiment 427* (Stanley Parable mod), *Spag Rollercoaster*.

Also handy on archive.org:
- **Oculus legacy runtime SDK 0.8.0.0** — [archive.org](https://archive.org/details/oculus_runtime_sdk_0.8.0.0_win_202303) (needed to run most of the above)
- **Oculus DK1 software collection** — [archive.org](https://archive.org/details/dk1softwarecollection)

---

## Where to find more

- **itch.io — free Oculus Rift / DK2-tagged games:** [itch.io/games/free/oculus-rift/tag-dk2](https://itch.io/games/free/oculus-rift/tag-dk2)
- **Steam Curator — Free VR Experiences:** [store.steampowered.com/curator/33078311](https://store.steampowered.com/curator/33078311-Free-VR-Experiences/)
- **RoadToVR — best free VR experiences:** [roadtovr.com](https://www.roadtovr.com/best-free-vr-games-experiences-pc-htc-vive-oculus-rift/)
- **UploadVR — best free VR experiences:** [uploadvr.com](https://www.uploadvr.com/best-free-vr-experiences/)
- **The Rift Arcade — DK2 supported games list** (now offline; try Wayback): `theriftarcade.com/oculus-rift-dk2-supported-games`
- **Oculus/Meta community forums — "DK2 Compatible Demos and Games"** (login-walled now): thread id `192031`

---

## Running these today

DK2-era demos predate the modern OpenXR/OpenVR stack. Typical paths:

1. **Period-correct:** install a **legacy Oculus runtime (0.5–0.8)** on Windows; many demos
   are pinned to a specific runtime version (noted per-entry where known).
2. **On a modern headset:** use **[Revive](https://github.com/LibreVR/Revive)** or
   **[OpenComposite](https://gitlab.com/znixian/OpenOVR)** to translate old Oculus/OpenVR calls
   to your current runtime. Results vary — some demos work great, others not at all.
3. **OpenVR builds** (e.g. SightLine v1.10) generally work directly through SteamVR.
4. **Standalone APKs** (e.g. 4th Floor Studio's Quest build) sideload onto a Quest.

> ⚠️ **Comfort note:** early demos often have imperfect tracking/latency and can be more
> nausea-inducing than modern VR. Start short.

---

## Contributing

Found a demo, a working mirror, or a dead link that needs fixing? Open an issue or PR.
Please include: name, creator, what it is, a link (prefer archive.org/Wayback for old files),
and headset/runtime notes. Links only — we don't host binaries.

*Disclaimer: links point to third-party and archival sources; we don't host or own this
content. Some files are very old and may carry the usual risks of running legacy executables —
use your judgement.*
