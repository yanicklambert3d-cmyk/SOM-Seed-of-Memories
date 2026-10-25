# <img src="assets/SOM_logo.svg" alt="" height="34"> Seed of Memories (SOM)

![Seed of Memories - scenes from the XR experience](assets/som-banner.webp)

Seed of Memories is an XR exploration-based serious game that connects virtual interaction with real-world plant care. Built with Unity 6 URP for Meta Quest 3, it explores embodied interaction and connectedness to nature through a journey inspired by Madeira’s Laurisilva forest and its ecological and cultural heritage.

## <img src="assets/SOMText_logo.svg" alt="" height="28"> The experience

Participants help restore Laura, the last laurel tree, by retrieving Magic Water from the Future and Magic Light from the Past. Underwater exploration, environmental puzzles and gesture-based interactions lead to a final passthrough sequence that connects the virtual quest with caring for a real plant.

Water and sunlight link the two parts of the experience: what participants seek in XR becomes what they provide through plant care.

<details>
<summary><strong><picture><img src="assets/procedure.svg" alt="" height="20"></picture> XR experience sequence</strong> <code>(click to expand)</code></summary>

![XR experience sequence of events](assets/som-experience-sequence.webp)

</details>

## <img src="assets/logo_VR.svg" alt="" height="28"> Interaction and study setup

- **Platform:** Meta Quest 3, running as a standalone application.
- **Development:** Unity 6 with the Universal Render Pipeline (URP).
- **Future scenario:** handheld controllers, teleportation and swimming interactions.
- **Past scenario:** hand tracking and gesture-based teleportation; bHaptics TactGlove supplies feedback in the experimental condition.
- **Final transition:** VR to colour passthrough.

Haptic gloves are optional for playing. To reproduce the study’s haptic condition, use paired and calibrated **bHaptics TactGlove** in the Past scenario.

<details>
<summary><strong><picture><img src="assets/logo_VR.svg" alt="" height="20"></picture> SOM XR apparatus</strong> <code>(click to expand)</code></summary>

![SOM XR apparatus](assets/som-xr-apparatus.webp)

</details>

## <picture><img src="assets/research_icon.svg" alt="" height="28"></picture> Research context

The study investigates embodiment, flow, perceived workload and connectedness to nature. Participants experience both interaction modalities in a fixed narrative sequence, followed by questionnaires and an interview. The XR session lasts approximately 30 minutes.

## <picture><img src="assets/gift%20boxe.svg" alt="" height="28"></picture> From XR to plant care

After completing the XR experience, each participant receives a **Seed of Memories Gift Box** containing a plant pot, soil, seeds, and planting and watering instructions. This begins the plant-care activity at home, supported by a reflective diary and a follow-up assessment over a period of up to two months.

<details>
<summary><strong><picture><img src="assets/gift%20boxe.svg" alt="" height="20"></picture> Seed of Memories Gift Box</strong> <code>(click to expand)</code></summary>

![Seed of Memories Gift Box received after the XR experience](assets/giftBox.webp)

</details>

<details>
<summary><strong><picture><img src="assets/procedure.svg" alt="" height="20"></picture> Procedure - from XR to plant care</strong> <code>(click to expand)</code></summary>

![Study procedure - from XR to plant care](assets/som-study-procedure.webp)

</details>

## <picture><img src="assets/apk_icon.svg" alt="" height="28"></picture> APK access

