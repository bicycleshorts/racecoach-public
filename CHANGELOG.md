# Changelog

All notable releases of RaceCoach are documented here.

Format: `[version] – date` with a brief summary of user-facing changes.

---

## [Unreleased]

---

## [1.9.0] – 2026-10-05

RaceCoach 1.9 adds premium telemetry video exports for sharing and reviewing complete laps.

• Export one lap or a two-lap comparison as a finished MP4 on Android and iOS.
• Add synchronized speed, lap timing, track position, racing lines and speed traces directly to exported videos.
• Choose landscape or portrait layouts, clean or analysis presentation, full-video or crop framing and the telemetry elements to include.
• Follow the current section of the circuit in map and speed-trace views, with fixed or dynamic speed scaling for consistent comparison or greater local detail.
• Preview export layouts and telemetry choices before rendering the video.
• Compare laps from the same session or different sessions with consistent lap colours, timing and video synchronization.
• Improved source validation, export progress, error messages and native video rendering reliability across Android and iOS.

RaceCoach telemetry video export is available as a RaceCoach Pro feature.

---

## [1.8.2] – 2026-09-19

RaceCoach 1.8.2 makes GoPro import problems easier to understand and resolve.

• Clearer import messages explain whether GPS is missing, a signal was unavailable or a recording is unsuitable for lap analysis.
• Videos containing unreadable GPS data are now identified correctly instead of being reported as having no GPS.
• More detailed, privacy-safe diagnostics help us investigate camera compatibility issues without collecting local file paths.

---

## [1.8.1] – 2026-09-03

RaceCoach 1.8.1 adds reliable GPS telemetry import for GoPro HERO13 recordings.

• Import GoPro HERO13 recordings and use their embedded GPS data for lap and sector analysis.
• Keep video playback accurately aligned with location and speed data.
• Import supported GoPro recordings more reliably across both earlier and current camera models.

---

## [1.8.0] – 2026-08-25

RaceCoach 1.8 adds GoPro multi-chapter recording support for RaceCoach Pro.

• Find and combine related GoPro video chapters into one continuous session.
• Play laps and sectors across chapter boundaries without losing video or timing data.
• Compare laps and build best-lap playback when sectors span different video files.
• Improved sector alignment, chart cursor stability and video import error handling.

Standard single-video import remains available without a Pro subscription.

---

## [1.7.2] – 2026-08-24

RaceCoach 1.7.2 makes longer GoPro recordings easier to import and analyse.

• RaceCoach Pro can find related GoPro video chapters, let you review the clips and combine their telemetry into one session.
• Keep laps that cross between GoPro files available for lap timing, sector analysis and video comparison.
• Store chapter-aware video references so saved multi-file sessions can reconnect each original clip.
• Continue importing an individual video normally when no related GoPro chapters are available or required.
• Improved video-chart stability when navigating rapidly between laps and clips.

GoPro chapter combining remains a RaceCoach Pro feature. The standard video import remains available without a Pro subscription.

---

## [1.7.1] – 2026-08-20

RaceCoach 1.7.1 makes Pro subscription management clearer and improves usability on modern Android phones.

• Manage RaceCoach Pro from a simpler screen with one clear purchase-access check and troubleshooting details available only when needed.
• Keep subscription access accurate as purchases are restored, subscriptions expire or payments are declined, while retaining valid access during temporary store outages.
• Stay compatible with current Google Play purchase requirements for reliable subscriptions and future Android releases.
• Enjoy improved edge-to-edge presentation with clearer system-bar icons in light and dark mode.
• Select navigation, map and Overview controls more easily, including on curved-screen Android devices.

---

## [1.7.0] – 2026-08-13

RaceCoach 1.7.0 makes setup clearer and gives you a more capable, reliable Overview workspace.

• Get started faster with a new video-led onboarding experience.
• Replay laps across the map and speed chart with synchronized play and pause controls.
• Explore every session with Satellite, Map and data-free Track views.
• Set up tracks more easily with streamlined start/finish and sector editing.
• Import new videos confidently with automatic nearby-track matching and a clean setup when no saved track matches.

This release also improves map reliability, light and dark mode presentation, and general usability.

---

## [1.6.1] – 2026-07-31

RaceCoach 1.6.1 makes landscape analysis clearer and keeps the included Vic example ready whenever you need it.

