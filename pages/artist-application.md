---
title: 3D Artist Application
layout: wiki
permalink: /pages/artist-application/
nav_group: applications
nav_order: 3
hero_image: /assets/images/control-room-banner.jpg
hero_title: 3D Artist Application
hero_subtitle: Apply to help create assets for Looped Operations
status: reviewed
---

## Overview

The 3D Artist role is responsible for creating and refining visual assets used within Looped Operations.

This includes:

- 3D models (props, equipment, environment assets)  
- Optimised meshes suitable for Roblox  
- Texturing and material setup  
- Maintaining a consistent visual style across the game  

Artists are expected to produce **clean, optimised, and game-ready assets**, while collaborating with developers and designers.

---

## Eligibility Requirements

Applicants must:

- Be **16 years of age or older**  
- Demonstrate a **good level of written English communication**  
- Have experience using **Blender or similar 3D software**  
- Understand basic modelling principles:
  - Clean topology  
  - Optimisation (low poly where needed)  
  - UV mapping  
  - Texturing basics  
- Be able to create assets suitable for **real-time game performance**  
- Be willing to follow project structure and visual standards  

> ⚠️ **Warning**  
> Applications from individuals under the age of 16 will not be considered.

---

## Expectations

3D Artists are expected to:

- Optimise models for performance (low poly, efficient geometry)  
- Maintain consistent scale and proportions  
- Follow project naming and organisation standards  
- Test assets in Roblox where required  
- Work collaboratively with developers and other contributors  

> ℹ️ **Note**  
> Assets may be reviewed and adjusted before being accepted into the main project.

---

## Voluntary Roles

All roles within PulseGrid Studios are currently offered on a **voluntary basis**.

This means:

- No financial compensation is provided  
- Contributions are made at your own discretion  
- Experience gained may support personal development  

> ℹ️ **Note**  
> These roles are intended for individuals who wish to contribute to the project, gain experience, and be part of the development process.

---

> ℹ️ **Note**  
> Submission of an application does not guarantee acceptance.

<div class="application-panel">
  <form id="artist-app-form" class="application-form multi-step-form">

    <div class="form-step is-active" data-step="1">
      <h3>Step 1 — Basic Information</h3>

      <div class="form-row">
        <label for="roblox_name">Roblox Username</label>
        <input id="roblox_name" name="roblox_name" type="text" required>
      </div>

      <div class="form-row">
        <label for="discord_name">Discord Username</label>
        <input id="discord_name" name="discord_name" type="text" required>
      </div>

      <div class="form-grid-two">
        <div class="form-row">
          <label for="timezone">Timezone</label>
          <input id="timezone" name="timezone" type="text" required>
        </div>

        <div class="form-row">
          <label for="community_time">How long have you been in the community?</label>
          <input id="community_time" name="community_time" type="text" required>
        </div>
      </div>
    </div>

    <div class="form-step" data-step="2">
      <h3>Step 2 — Experience</h3>

      <div class="form-grid-two">
        <div class="form-row">
          <label for="blender_experience">Do you use Blender or similar software?</label>
          <select id="blender_experience" name="blender_experience" required>
            <option value="">Select...</option>
            <option value="Yes">Yes</option>
            <option value="No">No</option>
          </select>
        </div>

        <div class="form-row">
          <label for="team_experience">Have you worked in a team before?</label>
          <select id="team_experience" name="team_experience" required>
            <option value="">Select...</option>
            <option value="Yes">Yes</option>
            <option value="No">No</option>
          </select>
        </div>
      </div>

      <div class="form-row">
        <label for="experience_time">How long have you been creating 3D models?</label>
        <input id="experience_time" name="experience_time" type="text" required>
      </div>

      <div class="form-row">
        <label for="assets_created">What types of assets have you created?</label>
        <textarea id="assets_created" name="assets_created" rows="5" required></textarea>
      </div>

      <div class="form-row">
        <label for="preferred_area">What do you prefer working on?</label>
        <select id="preferred_area" name="preferred_area" required>
          <option value="">Select...</option>
          <option value="Props">Props</option>
          <option value="Environment">Environment</option>
          <option value="Machinery">Machinery / Industrial</option>
          <option value="UI Assets">UI / Icons</option>
          <option value="Texturing">Texturing</option>
        </select>
      </div>
    </div>

    <div class="form-step" data-step="3">
      <h3>Step 3 — Portfolio</h3>

      <div class="form-row">
        <label for="portfolio_links">Links to your work (ArtStation, Sketchfab, Google Drive, etc.)</label>
        <textarea id="portfolio_links" name="portfolio_links" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="best_project">Describe your best project</label>
        <textarea id="best_project" name="best_project" rows="5" required></textarea>
      </div>

      <div class="form-row">
        <label for="workflow">What is your typical workflow when creating a model?</label>
        <textarea id="workflow" name="workflow" rows="5" required></textarea>
      </div>
    </div>

    <div class="form-step" data-step="4">
      <h3>Step 4 — Scenarios</h3>

      <div class="form-row">
        <label for="scenario_optimisation">You are asked to optimise a high-poly model. What do you do?</label>
        <textarea id="scenario_optimisation" name="scenario_optimisation" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="scenario_style">Your model does not match the game’s style. How do you fix it?</label>
        <textarea id="scenario_style" name="scenario_style" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="scenario_feedback">You receive feedback that your model needs changes. How do you respond?</label>
        <textarea id="scenario_feedback" name="scenario_feedback" rows="4" required></textarea>
      </div>
    </div>

    <div class="form-step" data-step="5">
      <h3>Step 5 — Agreement</h3>

      <div class="agreement-box">
        <p>I understand contributor access is for project work only.</p>
        <p>I will not leak or misuse project assets.</p>
        <p>I agree to follow project standards and guidelines.</p>
        <p>I understand I may be removed for misuse or poor conduct.</p>
      </div>

      <div class="form-row checkbox-row">
        <label class="checkbox-label">
          <input id="agreement" name="agreement" type="checkbox" required>
          <span>I Agree</span>
        </label>
      </div>

      <div class="form-row honeypot" aria-hidden="true">
        <label for="website">Website</label>
        <input id="website" name="website" type="text" tabindex="-1" autocomplete="off">
      </div>
    </div>

    <div class="form-navigation">
      <button type="button" id="form-prev" class="secondary-btn" disabled>Back</button>
      <div class="form-step-indicator" id="form-step-indicator">Step 1 of 5</div>
      <button type="button" id="form-next">Next</button>
      <button type="submit" id="artist-app-submit" style="display:none;">Submit Application</button>
    </div>

    <p id="artist-app-status" class="form-status"></p>
  </form>
</div>

---

## Additional Notes

Applications are reviewed by the project team. Please allow time for responses.

If you are unsuccessful, you may be invited to apply again in future depending on project needs.

> 💡 **Tip**  
> Clear, honest, and professional answers will always help your application more than trying to sound overly formal.