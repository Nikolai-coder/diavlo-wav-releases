<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:030303,28:160020,58:4c0070,82:0369a1,100:22d3ee&text=DIAVLO%20WAV&fontColor=ffffff&fontSize=66&fontAlignY=35&desc=AUDIO%20INTELLIGENCE%20FOR%20PRODUCERS&descAlignY=56&descSize=17&animation=fadeIn" alt="DIAVLO WAV" />

<a href="https://github.com/Nikolai-coder/diavlo-wav-releases/releases/latest">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=21&duration=2400&pause=650&color=C084FC&center=true&vCenter=true&repeat=true&width=980&height=58&lines=Download.+Analyse.+Separate.+Create.;From+raw+audio+to+production-ready+assets.;Local-first+processing.+No+cloud+maze.;Built+in+the+Canary+Islands." alt="DIAVLO WAV animated description" />
</a>

<br />

[![Latest Release](https://img.shields.io/github/v/release/Nikolai-coder/diavlo-wav-releases?display_name=tag\&sort=semver\&style=for-the-badge\&logo=github\&logoColor=white\&label=LATEST\&labelColor=09090b\&color=a855f7)](https://github.com/Nikolai-coder/diavlo-wav-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Nikolai-coder/diavlo-wav-releases/total?style=for-the-badge\&logo=windows11\&logoColor=white\&label=DOWNLOADS\&labelColor=09090b\&color=06b6d4)](https://github.com/Nikolai-coder/diavlo-wav-releases/releases)
[![Platform](https://img.shields.io/badge/PLATFORM-WINDOWS%2010%20%7C%2011-0078D6?style=for-the-badge\&logo=windows11\&logoColor=white\&labelColor=09090b)](#system-requirements)
[![Architecture](https://img.shields.io/badge/ARCHITECTURE-x64-18181b?style=for-the-badge\&logo=windows\&logoColor=white\&labelColor=09090b)](#system-requirements)
[![Core](https://img.shields.io/badge/CORE-RUST%20%2B%20TAURI-f97316?style=for-the-badge\&logo=rust\&logoColor=white\&labelColor=09090b)](#technology)
[![Privacy](https://img.shields.io/badge/AUDIO-LOCAL--FIRST-22c55e?style=for-the-badge\&logo=shield\&logoColor=white\&labelColor=09090b)](#privacy-and-security)

<br />

### A local-first Windows workstation for producers, beatmakers, artists and audio engineers.

**Download · Convert · Analyse · Separate · Repair · Transcribe · Master · Export**

[Download latest release](https://github.com/Nikolai-coder/diavlo-wav-releases/releases/latest) ·
[View all releases](https://github.com/Nikolai-coder/diavlo-wav-releases/releases) ·
[Report an issue](https://github.com/Nikolai-coder/diavlo-wav-releases/issues)

</div>

---

## About DIAVLO WAV

**DIAVLO WAV** is a native desktop application built to transform audio and media into production-ready material without interrupting the creative workflow.

It combines media extraction, format conversion, professional audio analysis, stem separation, intelligent mastering, Audio-to-MIDI, reference comparison, session management and production utilities inside one focused application.

DIAVLO WAV does not try to replace your DAW. It works beside it.

Use it to:

* Obtain and convert legally accessible media.
* Inspect the technical and musical characteristics of a track.
* Separate vocals, drums, bass and instrumental material.
* Extract MIDI from melodies or isolated instruments.
* Compare a mix against a reference.
* Prepare vocals and loops.
* Build mastering chains.
* Organize stems, MIDI, metadata and exports.
* Transfer clean assets into FL Studio, Ableton Live or another DAW.

The application follows a **local-first** philosophy: audio processing happens on the user's computer whenever the selected workflow permits it.

---

## Version 1.0

DIAVLO WAV `1.0.0` represents the first complete production workflow of the project.

The release line introduces or consolidates:

* Persistent DIAVLO Sessions.
* Native audio analysis in Rust.
* Local Demucs stem separation.
* Intelligent mastering with A/B comparison.
* Audio-to-MIDI workflows.
* Spotify Smart Resolver through OAuth PKCE.
* Model Manager with SHA-256 verification.
* Producer tools such as Beat Autopsy, DIAVLO DNA and Vocal Forge.
* Organized export packages.
* Signed automatic-update artifacts.
* Release verification gates for frontend, Rust, sidecars and updater metadata.

> [!IMPORTANT]
> A compiled build is not considered a stable release until its installer, updater, upgrade path and release artifacts pass the complete release verification gate.

---

## Main Workspaces

### Home

The starting point for recent projects, quick actions and application status.

Home can provide access to:

* Recent DIAVLO Sessions.
* Recent audio files.
* Active and completed processing jobs.
* Model installation status.
* Update availability.
* Quick access to analysis, stems, mastering and downloads.

---

### Download

Obtain media from supported public sources through the packaged extraction backend.

Available workflows can include:

* Individual URLs.
* Playlist-compatible workflows.
* Audio-only extraction.
* Video downloads.
* Output-folder selection.
* Format and quality selection.
* Real-time progress.
* Cancellation and error reporting.
* Safe filename handling.
* Unicode-compatible paths.
* Automatic conversion after extraction.

The extraction engine is packaged as a controlled sidecar. DIAVLO WAV does not depend on a random global installation found on the computer.

> [!NOTE]
> Platform compatibility may change when an external service modifies its website, API or access rules.

---

### Convert

Convert local files into formats suitable for production, delivery or archiving.

Supported workflows may include:

* Audio extraction from video.
* WAV conversion.
* FLAC conversion.
* MP3 conversion.
* MP4 processing.
* Sample-rate conversion.
* Channel conversion.
* Bit-depth selection.
* Batch processing.
* Output normalization.
* Safe overwrite protection.

FFmpeg operations are executed through the packaged application backend.

---

### Analyse

Inspect the musical and technical behavior of an audio file before making production decisions.

Analysis can include:

* BPM detection.
* BPM confidence.
* Half-time and double-time candidates.
* Key and scale detection.
* Tonal confidence.
* Camelot notation.
* Integrated loudness.
* Short-term loudness.
* Momentary loudness.
* True peak.
* RMS.
* Crest factor.
* Dynamic-range indicators.
* Clipping detection.
* DC-offset detection.
* Spectral balance.
* Five-band energy analysis.
* Stereo width.
* Phase correlation.
* Silence and transient detection.
* Energy changes over time.
* Structural estimation.
* Actionable production recommendations.

The native FFT pipeline uses windowed spectral analysis to provide measurable information instead of generic descriptions.

---

### Stems

Separate audio locally using installed Demucs-compatible models.

Typical stem configurations include:

* Vocals.
* Drums.
* Bass.
* Other or instrumental material.

Depending on the selected model, additional configurations may be available.

The stems workspace includes:

* Local model execution.
* Progress tracking.
* Cancellation.
* Error reporting.
* Temporary-file cleanup.
* Multistem playback.
* Synchronized stem preview.
* Solo and mute controls.
* Individual stem export.
* Grouped export.

Long songs and CPU-only systems may require significantly more processing time.

---

### Master

Create and preview a mastering chain based on the measurable properties of the source audio.

The mastering workflow can include:

* Corrective EQ.
* Dynamic processing.
* Compression.
* Multiband control when required.
* Saturation.
* Stereo control.
* Limiting.
* True-peak protection.
* Output loudness targeting.
* Adjustable processing intensity.
* Stage bypass.
* Preset workflows.
* Loudness-matched A/B comparison.
* Export without overwriting the original file.
* Persistent mastering history.

Mastering is non-destructive. The source file remains untouched unless the user explicitly exports a new result.

---

## DIAVLO Sessions

Create, open, save, duplicate and recover complete DIAVLO WAV projects.

A session can preserve:

* Imported audio references.
* Analysis results.
* Generated stems.
* Reference tracks.
* Audio-to-MIDI results.
* Mastering settings.
* Processing history.
* Export history.
* Active tool.
* Interface state.
* Last saved timestamp.

The session system is designed around:

* Versioned project formats.
* Atomic saves.
* Autosave.
* Recovery after an unexpected shutdown.
* Migration support.
* Missing-file detection.
* File relocation.
* Safe path handling.

Original media is not embedded or modified unless the chosen export workflow explicitly creates a new file.

---

## Producer Tools

### Stem Surgeon

Edit separated audio without modifying the original recording.

Available tools can include:

* Region selection.
* Splitting and trimming.
* Gain adjustment.
* Mute.
* Fades and crossfades.
* Normalization.
* Click repair.
* Basic noise cleanup.
* Region replacement.
* Undo and redo.
* Individual or grouped export.

---

### Reference Ghost

Compare a production against a real reference track.

Reference Ghost can inspect measurable differences in:

* Loudness.
* True peak.
* Dynamics.
* Frequency balance.
* Low-end energy.
* Brightness.
* Stereo width.
* Correlation.
* Tonality.
* Transients.
* Energy.
* Structure.

Recommendations are generated from detected differences. Changes are never applied automatically without an explicit user action.

---

### Audio-to-MIDI

Convert musical audio into Standard MIDI Files.

#### Fast extraction

Designed for clearer monophonic material such as:

* Melodies.
* Bass lines.
* Lead instruments.
* Simple vocal lines.

#### Polyphonic AI extraction

A local Basic Pitch workflow can detect overlapping notes and chords from suitable isolated material.

Generated MIDI can include:

* Note pitch.
* Note start and end.
* Velocity estimation.
* Tempo information.
* Standard MIDI File export.

Current limitations:

* Dense full mixes can reduce accuracy.
* Strong harmonics may be interpreted as extra notes.
* Pitch bends, vibrato and glissando curves are not fully preserved.
* Final MIDI cleanup inside a DAW may still be necessary.

---

### Beat Autopsy

Analyse how a beat changes through time.

Beat Autopsy can detect or estimate:

* Intro.
* Verse.
* Chorus.
* Bridge.
* Outro.
* Drops.
* Transitions.
* Fills.
* Silences.
* Energy changes.
* Density changes.
* Drum variation.
* Bass variation.
* Melodic variation.
* Contrast between sections.

Results include timestamps and confidence indicators.

---

### Vocal Forge

Prepare vocal recordings while preserving the original audio.

Processing can include:

* Noise detection.
* Breath management.
* De-essing.
* Plosive control.
* Resonance reduction.
* Corrective EQ.
* Gate.
* Leveling.
* Compression.
* Saturation.
* Limiting.
* A/B preview.

---

### Loop Alchemist

Transform loops into new production-ready variations.

Tools can include:

* BPM detection.
* Key detection.
* Time-stretching.
* Pitch-preserving tempo changes.
* Transposition.
* Reverse.
* Half-time.
* Double-time.
* Chopping.
* Slicing.
* Region rearrangement.
* Fades.
* Batch variation export.

---

### Local Sample Finder

Index selected folders and search a sample library without uploading it.

Search and filtering can use:

* Filename.
* Folder.
* Duration.
* Sample rate.
* Channel count.
* BPM.
* Key.
* Estimated sound type.
* Spectral characteristics.
* Audio similarity.

The local index supports:

* Incremental updates.
* Moved-file detection.
* Duplicate protection.
* Persistent metadata.
* User-controlled deletion.

---

### DIAVLO DNA

Build a measurable production profile from the user's own music.

DIAVLO DNA can summarize:

* Common BPM ranges.
* Frequent keys and modes.
* Loudness tendencies.
* Dynamic behavior.
* Spectral balance.
* Stereo characteristics.
* Energy and density.
* Structural tendencies.

Every profile includes its dataset size, confidence and update date.

The profile can be recalculated or deleted by the user.

---

### FL Studio Bridge

Prepare a clean exchange package for FL Studio or another compatible DAW.

A bridge package can include:

* Properly named stems.
* MIDI files.
* BPM information.
* Key information.
* Markers.
* Technical manifest.
* Export notes.
* Shortcut to the output folder.

DIAVLO WAV does not claim to remotely control FL Studio. The bridge focuses on reliable file exchange and project preparation.

---

### Export Center

Create individual exports or complete delivery packages.

Supported outputs can include:

* WAV 16-bit.
* WAV 24-bit.
* FLAC.
* MP3.
* MIDI.
* Individual stems.
* Grouped stems.
* ZIP packages.
* Technical manifests.
* Export notes.

Available delivery workflows can include:

* Streaming master.
* Beat-store preview.
* Trackouts.
* Mixing delivery.
* Distribution package.
* Social-media export.
* Artist delivery.

The Export Center handles:

* Unicode filenames.
* Duplicate names.
* Temporary files.
* Conversion errors.
* Overwrite protection.
* Organized folder structures.

---

### Visual Lab

Associate audio with visual material and prepare assets for visualizers.

Supported workflow:

```text
BEAT → VISUAL → PREVIEW → EXPORT
```

Visual Lab can work with:

* Imported images.
* Imported video.
* Audio previews.
* Exported visualizer assets.
* Safe import and export workflows for external design tools.

External services are not embedded when no stable or secure integration exists.

---

## Spotify Smart Resolver

DIAVLO WAV can interpret Spotify links through the official Spotify API using OAuth PKCE.

The resolver can:

* Parse Spotify URLs.
* Read authorized metadata.
* Identify artist, title, album and duration.
* Normalize search information.
* Score possible equivalent sources.
* Refresh OAuth sessions securely.
* Pass resolved metadata into supported workflows.

> [!IMPORTANT]
> Spotify Smart Resolver does not extract or decrypt Spotify audio streams. It uses authorized metadata to locate equivalent accessible sources when permitted.

A Spotify account login may be required for real metadata resolution.

---

## Model Manager

Optional AI and separation models are managed from inside the application.

Model Manager provides:

* Installation status.
* Download progress.
* SHA-256 checksum verification.
* Corruption detection.
* Reinstallation.
* Removal.
* Duplicate-download protection.
* Atomic installation.
* Cache invalidation.
* Backend and device information.
* Model license information.

Models and downloaded executables are not used before their integrity validation succeeds.

No optional model should be downloaded silently.

---

## Background Processing

Long-running operations are handled as controlled jobs.

The job system is designed to provide:

* Progress reporting.
* Current processing stage.
* Cancellation.
* Recoverable errors.
* Timeout handling.
* Temporary-file cleanup.
* Prevention of duplicate jobs.
* User-visible failure messages.
* Protection against frozen interface states.

Actual performance depends on the selected workflow, hardware and audio duration.

---

## Supported Formats

### Common import formats

Format availability depends on the decoding backend packaged with the build.

Commonly supported formats include:

* WAV.
* FLAC.
* MP3.
* AIFF.
* M4A.
* OGG.
* MP4.
* Other FFmpeg-compatible media formats.

### Export formats

* WAV 16-bit.
* WAV 24-bit.
* FLAC.
* MP3.
* MIDI.
* MP4 where supported.
* ZIP delivery packages.

---

## Privacy and Security

DIAVLO WAV is designed around local processing.

By default:

* Audio is processed locally.
* Samples are not uploaded.
* Local audio paths are not sent to external services.
* Filenames are not added to hidden telemetry.
* Models are integrity-checked before execution.
* Original files are preserved.
* Processing output is written to user-selected or application-controlled locations.
* Automatic updates require a valid updater signature.

Online access is limited to documented operations such as:

* Software update checks.
* Official release downloads.
* Optional model downloads.
* Spotify OAuth and metadata requests.
* User-requested media extraction.

Updater signatures and Windows Authenticode are different systems. A release can have a valid Tauri updater signature while Windows still displays an unknown-publisher warning when the installer has no Authenticode certificate.

---

## Automatic Updates

DIAVLO WAV checks the configured stable release channel for signed updates.

The updater workflow is designed to:

1. Detect a compatible version.
2. Download the correct Windows artifact.
3. Verify the updater signature.
4. Reject invalid or modified packages.
5. Install the update.
6. Restart the application when required.
7. Preserve supported sessions and user data.

A failed update must not silently replace the current working installation.

### Update policy

* Versions at or above the configured minimum-safe version receive normal optional updates.
* Versions below the minimum-safe version may receive a mandatory update gate.
* The current minimum-safe policy is based on version `0.4.0`.
* A release is not published when the release verification gate fails.

---

## Installation

### Traditional Windows installation

1. Open the [latest release](https://github.com/Nikolai-coder/diavlo-wav-releases/releases/latest).
2. Download the Windows x64 installer.
3. Run the installer.
4. Open DIAVLO WAV.
5. Install optional models from **Model Manager** when required.

Only install builds obtained from the official release repository.

### PowerShell installation

When the official release includes `install.ps1`, installation can be started with:

```powershell
irm "https://github.com/Nikolai-coder/diavlo-wav-releases/releases/latest/download/install.ps1" | iex
```

To inspect the script before execution:

```powershell
$script = "$env:TEMP\diavlo-wav-install.ps1"

irm "https://github.com/Nikolai-coder/diavlo-wav-releases/releases/latest/download/install.ps1" `
  -OutFile $script

notepad $script
& $script
```

---

## Quick Start

1. Create a **DIAVLO Session**.
2. Import an audio file or use a supported download workflow.
3. Run **Analyse**.
4. Choose the required production workflow:

   * Separate stems.
   * Compare a reference.
   * Extract MIDI.
   * Process vocals.
   * Transform a loop.
   * Master the track.
5. Preview the result.
6. Export through **Export Center**.
7. Save the session.

---

## System Requirements

### Windows release

* Windows 10 or Windows 11.
* 64-bit x86 processor.
* WebView2 Runtime.
* 8 GB RAM minimum.
* 16 GB RAM recommended.
* Free storage for temporary processing and optional models.
* Internet connection for updates, model downloads and online workflows.
* Dedicated GPU not required for standard local workflows.

### Recommended for heavier processing

* Modern multi-core processor.
* 16 GB RAM or more.
* SSD storage.
* AVX2-capable CPU.
* Compatible GPU or DirectML backend where supported.

Demucs and AI transcription can run on CPU, but processing will take longer.

### Other platforms

Windows x64 is the primary supported desktop platform.

Android builds may exist for development or experimental workflows, but feature availability differs from desktop because native sidecars and audio pipelines are not identical.

macOS, Linux and iOS are not currently presented as verified stable release targets.

---

## Technology

<div align="center">

![Tauri](https://img.shields.io/badge/TAURI-DESKTOP%20SHELL-24C8DB?style=for-the-badge\&logo=tauri\&logoColor=white)
![Rust](https://img.shields.io/badge/RUST-NATIVE%20CORE-000000?style=for-the-badge\&logo=rust\&logoColor=white)
![React](https://img.shields.io/badge/REACT-INTERFACE-0D1117?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TYPESCRIPT-APPLICATION%20LOGIC-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![Vite](https://img.shields.io/badge/VITE-FRONTEND-646CFF?style=for-the-badge\&logo=vite\&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFMPEG-MEDIA%20ENGINE-007808?style=for-the-badge\&logo=ffmpeg\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GITHUB%20ACTIONS-RELEASE%20PIPELINE-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)

</div>

```text
DIAVLO WAV
├── Desktop shell ............. Tauri 2
├── Native core ............... Rust
├── Interface .................. React + TypeScript
├── Frontend build ............. Vite
├── Audio decoding ............. Native Rust + FFmpeg
├── Spectral analysis .......... Windowed FFT
├── Loudness analysis .......... ITU-R BS.1770-compatible workflow
├── Stem separation ............ Demucs local sidecars
├── Audio-to-MIDI .............. Native SMF + optional Basic Pitch
├── Media extraction ........... Controlled extraction sidecar
├── Model management ........... SHA-256 verified downloads
├── Updater .................... Signed Tauri update workflow
└── Distribution ............... GitHub Releases
```

---

## Project Structure

```text
DIAVLO-WAV/
├── src/                         # React and TypeScript frontend
├── src-tauri/
│   ├── src/                     # Rust backend and Tauri commands
│   ├── binaries/                # Packaged sidecars
│   ├── capabilities/            # Tauri permissions and capabilities
│   ├── Cargo.toml
│   └── tauri.conf.json
├── tests/                       # Frontend and integration tests
├── scripts/                     # Build, fixture and release tools
├── docs/                        # Audits and technical documentation
├── public/                      # Static assets
├── release/                     # Local release-candidate outputs
├── package.json
└── README.md
```

Generated build folders, private signing keys, real user data, downloaded models and release binaries must not be committed unless the repository policy explicitly allows them.

---

## Development

### Prerequisites

* Node.js compatible with the committed lockfile.
* Rust stable toolchain.
* Cargo.
* Microsoft C++ Build Tools.
* Windows SDK.
* WebView2.
* Project-specific sidecars and test fixtures.

### Install dependencies

```bash
npm install
```

### Run in development

```bash
npm run tauri dev
```

### Frontend verification

```bash
npx tsc --noEmit
npm run lint
npm test
```

### Rust verification

```bash
cd src-tauri
cargo fmt --check
cargo check
cargo clippy -- -D warnings
cargo test
```

### Production build

```bash
npm run tauri build
```

A successful compiler exit is not enough to declare a release ready.

---

## Release Quality Gate

A stable release must pass the complete verification pipeline.

Expected checks include:

* TypeScript compilation.
* ESLint.
* Frontend tests.
* Rust formatting.
* Cargo check.
* Clippy with warnings denied.
* Rust tests.
* Fixture validation.
* Unicode and long-path fixtures.
* Sidecar presence.
* Sidecar architecture.
* Sidecar integrity.
* Frontend production build.
* Tauri production build.
* Release smoke tests.
* Installer presence.
* Portable artifact presence.
* Artifact SHA-256 generation.
* Updater signature verification.
* `latest.json` validation.
* Version consistency.
* Upgrade testing from a supported previous version.
* Installation and uninstallation verification where required.

The release process is fail-closed: when a critical step fails, publishing must stop.

---

## Capability Status

| Capability                      | Current classification            |
| ------------------------------- | --------------------------------- |
| Native audio decoding           | Implemented                       |
| BPM, key and tonal analysis     | Implemented                       |
| Loudness and technical metering | Implemented                       |
| Windowed FFT spectral analysis  | Implemented                       |
| Media extraction and conversion | Implemented                       |
| DIAVLO Sessions                 | Implemented                       |
| Standard MIDI export            | Implemented                       |
| Spotify Smart Resolver          | Implemented; requires OAuth       |
| Demucs stem separation          | Functional; model-dependent       |
| Intelligent mastering           | Functional                        |
| Audio-to-MIDI monophonic mode   | Functional                        |
| Basic Pitch polyphonic mode     | Functional; model-dependent       |
| Stem Surgeon                    | Functional                        |
| Beat Autopsy                    | Functional                        |
| Vocal Forge                     | Functional                        |
| Loop Alchemist                  | Functional                        |
| Local Sample Finder             | Functional                        |
| DIAVLO DNA                      | Functional                        |
| FL Studio Bridge                | Functional file-exchange workflow |
| Model Manager                   | Functional; optional models       |
| Export Center                   | Implemented                       |
| Visual Lab                      | Import/export workflow            |
| Android                         | Experimental                      |
| macOS, Linux and iOS            | Not verified as stable targets    |

Feature status should always be determined by the current implementation audit and release tests, not merely by the presence of interface code.

---

## Known Limitations

* Polyphonic Audio-to-MIDI does not fully preserve pitch bends or vibrato curves.
* Polyphonic transcription performs best with isolated instruments.
* Strong harmonics may be detected as additional MIDI notes.
* Demucs processing time depends heavily on song duration and hardware.
* CPU-only stem separation can be slow.
* Optional models require an initial download.
* Spotify metadata resolution requires interactive OAuth authentication.
* External platforms can change their access rules without notice.
* The FL Studio Bridge prepares files but does not remotely control FL Studio.
* Visual Lab may rely on import and export instead of direct third-party integration.
* Windows may show an unknown-publisher warning when a build is not Authenticode-signed.
* Experimental mobile builds do not provide every desktop feature.
* A portable executable may still require packaged or adjacent sidecars for specific workflows.

---

## Troubleshooting

### A model appears as corrupt

Remove the model from Model Manager and install it again. DIAVLO WAV validates downloaded models before allowing their execution.

### FFmpeg or a conversion operation fails

Confirm that the official application build contains the expected sidecar. Avoid mixing the packaged engine with an unrelated global FFmpeg installation.

### Stem separation does not start

Check that:

* The required model is installed.
* The model checksum is valid.
* Sufficient free storage is available.
* The input path is accessible.
* No previous separation job is still active.

### Spotify resolution is unavailable

Sign in through the authorized Spotify OAuth flow and confirm that the configured Spotify application is active.

DIAVLO WAV cannot bypass Spotify authentication or DRM.

### A session references a moved file

Use the locate or replace action to reconnect the file. The session should not need to be recreated unless recovery fails.

### Processing appears frozen

Review the active job status. Cancel the operation and retry. Controlled failures should clean temporary outputs without modifying the source file.

### The updater cannot install a release

Check:

* Internet connection.
* Available disk space.
* File permissions.
* Update signature.
* Correct platform artifact.
* Version metadata.

The installed working version should remain available after a failed update.

---

## Responsible Use

Use DIAVLO WAV only with:

* Content you created.
* Content you own.
* Public-domain material.
* Content you are legally authorized to download, convert or process.
* Media made available under a compatible license.

DIAVLO WAV is not affiliated with Spotify, YouTube, SoundCloud, TikTok, X, Reddit, Apple, Tidal or other third-party services.

Product names and trademarks belong to their respective owners.

The application is not intended to:

* Circumvent DRM.
* Bypass subscriptions.
* Break platform access controls.
* Obtain protected media without authorization.
* Remove copyright protection.
* Conceal the origin of copyrighted material.

The user is responsible for complying with applicable laws and platform terms.

---

## Security Reporting

Do not disclose a security vulnerability through a public issue containing sensitive information.

A useful private report should include:

* Affected version.
* Reproduction steps.
* Expected behavior.
* Actual behavior.
* Potential impact.
* Relevant sanitized logs.
* Suggested mitigation when known.

Never include:

* Private audio.
* Signing keys.
* Passwords.
* OAuth tokens.
* Personal paths.
* Private model files.
* User databases.

---

## Contributing

Before submitting a contribution:

1. Preserve the existing visual language.
2. Avoid destructive repository operations.
3. Add tests for new behavior.
4. Run frontend and Rust verification.
5. Do not introduce hidden network activity.
6. Do not commit credentials or signing keys.
7. Do not commit private models or real user files.
8. Document limitations honestly.
9. Preserve supported session formats.
10. Keep original audio non-destructive by default.

A visual placeholder must not be classified as a completed functional module.

---

## License

See the [`LICENSE`](LICENSE) file included with the repository.

Third-party libraries, sidecars and models retain their respective licenses.

Required notices, authorship and model-source information must remain available in the project documentation and release packages.

---

## Credits

Built from the Canary Islands for producers who want deeper control without leaving the creative zone.

DIAVLO WAV uses open-source technologies and optional third-party audio models. Respect to every developer, researcher and creator whose work makes independent tools like this possible.

---

<div align="center">

## DIAVLO WAV

### NO SMOKE. NO FAKE PROGRESS. JUST SIGNAL TURNED INTO ACTION.

[![Download Latest](https://img.shields.io/badge/DOWNLOAD-LATEST%20RELEASE-A855F7?style=for-the-badge\&logo=github\&logoColor=white\&labelColor=09090B)](https://github.com/Nikolai-coder/diavlo-wav-releases/releases/latest)
[![Report Issue](https://img.shields.io/badge/REPORT-AN%20ISSUE-ef4444?style=for-the-badge\&logo=github\&logoColor=white\&labelColor=09090B)](https://github.com/Nikolai-coder/diavlo-wav-releases/issues)
[![Star Project](https://img.shields.io/badge/STAR-THE%20PROJECT-facc15?style=for-the-badge\&logo=github\&logoColor=09090b\&labelColor=09090B)](https://github.com/Nikolai-coder/diavlo-wav-releases)

<br />

**Built in the Canary Islands. Ready for the next signal.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:050505,45:4c0070,100:00d4ff&animation=fadeIn" alt="DIAVLO WAV footer" />

</div>