[**Download SOM for Meta Quest 3**](https://github.com/yanicklambert3d-cmyk/SOM-Seed-of-Memories/releases/download/v1.0/SOM-1.0-research-build-2026-10-25.7z) · [Release v1.0](https://github.com/yanicklambert3d-cmyk/SOM-Seed-of-Memories/releases/tag/v1.0)

The research APK is packaged in a password-protected .7z archive. Contact [lambertyanick@gmail.com](mailto:lambertyanick@gmail.com) to request access.

<details>
<summary><strong><picture><img src="assets/installation_icon.svg" alt="" height="20"></picture> Installation &amp; Usage</strong> <code>(click to expand)</code></summary>

1. Download the SOM archive from [Releases](https://github.com/yanicklambert3d-cmyk/SOM-Seed-of-Memories/releases/tag/v1.0) and request the password at [lambertyanick@gmail.com](mailto:lambertyanick@gmail.com).
2. Extract **SOM 2026.apk** using [7-Zip](https://www.7-zip.org/) and the password provided.
3. Install the APK on your **Meta Quest 3** using [SideQuest](https://sidequestvr.com/), [Meta Quest Developer Hub](https://developers.meta.com/horizon/documentation/unity/ts-mqdh/) or `adb install`.
4. Launch **SOM** from your headset.
5. Follow the in-game tutorial to begin the experience.

</details>

<details>
<summary><strong><picture><img src="assets/build.svg" alt="" height="20"></picture> Build information</strong> <code>(click to expand)</code></summary>

Seed of Memories is a standalone XR experience for Meta Quest 3. This research build supports the interaction conditions described in the study.

### <picture><img src="assets/build.svg" alt="" height="20"></picture> Build details

| Item | Value |
|---|---|
| Application | Seed of Memories (SOM) |
| Platform | Meta Quest 3 - standalone XR |
| Engine | Unity 6 · Universal Render Pipeline |
| APK filename | SOM 2026.apk |
| Package identifier | com.ITI_LogaCulture.SOM_2026_PT_EN |
| Version | 1.0 |
| Version code | 1 |
| Architecture | ARM64 (arm64-v8a) |
| Minimum / target SDK | 32 / 32 |
| APK size | 1,337,011,707 bytes (approximately 1.34 GB) |

### <picture><img src="assets/build.svg" alt="" height="20"></picture> File integrity

Game data is included in the APK. The SHA-256 below identifies this exact build and can be used to verify the extracted file.

```text
0e47fbccdedf985f0c2a2cd64a6783aa8f38053a6d309d08e3a90a354362aa7c
```

</details>

<details>
<summary><strong><picture><img src="assets/study.svg" alt="" height="20"></picture> Study reproduction notes</strong> <code>(click to expand)</code></summary>

This guide describes the hardware, interaction conditions and procedure used in the SOM study.

### <picture><img src="assets/logo_VR.svg" alt="" height="20"></picture> Interaction conditions

| Narrative phase | Interaction condition |
|---|---|
| Future | Handheld controllers, teleportation and swimming interactions |
| Past | Hand tracking, gesture-based teleportation and bHaptics TactGlove feedback |
| End of XR | Colour passthrough and introduction to plant care |

Keep the fixed **Future-then-Past** order used in the study.

The haptic design combines discrete feedback for narrative events with continuous wrist feedback. The wrist-feedback intensity varies between 5% and 30%, modulated at 2 Hz with a 10 Hz update rate.

### <picture><img src="assets/procedure.svg" alt="" height="20"></picture> Procedure

1. Before XR: briefing, informed consent, participant profile, CNS baseline and technical preparation.
2. During XR: approximately 30 minutes, with supervised casting observation. Pause between Future and Past to exchange controllers for haptic gloves.
3. After XR: FSS, VEQ, NASA-TLX and CNS, followed by an interview. The in-lab session totals approximately 45 minutes.
4. Plant care: give each participant a **Seed of Memories Gift Box** containing a plant pot, soil, seeds, and planting and watering instructions. Participants care for the plant at home, maintain a reflective diary for up to two months, and complete follow-up CNS.

### <picture><img src="assets/logo_VR.svg" alt="" height="20"></picture> Equipment and play area

Use a **Meta Quest 3** with controllers and hand tracking. Prepare a clear play area of approximately **3 m²** and set the headset boundary.

</details>

## <picture><img src="assets/issues_icon.svg" alt="" height="28"></picture> Known Issues

- Passthrough may appear dark when the user moves outside the configured play area.
- Frame rate may fluctuate between 45 and 50 FPS in some areas of the experience.

## <picture><img src="assets/roadmap_icon.svg" alt="" height="28"></picture> Roadmap

- [x] Future and Past XR journey inspired by Madeira’s Laurisilva.
- [x] Controller and hand-tracking interaction with haptic feedback.
- [x] Passthrough transition from XR to real-world plant care.
- [x] Gift Box and reflective plant-care diary.
- [x] Plant Growth Platform for diary submission and follow-up questionnaires.
- [ ] Compare embodiment, flow and perceived workload across the two interaction conditions.
- [ ] Follow participants’ plant-care experience for up to two months.
- [ ] Analyse connectedness to nature before XR, after XR and after plant care.

## <picture><img src="assets/link_icon.svg" alt="" height="28"></picture> Related links

- [Plant Growth Platform](https://som.yanicklambert.com/)
- [Author portfolio](https://yanicklambert.com/)

## <picture><img src="assets/contact_icon.svg" alt="" height="28"></picture> Contact

For APK access, questions or feedback, contact [lambertyanick@gmail.com](mailto:lambertyanick@gmail.com).
