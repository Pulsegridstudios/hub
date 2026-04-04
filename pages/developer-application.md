---
title: Developer Application
layout: wiki
permalink: /pages/developer-application/
nav_group: applications
nav_order: 99
nav_hidden: true
hero_image: /assets/images/control-room-banner.jpg
hero_title: Developer Application
hero_subtitle: Apply to help build Looped Operations
status: reviewed
---

## Overview

The Developer role is responsible for contributing to the design, development, and maintenance of systems within Looped Operations.

This includes work on:

- Roblox systems and scripting  
- UI and user experience  
- Game mechanics and logic  
- Performance and optimisation  

Developers are expected to follow established standards, maintain clean and structured code, and collaborate effectively with other contributors.


---

## Eligibility Requirements

Applicants must:

- Be **16 years of age or older**  
- Demonstrate a **good level of written English communication**  
- Have a working knowledge of **Lua / Luau (Roblox scripting)**  
- Be able to write **clean, readable, and maintainable code**  
- Understand basic concepts such as:
  - Variables, functions, and tables  
  - Events and client/server structure  
  - Debugging and problem solving  
- Be willing to follow project structure and coding standards  

> ⚠️ **Warning**  
> Applications from individuals under the age of 16 will not be considered.

## Expectations

Developers are expected to:

- Test their work before submission  
- Avoid unnecessary complexity  
- Write efficient and optimised code  
- Document systems where appropriate  

> ℹ️ **Note**  
> Code may be reviewed before being accepted into the main project.


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
  <form id="developer-app-form" class="application-form multi-step-form">

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
      <h3>Step 2 — Development Experience</h3>

      <div class="form-grid-two">
        <div class="form-row">
          <label for="roblox_scripting">Have you scripted in Roblox before?</label>
          <select id="roblox_scripting" name="roblox_scripting" required>
            <option value="">Select...</option>
            <option value="Yes">Yes</option>
            <option value="No">No</option>
          </select>
        </div>

        <div class="form-row">
          <label for="team_experience">Have you worked in a development team before?</label>
          <select id="team_experience" name="team_experience" required>
            <option value="">Select...</option>
            <option value="Yes">Yes</option>
            <option value="No">No</option>
          </select>
        </div>
      </div>

      <div class="form-row">
        <label for="lua_experience">How long have you used Lua / Luau?</label>
        <input id="lua_experience" name="lua_experience" type="text" required>
      </div>

      <div class="form-row">
        <label for="systems_built">What kinds of systems have you built?</label>
        <textarea id="systems_built" name="systems_built" rows="5" required></textarea>
      </div>

      <div class="form-row">
        <label for="preferred_area">What area do you prefer working in?</label>
        <select id="preferred_area" name="preferred_area" required>
          <option value="">Select...</option>
          <option value="UI">UI</option>
          <option value="Gameplay">Gameplay</option>
          <option value="Plant Systems">Plant Systems</option>
          <option value="Optimisation">Optimisation</option>
          <option value="Data / Back-end">Data / Back-end</option>
          <option value="General Scripting">General Scripting</option>
        </select>
      </div>
    </div>

    <div class="form-step" data-step="3">
      <h3>Step 3 — Portfolio / Examples</h3>

      <div class="form-row">
        <label for="portfolio_links">Links to games, GitHub, models, or examples of your work</label>
        <textarea id="portfolio_links" name="portfolio_links" rows="4"></textarea>
      </div>

      <div class="form-row">
        <label for="best_project">Describe the best project you have worked on</label>
        <textarea id="best_project" name="best_project" rows="5" required></textarea>
      </div>

      <div class="form-row">
        <label for="debugging_approach">How do you usually debug a broken system?</label>
        <textarea id="debugging_approach" name="debugging_approach" rows="5" required></textarea>
      </div>
    </div>

    <div class="form-step" data-step="4">
      <h3>Step 4 — Lua / Luau Quiz</h3>

      <div class="form-row">
        <label for="quiz_pairs">What does <code>pairs()</code> do in Lua?</label>
        <textarea id="quiz_pairs" name="quiz_pairs" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="quiz_scripts">What is the difference between a <code>LocalScript</code> and a <code>Script</code> in Roblox?</label>
        <textarea id="quiz_scripts" name="quiz_scripts" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="quiz_data">How would you store player data safely in Roblox?</label>
        <textarea id="quiz_data" name="quiz_data" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="quiz_remoteevent">What is a <code>RemoteEvent</code> used for?</label>
        <textarea id="quiz_remoteevent" name="quiz_remoteevent" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="quiz_bugfix">This code does not work correctly. What is wrong with it, and how would you fix it?</label>
        <pre><code>local Players = game:GetService("Players")

