---
title: Discord Application
layout: wiki
permalink: /pages/discord-application/
nav_group: applications
nav_order: 99
nav_hidden: true
hero_image: /assets/images/control-room-banner.jpg
hero_title: Discord Application
hero_subtitle: Apply for Discord moderation and community support roles
status: reviewed
---
## Overview

Use this page to apply for Discord-related roles within the Looped Operations project.

Applications may be used for positions such as:

- Discord Moderator
- Community Support
- Future staff and contributor roles

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

---

## Before You Apply

Please make sure you:

- understand the expectations of staff [conduct]({{ '/pages/discord-moderation/' | relative_url }})
- can remain professional when dealing with users
- are comfortable following rules and internal guidance
- understand that misuse of staff tools will result in removal

> ⚠️ **Warning**  
> False information, joke applications, or misuse of the application system may result in restrictions from future applications.

---

## Application Form

---


Complete the application below. Please answer honestly and fully.

> ⚠️ **Warning**  
> Joke applications, false information, or misuse of the application system may result in restrictions from future applications.

<div class="application-panel">
  <form id="discord-app-form" class="application-form multi-step-form">

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

      <div class="form-row">
        <label for="timezone">Timezone (e.g. GMT / BST / EST)</label>
        <input id="timezone" name="timezone" type="text" required>
      </div>

      <div class="form-row">
        <label for="community_time">How long have you been part of the SOP community?</label>
        <input id="community_time" name="community_time" type="text" required>
      </div>
    </div>

    <div class="form-step" data-step="2">
      <h3>Step 2 — Experience</h3>

      <div class="form-row">
        <label for="moderation_experience">Do you have previous moderation experience?</label>
        <select id="moderation_experience" name="moderation_experience" required>
          <option value="">Select...</option>
          <option value="Yes">Yes</option>
          <option value="No">No</option>
        </select>
      </div>

      <div class="form-row">
        <label for="experience_detail">If yes, please describe your experience (games, servers, responsibilities, etc.)</label>
        <textarea id="experience_detail" name="experience_detail" rows="5"></textarea>
      </div>

      <div class="form-row">
        <label for="roblox_mod_experience">Have you moderated a Roblox game before?</label>
        <select id="roblox_mod_experience" name="roblox_mod_experience" required>
          <option value="">Select...</option>
          <option value="Yes">Yes</option>
          <option value="No">No</option>
        </select>
      </div>

      <div class="form-row">
        <label for="tools_used">If yes, which tools/systems have you used before?</label>
        <textarea id="tools_used" name="tools_used" rows="4"></textarea>
      </div>
    </div>

    <div class="form-step" data-step="3">
      <h3>Step 3 — Moderation Scenarios</h3>

      <div class="form-row">
        <label for="scenario_spam">A player is spamming chat and disrupting others. What do you do?</label>
        <textarea id="scenario_spam" name="scenario_spam" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="scenario_argument">Two players are arguing and blaming each other. How do you handle the situation?</label>
        <textarea id="scenario_argument" name="scenario_argument" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="scenario_ranked">A higher-ranked player is breaking the rules. What would you do?</label>
        <textarea id="scenario_ranked" name="scenario_ranked" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="scenario_bug">A player reports a bug or exploit. What steps do you take?</label>
        <textarea id="scenario_bug" name="scenario_bug" rows="4" required></textarea>
      </div>

      <div class="form-row">
        <label for="scenario_abuse">You are given access to admin commands. A friend asks you to “just give them a small advantage” or help them. What do you do?</label>
        <textarea id="scenario_abuse" name="scenario_abuse" rows="4" required></textarea>
      </div>
    </div>

    <div class="form-step" data-step="4">
      <h3>Step 4 — Availability</h3>

      <div class="form-row">
        <label for="hours_per_day">How many hours per day can you moderate?</label>
        <input id="hours_per_day" name="hours_per_day" type="text" required>
      </div>

      <div class="form-row">
        <label for="usual_times">What times are you usually online?</label>
        <input id="usual_times" name="usual_times" type="text" required>
      </div>

      <div class="form-row">
        <label for="weekends">Are you active on weekends?</label>
        <select id="weekends" name="weekends" required>
          <option value="">Select...</option>
          <option value="Yes">Yes</option>
          <option value="No">No</option>
          <option value="Sometimes">Sometimes</option>
        </select>
      </div>
    </div>

    <div class="form-step" data-step="5">
      <h3>Step 5 — Behaviour & Attitude</h3>

      <div class="form-row">
        <label for="why_moderator">Why do you want to be a moderator?</label>
        <textarea id="why_moderator" name="why_moderator" rows="5" required></textarea>
      </div>

      <div class="form-row">
        <label for="good_fit">What makes you a good fit for this role?</label>
        <textarea id="good_fit" name="good_fit" rows="5" required></textarea>
      </div>

      <div class="form-row">
        <label for="toxic_players">How do you handle difficult or toxic players?</label>
        <textarea id="toxic_players" name="toxic_players" rows="5" required></textarea>
      </div>
    </div>

    <div class="form-step" data-step="6">
      <h3>Step 6 — Agreement</h3>

      <div class="agreement-box">
        <p>I understand that moderation tools are for enforcing rules, not personal use.</p>
        <p>I will not abuse commands (kick, ban, mute, etc.) under any circumstances.</p>
        <p>I understand that all moderator actions may be logged and reviewed.</p>
        <p>I agree that abuse of power will result in immediate removal.</p>
        <p>I will treat all players fairly regardless of rank or personal opinions.</p>
        <p>I agree to act professionally at all times.</p>
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
      <button type="submit" id="discord-app-submit" style="display:none;">Submit Application</button>
    </div>

    <p id="discord-app-status" class="form-status" role="status" aria-live="polite"></p>
  </form>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const form = document.getElementById("discord-app-form");
  if (!form) return;

  const steps = Array.from(form.querySelectorAll(".form-step"));
  const prevBtn = document.getElementById("form-prev");
  const nextBtn = document.getElementById("form-next");
  const submitBtn = document.getElementById("discord-app-submit");
  const indicator = document.getElementById("form-step-indicator");
  const status = document.getElementById("discord-app-status");

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
      roblox_name: String(formData.get("roblox_name") || "").trim(),
      discord_name: String(formData.get("discord_name") || "").trim(),
      timezone: String(formData.get("timezone") || "").trim(),
      community_time: String(formData.get("community_time") || "").trim(),
      moderation_experience: String(formData.get("moderation_experience") || "").trim(),
      experience_detail: String(formData.get("experience_detail") || "").trim(),
      roblox_mod_experience: String(formData.get("roblox_mod_experience") || "").trim(),
      tools_used: String(formData.get("tools_used") || "").trim(),
      scenario_spam: String(formData.get("scenario_spam") || "").trim(),
      scenario_argument: String(formData.get("scenario_argument") || "").trim(),
      scenario_ranked: String(formData.get("scenario_ranked") || "").trim(),
      scenario_bug: String(formData.get("scenario_bug") || "").trim(),
      scenario_abuse: String(formData.get("scenario_abuse") || "").trim(),
      hours_per_day: String(formData.get("hours_per_day") || "").trim(),
      usual_times: String(formData.get("usual_times") || "").trim(),
      weekends: String(formData.get("weekends") || "").trim(),
      why_moderator: String(formData.get("why_moderator") || "").trim(),
      good_fit: String(formData.get("good_fit") || "").trim(),
      toxic_players: String(formData.get("toxic_players") || "").trim(),
      agreement: formData.get("agreement") ? "Yes" : "No",
      website: String(formData.get("website") || "").trim()
    };

    try {
      const response = await fetch("https://lingering-frost-5384.frazergrant345.workers.dev/discord-application", {
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