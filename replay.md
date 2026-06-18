---
layout: home
permalink: /replay/
title: "Project: Archery Replay Kiosk"
hero_eyebrow: "Custom Archery Feedback"
hero_heading: "The Archery Replay System"
hero_sub: "A custom video feedback tool developed to provide hands-free, time-shifted visual review directly on the shooting line."
hero_img: "/assets/photo-reel/replay-kiosk-hero.jpg"

about_heading: "Why I Built This Tool"
about_text_1: "Video review is one of the most effective ways to analyze archery form, but traditional methods introducing a lot of friction. Stopping to hit record on a phone, stepping off the line to scrub through a timeline, and managing video files completely disrupts the rhythm of a shooting session. I built this system to eliminate that overhead entirely."
about_text_2: "The software runs completely on autopilot in the background. It allows an archer to focus entirely on their shot execution, glance to the monitor and immediately watch their shot sequence in a natural reflection window without needing to interact with a mouse, keyboard, or screen."

credentials:
  - "Automated Delayed Loop"
  - "Optional Multi-Camera Layout"
  - "Precision Frame Scrubbing"
  - "Integrated Timer"

services:
  - title: "01 / Hands-Free Time-Shift"
    desc: "The system continuously loops video on a configurable 10-second delay. The archer executes a shot, glances to the monitor, and the video of that shot plays back automatically."
  - title: "02 / Multo-Angle Monitoring"
    desc: "As many standard USB webcams can be connected as there are available ports. Each shown on the monitor, synced."
  - title: "03 / App Management"
    desc: "Android app connects to the wifi emitted by the kiosk, allowing for the last two minutes of video to be scrolled through on both phone and screen. Immediate frame by frame analysis. Never miss a shot."
  - title: "04 / Saving and Storing"
    desc: "Clips can be saved to the kiosk for the duration of the session and shown on the screen to compare shots throughout the session. Clips can also be downloaded to the attached phone via wifi."
---

<!-- FEATURE DETAILED OVERVIEW -->
<section style="padding: 5rem 0;">
  <span class="eyebrow">Core Functionality</span>
  <h2>The User Interface & Controls</h2>
  <p style="max-width: 650px; margin-bottom: 3.5rem; color: var(--gray-600);">The system is controlled via a clean, web-based dashboard designed to be easily accessible from a phone, tablet, or kiosk monitor on the range line. Downloads available through a dedicated Android app.</p>
  
  <div class="grid-2" style="align-items: center; gap: 4rem;">
    <div>
      <h3 style="margin-top: 0;">Dual-Slider Frame Control</h3>
      <p style="font-size: 0.98rem; color: var(--gray-600); margin-bottom: 2rem;">
        When the live feed is paused, the interface opens up two separate scrubbing sliders for reviewing form. The **Macro Slider** allows you to quickly sweep through the last two minutes of footage to find a specific shot. The **Micro Slider** allows for fine-tuning, letting you step through the footage frame-by-frame to isolate the exact moment of the release or clicker break.
      </p>
    
    <div style="background: var(--gray-100); padding: 1.5rem; border-radius: var(--radius);">
      <img src="/assets/photo-reel/interface-controls.jpg" alt="Web application interface showing playback controls and scrubbing sliders" style="width: 100%; height: auto; display: block; border-radius: calc(var(--radius) - 4px); margin-bottom: 1.5rem;" />
      <span class="eyebrow" style="margin-bottom: 0.2rem; font-size: 0.75rem;">Dashboard View</span>
      <h3 style="font-size: 1.05rem; margin-bottom: 0.2rem;">Control Layout</h3>
      <p style="font-size: 0.88rem; color: var(--gray-600); line-height: 1.5;">The browser-based dashboard layout, featuring simple button controls and timeline adjustment sliders meant for quick adjustments between ends.</p>
    </div>
  </div>
</section>

<!-- TOURNAMENT SIMULATION FEATURES -->
<section style="padding: 5rem 0; border-bottom: none;">
  <span class="eyebrow">Pacing Tools</span>
  <h2>Integrated Tournament Timer</h2>
  
  <div class="grid-2" style="align-items: center; gap: 4rem; direction: rtl;">
    <div>
      <h3 style="margin-top: 0;">Contextual Countdown Overlay</h3>
      <p style="font-size: 0.98rem; color: var(--gray-600); margin-bottom: 2rem;">
        To help practice shot pacing and timing under tournament conditions, I integrated a visual countdown timer directly onto the video display. The tool includes standard tournament presets (like 120-second or 240-second ends) as well as a custom 40-second configuration for practicing rapid alternate-shooting scenarios.
      </p>
      
      <h3>Visual Warning Cues</h3>
      <p style="font-size: 0.98rem; color: var(--gray-600);">
        The timer overlay automatically responds to the remaining time by shifting colors, mirroring official World Archery tournament clocks. It stays a clean green during safe boundaries, changes to orange when the clock drops below 30 seconds, and flashes red during the final 10 seconds of the end.
      </p>
    </div>
    
    <div style="background: var(--gray-100); padding: 1.5rem; border-radius: var(--radius); direction: ltr;">
      <img src="/assets/photo-reel/timer-overlay-sample.jpg" alt="Video stream with a large digital countdown clock overlaid on the screen" style="width: 100%; height: auto; display: block; border-radius: calc(var(--radius) - 4px); margin-bottom: 1.5rem;" />
      <span class="eyebrow" style="margin-bottom: 0.2rem; font-size: 0.75rem;">Display Overlay</span>
      <h3 style="font-size: 1.05rem; margin-bottom: 0.2rem;">Match Timer Integration</h3>
      <p style="font-size: 0.88rem; color: var(--gray-600); line-height: 1.5;">A look at the video stream canvas with the custom countdown clock rendered over the footage to help monitor execution pacing.</p>
    </div>
  </div>
</section>