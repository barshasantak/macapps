---
layout: default
title: Mac Apps Portfolio
description: Thoughtfully crafted utilities and tools for macOS.
---

<style>
  .app-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin: 2rem 0;
  }
  .app-card {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    padding: 1.5rem;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    box-shadow: 0 4px 6px rgba(0,0,0,0.04);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .app-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 16px rgba(0,0,0,0.08);
  }
  .app-header {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 0.75rem;
  }
  .app-icon {
    width: 56px;
    height: 56px;
    border-radius: 12px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    flex-shrink: 0;
  }
  .app-title {
  margin: 0;
  font-size: 1.25rem;
  font-weight: 600;
  }

  /* Disables Architect's negative-offset '///' prefix */
  .app-title:before {
    content: none !important;
    display: none !important;
  }
  .app-desc {
    color: #586069;
    font-size: 0.95rem;
    line-height: 1.4;
    margin-bottom: 1.5rem;
  }
  .app-actions {
    display: flex;
    gap: 0.75rem;
    align-items: center;
  }
  .btn {
    display: inline-block;
    padding: 0.45rem 0.85rem;
    font-size: 0.85rem;
    font-weight: 500;
    text-decoration: none;
    border-radius: 6px;
    text-align: center;
  }
  .btn-primary {
    background-color: #0366d6;
    color: #ffffff !important;
  }
  .btn-primary:hover {
    background-color: #0255b3;
  }
  .btn-secondary {
    background-color: #f6f8fa;
    color: #24292e !important;
    border: 1px solid #e1e4e8;
  }
  .btn-secondary:hover {
    background-color: #e1e4e8;
  }
</style>

## Crafted exclusively for macOS

Focused, lightweight, and native tools built to boost productivity and enhance your everyday workflow.

<div class="app-grid">

  <!-- Desktop Rover -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/Rover_128.png" alt="Rover Icon" />
        <h3 class="app-title">Desktop Rover</h3>
      </div>
      <p class="app-desc">Your Loyal Desktop Companion: Rover stays by your side, watches over your Mac, and keeps you company through every task. He's the loyal and dependable friend you need.</p>
    </div>
    <div class="app-actions">
      <a href="https://barshasantak.github.io/rover" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/us/app/desktop-rover/id6783631987?mt=12" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- Desktop Felix -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/Felix_128.png" alt="Felix Icon" />
        <h3 class="app-title">Desktop Felix</h3>
      </div>
      <p class="app-desc">Your Curious Desktop Companion: Felix explores, observes, and brings a touch of curiosity to your workspace. He helps you stay healthy and keeps an eye on your Mac.</p>
    </div>
    <div class="app-actions">
      <a href="https://barshasantak.github.io/felix" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/us/app/desktop-felix/id6791848020?mt=12" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- F1-Gantry -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/F1Gantry_128.png" alt="F1-Gantry Icon" />
        <h3 class="app-title">F1-Gantry</h3>
      </div>
      <p class="app-desc">Lights Out: An app simulating the official FIA Formula 1 starting gantry, with sub-millisecond reaction telemetry, jump-start penalty validation and competitive timing leaderboard.</p>
    </div>
    <div class="app-actions">
      <a href="https://barshasantak.github.io/f1-gantry" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/us/app/f1-gantry/id6814986763?mt=12" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- Image-Peek -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/ImagePeek_128.png" alt="Image-Peek Icon" />
        <h3 class="app-title">Image-Peek</h3>
      </div>
      <p class="app-desc">Elevate Your Digital Photography & Imaging Workflow: Native, high-performance image spec analyzer, deep EXIF/optical inspector, and A-B image comparator built for macOS.</p>
    </div>
    <div class="app-actions">
      <a href="https://barshasantak.github.io/image-peek" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/us/app/image-peek/id6817664535?mt=12" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- Audio_Peek -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/AudioPeek_128.png" alt="Audio-Peek Icon" />
        <h3 class="app-title">Audio-Peek</h3>
      </div>
      <p class="app-desc">Elevate Your Audio Workflow: The native, studio-grade audio specification analyzer and side-by-side A-B diff comparator engineered exclusively for macOS.</p>
    </div>
    <div class="app-actions">
      <a href="https://barshasantak.github.io/audio-peek" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/us/app/audio-peek/id6817665269?mt=12" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

  <!-- Video-Peek -->
  <div class="app-card">
    <div>
      <div class="app-header">
        <img class="app-icon" src="assets/icons/VideoPeek_128.png" alt="Video-Peek Icon" />
        <h3 class="app-title">Video-Peek</h3>
      </div>
      <p class="app-desc">Elevate Your Video Mastering & Workflow: The native, studio-grade video specification analyzer and side-by-side A-B diff comparator engineered exclusively for macOS.</p>
    </div>
    <div class="app-actions">
      <a href="https://barshasantak.github.io/video-peek" target="_blank" rel="noopener" class="btn btn-secondary">Learn More</a>
      <a href="https://apps.apple.com/us/app/video-peek/id6817666279?mt=12" target="_blank" rel="noopener" class="btn btn-primary">App Store ↗</a>
    </div>
  </div>

</div>

 <br>

### Need Support or Have Feedback?
Contact us by creating an issue for the respective app at [https://forms.gle/XDUkjJ2TJzEruakX9](https://forms.gle/XDUkjJ2TJzEruakX9).


 <br>
 
 <hr>
 
 <small>*© 2026 Santak Das, Tara Design Studio. All rights reserved.*</small>

 <br>
