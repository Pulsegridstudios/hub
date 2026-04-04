---
title: Discord Application
layout: wiki
permalink: /pages/discord-application/
nav_group: applications
nav_order: 99
nav_hidden: true
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

> ℹ️ **Note**  
> Submission of an application does not guarantee acceptance.

---

## Before You Apply

Please make sure you:

- understand the expectations of staff conduct
- can remain professional when dealing with users
- are comfortable following rules and internal guidance
- understand that misuse of staff tools will result in removal

> ⚠️ **Warning**  
> False information, joke applications, or misuse of the application system may result in restrictions from future applications.

---

## Application Form

<div class="application-panel">
  <form id="discord-app-form" class="application-form">
    <div class="form-row">
      <label for="discord_name">Discord Username</label>
      <input id="discord_name" name="discord_name" type="text" required>
    </div>

    <div class="form-row">
      <label for="roblox_name">Roblox Username</label>
      <input id="roblox_name" name="roblox_name" type="text">
    </div>

    <div class="form-row">
      <label for="age">Age</label>
      <input id="age" name="age" type="text" required>
    </div>

    <div class="form-row">
      <label for="experience">Relevant Experience</label>
      <textarea id="experience" name="experience" rows="5" required></textarea>
    </div>

    <div class="form-row">
      <label for="why_join">Why do you want to join?</label>
      <textarea id="why_join" name="why_join" rows="6" required></textarea>
    </div>

    <div class="form-row honeypot" aria-hidden="true">
      <label for="website">Website</label>
      <input id="website" name="website" type="text" tabindex="-1" autocomplete="off">
    </div>

    <div class="form-actions">
      <button type="submit" id="discord-app-submit">Submit Application</button>
    </div>

    <p id="discord-app-status" class="form-status" role="status" aria-live="polite"></p>
  </form>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const form = document.getElementById("discord-app-form");
  const status = document.getElementById("discord-app-status");
  const submitButton = document.getElementById("discord-app-submit");

  if (!form || !status || !submitButton) return;

  form.addEventListener("submit", async function (event) {
    event.preventDefault();

    status.textContent = "";
    submitButton.disabled = true;
    submitButton.textContent = "Submitting...";

    const formData = new FormData(form);
    const payload = {
      discord_name: String(formData.get("discord_name") || "").trim(),
      roblox_name: String(formData.get("roblox_name") || "").trim(),
      age: String(formData.get("age") || "").trim(),
      experience: String(formData.get("experience") || "").trim(),
      why_join: String(formData.get("why_join") || "").trim(),
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
      status.textContent = "Application submitted successfully.";
    } catch (error) {
      status.textContent = error.message || "Something went wrong.";
    } finally {
      submitButton.disabled = false;
      submitButton.textContent = "Submit Application";
    }
  });
});
</script>

---

## Additional Notes

Applications are reviewed by the project team. Please allow time for responses.

If you are unsuccessful, you may be invited to apply again in future depending on project needs.

> 💡 **Tip**  
> Clear, honest, and professional answers will always help your application more than trying to sound overly formal.