• Overview now uses landscape space more effectively, with a side-by-side map and speed chart on phones and improved map/chart proportions on tablets.
• Video playback and lap comparison remain usable in short landscape windows, with bounded video panes and controls that stay accessible.
• Navigation, chart labels and sector controls are larger and easier to read on tablets in both landscape and portrait.
• Sector analysis uses a two-column tablet workspace so lap comparisons and time gained or lost can be reviewed together.
• The included Vic example is now saved reliably, so it remains available after you import or open other sessions.
• Free drivers can reopen the Vic example from the Session Library preview, while RaceCoach Pro drivers continue to manage it alongside their own saved sessions.

Phone portrait layouts and text sizing remain unchanged.

---

## [1.6.0] – 2026-07-28

RaceCoach 1.6.0 makes it easier to back up, move and restore your saved driving sessions.

• Export an individual session or your complete Session Library to a RaceCoach backup file.
• Import one or many sessions with a clear review step, duplicate protection and the option to reconnect each original video.
• Reconnect a missing video later from the Session Library without importing the session again.
• Improved video matching on Android and iOS, including reliable filenames when selecting videos from iOS Photos.
• Start exploring immediately on a fresh install with a built-in example session based on Vic telemetry.
• Enjoy a cleaner Session Library with compact management actions, clearer Save controls and more room for your sessions.
• Speed and sector charts now follow your light, dark or system appearance setting.
• Kept important actions clear of Android and iOS system navigation controls.

Session backup files include telemetry, laps, track details and session notes, but not the large video files themselves. RaceCoach will help you reconnect those videos during import or later from the Session Library.

---

## [1.5.4] – 2026-07-17

RaceCoach 1.5.4 resolves App Store review feedback for subscriptions, tracking consent and empty tab states.

• Added clearer subscription period and price-per-month details to the RaceCoach Pro paywall.
• Clarified the iOS analytics consent flow before Apple App Tracking Transparency permission is requested.
• Fixed empty session states so tabs consistently guide users to import a GoPro video from Overview.
• Fixed the AI tab in standard release builds so it remains visible and shows the RaceCoach Pro coming-soon message.

---

## [1.5.3] – 2026-07-15

RaceCoach 1.5.3 improves App Store readiness and privacy transparency.

• Added Apple tracking permission handling for iOS attribution when analytics sharing is enabled.
• Added Privacy Policy and Terms of Use links to the subscription screen.
• Updated consent wording and privacy documentation so analytics, attribution and AI coaching data use are clearer.

---

## [1.5.2] – 2026-07-08

RaceCoach 1.5.2 improves AI evidence handoff and cross-session comparison review.

• AI coaching evidence now opens the existing side-by-side video comparison with focused sector and lap selection.
• Cross-session comparison colours and labels are consistent across map, speed charts, sectors and video review.
• Fixed session ultimate sector comparison so each session uses its own fastest sector sources.
• Improved speed chart zoom, reset and scrub behaviour, including zoom-aware cursor dragging.
• Added a future plan for AI-assisted cross-session coaching using locally summarised historical context.

---

## [1.5.1] – 2026-07-05

RaceCoach 1.5.1 improves the hosted AI coaching beta and prepares the build for wider testing.

• Improved Ask RaceCoach follow-up handling so repeated questions can move through remaining opportunities instead of looping on the same sector.
• Added contextual evidence actions for AI answers, including links into sector comparison and video review where available.
• Hardened the hosted AI backend deployment with deterministic Cloud Run packaging and safer build-context ignores.
• Kept provider API keys server-side while preserving beta build configuration for RaceCoach Pro testing.

---

## [1.5.0] – 2026-07-02

RaceCoach 1.5.0 adds the first hosted AI coaching beta for RaceCoach Pro testing builds.

• Added Ask RaceCoach for session-focused questions using derived sector and opportunity data.
• Added hosted AI coaching through the RaceCoach backend so provider API keys are no longer packaged in the app.
• Improved Coach and AI beta flows around priority sectors, next-lap focus and kid-friendly explanations.
• Added beta build configuration for Android, iOS and VS Code testing against the hosted AI service.

---

## [1.4.0] – 2026-06-29

RaceCoach 1.4.0 adds cross-session video comparison.

• Compare laps from different saved sessions side by side with video, speed and sector timing in sync.
• Review runs from different days, setups or conditions without re-importing the current video each time.
• Android videos and iOS videos imported from Files can be reopened for saved-session comparison.
• iOS Photos videos can still be reopened for normal saved-session playback after permission is granted.
• iOS limitation: Photos videos are not yet supported in cross-session video comparison. On iPhone, save videos to Files and import them from Files when you want to compare videos from saved sessions.

