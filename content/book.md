+++
title = "Book Exotic Pet Care | San Francisco & Peninsula | House of Guineas"
shortTitle = "Book Care"
description = "Request in-home or recurring exotic pet care in San Francisco & the Peninsula. Tell us about your pet and dates, and we'll get back to you to set up a meet-and-greet."
og_image = "BunnyReceivingPets.jpg"
[params]
  hideCtaBlock = true
[sitemap]
  priority = 0.8
+++

Tell us a little about your pet and what you need, and we'll get right back to you to talk through care and set up a meet-and-greet. Prefer to talk now? [Call or text 415-484-6493](tel:415-484-6493) or email [petcare@houseofguineas.com](mailto:petcare@houseofguineas.com).
<!--more-->

<!--
  FORM SETUP — ALREADY WIRED (via FormSubmit.co; no account or API key needed).
  Submissions are emailed to petcare@houseofguineas.com.

  ⚠️ ONE-TIME ACTIVATION (only you can do this):
  The FIRST time anyone submits this form after it goes live, FormSubmit will email
  petcare@houseofguineas.com a "Confirm your email" link. Click it once to activate.
  After that, every booking request lands in that inbox automatically. (Tip: submit
  the form yourself once after launch to trigger and complete the activation.)

  To change the destination inbox, edit the email in the <form action="..."> below.
  On successful submit, users are sent to /thank-you/.
-->

<style>
  .booking-form { max-width: 640px; margin: 1.5rem auto; }
  .booking-form .form-row { margin-bottom: 1.1rem; }
  .booking-form label { display: block; font-weight: 600; margin-bottom: 0.35rem; }
  .booking-form input[type="text"],
  .booking-form input[type="email"],
  .booking-form input[type="tel"],
  .booking-form select,
  .booking-form textarea {
    width: 100%;
    padding: 0.7rem 0.85rem;
    border: 1px solid #ccc;
    border-radius: 8px;
    font-size: 1rem;
    font-family: inherit;
    box-sizing: border-box;
  }
  .booking-form textarea { min-height: 110px; resize: vertical; }
  .booking-form fieldset { border: 1px solid #ddd; border-radius: 8px; padding: 0.75rem 1rem 1rem; }
  .booking-form legend { font-weight: 600; padding: 0 0.4rem; font-size: 1rem; }
  .booking-form .check-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 0.4rem 1rem; }
  .booking-form .check-grid label { font-weight: 400; display: flex; align-items: center; gap: 0.5rem; margin: 0; }
  .booking-form .hp { position: absolute; left: -5000px; }
  .booking-form .required { color: #C4704B; }
  .booking-form .form-note { font-size: 0.9rem; color: #666; margin-top: 0.35rem; }
  @media (max-width: 480px) { .booking-form .check-grid { grid-template-columns: 1fr; } }
</style>

<form class="booking-form" action="https://formsubmit.co/petcare@houseofguineas.com" method="POST">
  <!-- FormSubmit config -->
  <input type="hidden" name="_subject" value="New care request from houseofguineas.com">
  <input type="hidden" name="_template" value="table">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_next" value="https://www.houseofguineas.com/thank-you/">

  <div class="form-row">
    <label for="name">Your name <span class="required">*</span></label>
    <input type="text" id="name" name="name" required>
  </div>

  <div class="form-row">
    <label for="email">Email <span class="required">*</span></label>
    <input type="email" id="email" name="email" required>
  </div>

  <div class="form-row">
    <label for="phone">Phone / text number</label>
    <input type="tel" id="phone" name="phone">
  </div>

  <div class="form-row">
    <label for="location">Neighborhood or city <span class="required">*</span></label>
    <input type="text" id="location" name="location" placeholder="e.g. Inner Sunset, or San Mateo" required>
    <p class="form-note">Helps us confirm we cover your area (San Francisco through the Peninsula).</p>
  </div>

  <div class="form-row">
    <label for="service">What kind of care do you need? <span class="required">*</span></label>
    <select id="service" name="service" required>
      <option value="" disabled selected>Choose one…</option>
      <option value="Routine / recurring care">Routine / recurring upkeep (weekly or biweekly)</option>
      <option value="Travel / vacation care">In-home care while I travel</option>
      <option value="Boarding">Boarding (hosted in San Francisco)</option>
      <option value="Not sure yet">Not sure yet — help me decide</option>
    </select>
  </div>

  <div class="form-row">
    <fieldset>
      <legend>My pet(s)</legend>
      <div class="check-grid">
        <label><input type="checkbox" name="pets" value="Guinea pig"> Guinea pig</label>
        <label><input type="checkbox" name="pets" value="Rabbit"> Rabbit</label>
        <label><input type="checkbox" name="pets" value="Chinchilla"> Chinchilla</label>
        <label><input type="checkbox" name="pets" value="Ferret"> Ferret</label>
        <label><input type="checkbox" name="pets" value="Rat / small mammal"> Rat / other small mammal</label>
        <label><input type="checkbox" name="pets" value="Bearded dragon"> Bearded dragon</label>
        <label><input type="checkbox" name="pets" value="Gecko / other reptile"> Gecko / other reptile</label>
        <label><input type="checkbox" name="pets" value="Turtle / tortoise"> Turtle / tortoise</label>
        <label><input type="checkbox" name="pets" value="Bird"> Bird</label>
        <label><input type="checkbox" name="pets" value="Cat"> Cat</label>
      </div>
    </fieldset>
  </div>

  <div class="form-row">
    <label for="dates">Dates or schedule</label>
    <input type="text" id="dates" name="dates" placeholder="e.g. weekly Tuesdays, or Aug 4–11">
  </div>

  <div class="form-row">
    <label for="message">Anything else we should know?</label>
    <textarea id="message" name="message" placeholder="Medication, feeding routine, number of pets, special needs…"></textarea>
  </div>

  <!-- Honeypot spam trap — leave empty -->
  <input class="hp" type="text" name="_honey" tabindex="-1" autocomplete="off" aria-hidden="true">

  <div class="form-row text-center">
    <button type="submit" class="btn btn-lg btn-cta-primary">Send My Request</button>
  </div>
</form>

*A meet-and-greet is required before our first visit — it's how we get to know you and your pet, and it's where care details and the booking deposit are handled. See the [FAQ page](/home/services/faqs/) for how booking, keys, and payment work.*
