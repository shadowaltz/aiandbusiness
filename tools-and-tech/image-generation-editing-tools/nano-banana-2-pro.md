# Nano Banana 2 / Pro

### Nano Banana 2

Google’s Nano Banana 2 is the second-generation Gemini image generation model, designed to deliver more realistic visuals, stronger text rendering, and improved editing control compared to its predecessor, positioning it as a more production-ready creative engine inside Google’s AI ecosystem.

Pros:

* Improved photorealism and detail consistency over the previous generation
* Better in-image text rendering and layout handling
* Tighter integration with Gemini workflows for conversational image creation and editing
* More reliable multi-object and complex scene generation

Cons:

* Still dependent on prompt quality for best results
* Competes in a crowded high-end image model market
* Advanced creative controls may require experimentation to master

## Nano Banana 2: Command & Parameter Cheat Sheet

Version: 2.0 (Feb 2026)

Scope: Gemini App, AI Studio, and Pro API

### 1. Core Reference Triggers (@ Commands)

| **Command** | **Function**                                                 | **Syntax Example**                                                 |
| ----------- | ------------------------------------------------------------ | ------------------------------------------------------------------ |
| @search     | Triggers live Google Search Grounding for factual accuracy.  | "Generate a schematic of @search\[2026 Tesla Model S Interior]"    |
| @acoustic   | Generates synchronized material-specific audio physics.      | "A ceramic bowl falling on wood floor @acoustic\[shatter]"         |
| @identity   | Locks character consistency across multiple generations.     | "Generate @identity\[Character\_1] in a futuristic Irvine library" |
| @translate  | Native in-image text translation and localization.           | "Update label text to @translate\[Japanese]"                       |
| @fusion     | Blends up to 14 reference images into a single lighting rig. | "Fuse @ref\[1-8] with volumetric lighting @fusion\[HDR]"           |

### 2. Advanced Thinking Parameters (Pro API)

These parameters allow you to control the "Reasoning vs. Speed" balance of the Gemini 3.1 architecture.

* \--thinking\_level \[minimal|dynamic|high]
  * _minimal:_ For rapid ideation (1s). Best for social media posts.
  * _dynamic:_ Default mode. Automatically balances logic and speed.
  * _high:_ For complex infographics, architectural renders, and fine text.
* \--physics\_engine \[enabled|disabled]
  * Set to _enabled_ to ensure shadows, reflections, and light fall-off respect real-world optical laws.
* \--upscale \[2k|4k|8k]
  * Directly outputs or upscales the generation to high-fidelity production resolutions.

### 3. Aspect Ratio Presets

Nano Banana 2 supports extreme aspect ratios for specialized marketing formats.

* \--ar 8:1 / 1:8 (Ultra-wide Panoramas / Mobile Scroller Ads)
* \--ar 4:1 / 1:4 (Website Banners / Story Posters)
* \--ar 2.39:1 (Cinematic Anamorphic)

### 4. Best Practices for "Identity Lock"

To maintain 100% character consistency in a storyboard (Irvine Filmmaker Workflow):

1. Step 1: Generate your "Hero Shot" and save the Character ID.
2. Step 2: Use `@identity[ID_Code]` in all subsequent prompts.
3. Step 3: Use `--thinking_level high` to ensure facial micro-details (skin texture, freckles) do not drift during transitions.

### Awesome Nano Banana Pro Prompts

{% embed url="https://github.com/YouMind-OpenLab/awesome-nano-banana-pro-prompts" %}