Players.PlayerAdded:Connect(function(player)
    player.leaderstats.Coins.Value = player.leaderstats.Coins.Value + 100
end)</code></pre>
        <textarea id="quiz_bugfix" name="quiz_bugfix" rows="6" required></textarea>
      </div>
    </div>

    <div class="form-step" data-step="5">
      <h3>Step 5 — Development Scenarios</h3>

      <div class="form-row">
        <label for="scenario_update_break">A system breaks after an update. What do you do first?</label>
        <textarea id="scenario_update_break" name="scenario_update_break" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="scenario_messy_code">You find messy code written by another developer. How do you handle it?</label>
        <textarea id="scenario_messy_code" name="scenario_messy_code" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="scenario_unfair_feature">A friend asks you to add an unfair hidden advantage for them. What do you do?</label>
        <textarea id="scenario_unfair_feature" name="scenario_unfair_feature" rows="4" required></textarea>
      </div>
    </div>

    <div class="form-step" data-step="6">
      <h3>Step 6 — Agreement</h3>

      <div class="agreement-box">
        <p>I understand contributor access is for project work only.</p>
        <p>I will not intentionally damage, leak, or abuse project assets or systems.</p>
        <p>I agree to communicate honestly and work professionally.</p>
        <p>I understand that accepted contributors may be removed for misuse of access or poor conduct.</p>
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
      <div class="form-step-indicator" id="form-step-indicator">Step 1 of 6</div>
      <button type="button" id="form-next">Next</button>
      <button type="submit" id="developer-app-submit" style="display:none;">Submit Application</button>
    </div>

    <p id="developer-app-status" class="form-status" role="status" aria-live="polite"></p>
  </form>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const form = document.getElementById("developer-app-form");
  if (!form) return;

  const steps = Array.from(form.querySelectorAll(".form-step"));
  const prevBtn = document.getElementById("form-prev");
  const nextBtn = document.getElementById("form-next");
  const submitBtn = document.getElementById("developer-app-submit");
  const indicator = document.getElementById("form-step-indicator");
  const status = document.getElementById("developer-app-status");

  let currentStep = 0;

  function showStep(index) {
    steps.forEach((step, i) => {
      step.classList.toggle("is-active", i === index);
    });

    prevBtn.disabled = index === 0;
    indicator.textContent = `Step ${index + 1} of ${steps.length}`;

    const isLast = index === steps.length - 1;
    nextBtn.style.display = isLast ? "none" : "inline-flex";
    submitBtn.style.display = isLast ? "inline-flex" : "none";
  }

  function validateStep(index) {
    const fields = steps[index].querySelectorAll("input, textarea, select");
    for (const field of fields) {
      if (!field.checkValidity()) {
        field.reportValidity();
        return false;
      }
    }
    return true;
  }

  prevBtn.addEventListener("click", function () {
    if (currentStep > 0) {
      currentStep--;
      showStep(currentStep);
      form.scrollIntoView({ behavior: "smooth", block: "start" });
    }
  });

  nextBtn.addEventListener("click", function () {
    if (!validateStep(currentStep)) return;
    if (currentStep < steps.length - 1) {
      currentStep++;
      showStep(currentStep);
      form.scrollIntoView({ behavior: "smooth", block: "start" });
    }
  });

  form.addEventListener("submit", async function (event) {
    event.preventDefault();

    if (!validateStep(currentStep)) return;

    status.textContent = "";
    status.classList.remove("is-success", "is-error");
    submitBtn.disabled = true;
    submitBtn.textContent = "Submitting...";

    const formData = new FormData(form);
    const payload = {
      application_type: "developer",
      roblox_name: String(formData.get("roblox_name") || "").trim(),
      discord_name: String(formData.get("discord_name") || "").trim(),
      timezone: String(formData.get("timezone") || "").trim(),
      community_time: String(formData.get("community_time") || "").trim(),
      roblox_scripting: String(formData.get("roblox_scripting") || "").trim(),
      team_experience: String(formData.get("team_experience") || "").trim(),
      lua_experience: String(formData.get("lua_experience") || "").trim(),
      systems_built: String(formData.get("systems_built") || "").trim(),
      preferred_area: String(formData.get("preferred_area") || "").trim(),
      portfolio_links: String(formData.get("portfolio_links") || "").trim(),
      best_project: String(formData.get("best_project") || "").trim(),
      debugging_approach: String(formData.get("debugging_approach") || "").trim(),
      quiz_pairs: String(formData.get("quiz_pairs") || "").trim(),
      quiz_scripts: String(formData.get("quiz_scripts") || "").trim(),
      quiz_data: String(formData.get("quiz_data") || "").trim(),
      quiz_remoteevent: String(formData.get("quiz_remoteevent") || "").trim(),
      quiz_bugfix: String(formData.get("quiz_bugfix") || "").trim(),
      scenario_update_break: String(formData.get("scenario_update_break") || "").trim(),
      scenario_messy_code: String(formData.get("scenario_messy_code") || "").trim(),
      scenario_unfair_feature: String(formData.get("scenario_unfair_feature") || "").trim(),
      agreement: formData.get("agreement") ? "Yes" : "No",
      website: String(formData.get("website") || "").trim()
    };

    try {
      const response = await fetch("https://lingering-frost-5384.frazergrant345.workers.dev/developer-application", {
        method: "POST",
        headers: {
          "Content-Type": "application/json"
        },
        body: JSON.stringify(payload)
      });

      const result = await response.json();

      if (!response.ok) {
        throw new Error(result.error || "Submission failed.");
      }

      form.reset();
      currentStep = 0;
      showStep(currentStep);
      status.textContent = "Application submitted successfully.";
      status.classList.add("is-success");
    } catch (error) {
      status.textContent = error.message || "Something went wrong.";
      status.classList.add("is-error");
    } finally {
      submitBtn.disabled = false;
      submitBtn.textContent = "Submit Application";
    }
  });

  showStep(currentStep);
});
</script>

---

## Additional Notes

Applications are reviewed by the project team. Please allow time for responses.

If you are unsuccessful, you may be invited to apply again in future depending on project needs.

> 💡 **Tip**  
> Clear, honest, and professional answers will always help your application more than trying to sound overly formal.