---

## [1.3.3] – 2026-06-27

RaceCoach 1.3.3 improves iOS video import and saved-session playback.

• Added iOS Photos restore for saved sessions so Photos-backed videos can be reopened after relaunch.
• Simplified iOS video import to one Import Video action with Photos and Files choices.
• Kept Files-backed iOS videos on the durable no-copy bookmark path for large source files.
• Prevented cross-session comparison from silently creating multiple full-size temporary Photos video exports.
• Improved cleanup of temporary iOS Photos video files.

---

## [1.3.2] – 2026-06-19

RaceCoach 1.3.2 improves reference data management.

• Fixed an issue where default conditions such as Dry, Damp, Wet and Cold could duplicate after saving sessions.
• Existing duplicate default conditions are cleaned up automatically.
• Fixed a crash that could occur when renaming tracks from Manage Data.
• Improved video import feedback when a selected file has no GoPro GPS data.

---

## [1.3.1] – 2026-06-10

RaceCoach 1.3.1 improves RaceCoach Pro subscription handling.

• Premium access now follows active store entitlements on Android and iOS.
• Improved Pro upgrade and AI Coach gating behavior.
• Cleared legacy test entitlement state so store purchases and restores behave consistently.

---

## [1.3.0] – 2026-06-08

RaceCoach 1.3.0 adds cross-session comparisons and better GoPro timing.

• Compare selected laps from multiple saved sessions in the existing analysis tabs.
• Build Session Ultimate comparisons from each session's fastest sectors.
• Clearer comparison labels and a collapsible comparison banner.
• Fixed GoPro GPS5 timing for 10Hz/18Hz streams and improved start/finish diagnostics.

---

## [1.2.1] – 2026-06-06

RaceCoach 1.2.1 improves iOS video importing and prepares the app for richer cross-session analysis.

• Improved iOS GoPro video import: videos from Photos now work directly from the main Import GoPro Video button, with Files kept as a secondary option.
• Added driver, vehicle, setup and condition details for saved sessions to support more meaningful analysis.
• Prepared the foundation for upcoming cross-session data comparisons.
• Improved iOS video storage handling, cleanup and saved-session source tracking to reduce stale temporary files and missing-video issues.

---

## [1.2.0] – 2026-06-02

RaceCoach 1.2.0 improves lap analysis, track setup and playback.

• Autogenerate a best-lap video from your fastest sectors
• Clearer Start/Finish Line setup and guidance
• More reliable lap/sector detection and track matching
• Better charts in light and dark mode, with clearer lap colours
• Smoother generated playback with active-lap highlighting
• Improved saved session/track handling and recalculation
• Better subscription/status handling
• General stability, reliability and build fixes

## [1.1.3] – 2026-06-01

New in RaceCoach 1.1.3

Build your best possible lap.

RaceCoach can now autogenerate a best-lap video using your fastest sectors, giving you a clearer way to see what your ideal lap could look like.

Also included:
• Smoother generated playback across fastest sectors
• Clearer Start/Finish Line setup guidance
• Improved chart readability in light and dark mode
• Better lap comparison colours and active-lap highlighting
• Refined sector markers on speed charts
• Stability and reliability improvements

## [1.1.2] – 2026-05-23

1.1.2 - Subscription and Session Management update

 - Added Session and Track Management for Pro users (save, load, and manage sessions/tracks).
 - Added Restore Purchases, Refresh Status, and Manage Subscription actions.
 - Improved free-tier UX with blurred example sessions and clearer upgrade messaging.
 - Improved entitlement sync reliability.


## [1.1.1] – 2026-05-23

1.1.1 — Bug fixes

Download reliability: The test video download now continues in the background if you switch to another app. A system notification shows progress during the download.
Smoother download progress: The progress bar now animates fluidly rather than jumping between updates.

## [1.1.0] – 2026-05-23

What's new

RaceCoach is here! 🏁

• Upload GoPro MP4 footage from your track day
• Automatically extract GPS telemetry — speed, position, elevation
• Instant lap detection and lap time comparison
• Identify where you're gaining or losing time on track
• AI coaching analysis (coming soon)

Built for amateur and club racers who want data-driven feedback without the expensive hardware.

---

<!--
Template for future entries:

## [X.Y.Z] – YYYY-MM-DD

### Added
- 

### Changed
- 

### Fixed
- 

### Removed
- 
-->
