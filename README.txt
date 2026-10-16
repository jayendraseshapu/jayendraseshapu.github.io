JAYENDRA SESHAPU — REDNOVA-INSPIRED PORTFOLIO

FILES
- index.html: complete responsive portfolio page (HTML, CSS, and JavaScript).
- assets/cinematic-sunset.jpg: cinematic sunset scene with the seated laptop user.
- assets/project-courtroom.jpg: courtroom/video recording project image.
- assets/project-social-automation.jpg: social media automation project image.
- assets/project-content-research.jpg: article research workstation project image.
- assets/automation-operator.png: retained source asset; not used as a foreground overlay.
- Jayendra_Resume.pdf: resume download used by the hero CTA.

RUN LOCALLY (Windows)
1. Extract the ZIP to a folder.
2. Open PowerShell in that folder.
3. Run: python -m http.server 8000
4. Open http://localhost:8000 in your browser.

You can also double-click index.html, but a local server is recommended for consistent asset loading.

NOTES
- All visual assets referenced by index.html are bundled locally under assets/.
- The clock uses Asia/Kolkata time.
- Navigation, mobile menu, scroll-to-top, project links, social links, and resume download are included.
- The background uses the cinematic sunset scene as the page backdrop, with subtle drifting particles and reduced-motion support.


Latest update (October 16, 2026):
- Restored the three translucent right-side hero panels: System Status, a live IST clock/date, and Current Focus with the handwritten quote.
- The clock refreshes every second using the Asia/Kolkata time zone.
- Added subtle animated wind streaks and drifting ember particles over the existing cinematic scene; all animations respect prefers-reduced-motion.
- The experience section and statistics strip both show 2+ years of AI Automation Engineer experience.
- Kept the original background and project image assets; no image paths were changed.

Visual limitation:
- The sunset, city, and seated character are one flattened background image. The hair and cape already appear wind-swept in that image, but CSS cannot independently animate those exact pixels without a separate cutout/layered character asset. The update therefore animates atmospheric wind streaks and particles without moving or hiding the character or replacing the scene.


Latest update (October 16, 2026 — horizontal information panels):
- The System Status, live IST clock/date, and Current Focus cards now sit side-by-side in one horizontal row on desktop instead of a vertical stack.
- The original cinematic sunset background asset is unchanged, preserving the sun, mountains, illuminated city, and seated laptop character.
- On tablet the cards adapt into a compact row; on mobile they stack for readability.
- Clock remains live and uses Asia/Kolkata.


Image reliability note: The main cinematic background and featured project photos are embedded directly in index.html so they remain visible even in single-file previews. The assets folder is also retained for normal local development.
