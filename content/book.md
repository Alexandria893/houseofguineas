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

Tell us a little about your pet(s) and what you need, and we'll get right back to you to talk through care and set up a meet-and-greet. Prefer to talk now? [Call or text 415-484-6493](tel:415-484-6493) or email [petcare@houseofguineas.com](mailto:petcare@houseofguineas.com).
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
  .booking-form .start-options { display: flex; flex-wrap: wrap; gap: 0.6rem; margin-top: 0.25rem; }
  .booking-form .start-options label { font-weight: 600; display: flex; align-items: center; gap: 0.45rem; margin: 0; padding: 0.55rem 1rem; border: 2px solid #C4704B; border-radius: 999px; color: #C4704B; cursor: pointer; }
  .booking-form .start-options input { accent-color: #C4704B; }
  .booking-form .start-options label:has(input:checked) { background: #C4704B; color: #fff; }
  .booking-form .start-options label:has(input:checked) input { accent-color: #fff; }
  @media (max-width: 480px) { .booking-form .check-grid { grid-template-columns: 1fr; } }
</style>

<form class="booking-form" action="https://formsubmit.co/petcare@houseofguineas.com" method="POST">
  <!-- FormSubmit config -->
  <input type="hidden" name="_subject" value="New care request from houseofguineas.com">
  <input type="hidden" name="_template" value="table">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_next" value="https://houseofguineas.com/thank-you/">

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
      <optgroup label="Routine care — standing visits">
        <option value="Routine: Cleaning (weekly)">Cleaning (Deep Clean or Upkeep), weekly — from $105/visit</option>
        <option value="Routine: Cleaning (every other week)">Cleaning (Deep Clean or Upkeep), every other week — from $115/visit</option>
        <option value="Routine: Nail Trims (every other week)">Nail Trims, every other week — from $115/visit</option>
        <option value="Routine: not sure which plan">Routine care — help me pick a plan</option>
      </optgroup>
      <optgroup label="Care while you're away">
        <option value="Travel / vacation care">In-home care while I travel — from $85/visit</option>
        <option value="Boarding">Boarding, for families outside SF — $125/night</option>
      </optgroup>
      <option value="Not sure yet">Not sure yet — help me decide</option>
    </select>
    <p class="form-note" id="routine-note" style="display:none;">Visits start at <strong>$105</strong> weekly or <strong>$115</strong> every other week — tell us below if you'd like a Deep Clean, Upkeep, or a mix, and we'll fine-tune it at your free meet-and-greet.</p>
    <p class="form-note" id="travel-note" style="display:none;">While you're away, we come to your pet's own home: <strong>$85</strong> for a 30-minute visit, <strong>$125</strong> for a full hour, or twice-daily care at <strong>$155–$215/day</strong> depending on visit lengths. There's no travel surcharge anywhere in San Francisco; farther out, visits add $15–$25 each depending on distance. See the <a href="/home/services/exotic-pet-care-services-in-home/">in-home care page</a> for the full rate card.</p>
    <p class="form-note" id="boarding-note" style="display:none;">Heads up: boarding is <strong>$125/night</strong>, spots are limited, and we <strong>reserve them for pet parents outside San Francisco</strong> — Peninsula and Marin families, where in-home visits add a travel surcharge, get priority, and the farther you are the more welcome you are to ask. If you live in San Francisco, in-home care is the better fit: no travel surcharge anywhere in the city, far more availability, and your little ones stay in the home they know. Please <a href="tel:415-484-6493">call or text us</a> as early as you can to check availability.</p>
  </div>

  <script>
    document.getElementById('service').addEventListener('change', function () {
      var noteByService = {
        'Travel / vacation care': 'travel-note',
        'Boarding': 'boarding-note'
      };
      ['routine-note', 'travel-note', 'boarding-note'].forEach(function (id) {
        document.getElementById(id).style.display = 'none';
      });
      var noteId = this.value.indexOf('Routine:') === 0 ? 'routine-note' : noteByService[this.value];
      if (noteId) document.getElementById(noteId).style.display = 'block';
    });

    // Arriving from the routine care page (/book/?care=routine): show only the routine options.
    if (new URLSearchParams(window.location.search).get('care') === 'routine') {
      var select = document.getElementById('service');
      Array.prototype.slice.call(select.options).forEach(function (opt) {
        if (opt.value && opt.value.indexOf('Routine:') !== 0) opt.remove();
      });
      Array.prototype.slice.call(select.querySelectorAll('optgroup')).forEach(function (group) {
        if (!group.children.length) group.remove();
      });
      document.getElementById('routine-note').style.display = 'block';
    }
  </script>

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
    <p class="form-note" id="nail-trim-note" style="display:none;"></p>
  </div>

  <script>
    (function () {
      var service = document.getElementById('service');
      var note = document.getElementById('nail-trim-note');
      var noTrim = { 'Bird': 'birds', 'Ferret': 'ferrets', 'Cat': 'cats' };
      function update() {
        var picked = Array.prototype.slice.call(document.querySelectorAll('input[name="pets"]:checked'))
          .map(function (box) { return noTrim[box.value]; })
          .filter(Boolean);
        if (service.value.indexOf('Nail Trims') === -1 || !picked.length) {
          note.style.display = 'none';
          return;
        }
        var list = picked.length === 1 ? picked[0]
          : picked.slice(0, -1).join(', ') + (picked.length > 2 ? ',' : '') + ' or ' + picked[picked.length - 1];
        note.textContent = "We don't offer nail trims for " + list + " at this time, but we can absolutely help support you with maintaining their husbandry!";
        note.style.display = 'block';
      }
      service.addEventListener('change', update);
      Array.prototype.slice.call(document.querySelectorAll('input[name="pets"]')).forEach(function (box) {
        box.addEventListener('change', update);
      });
    })();
  </script>

  <div class="form-row" id="routine-start" style="display:none;">
    <fieldset>
      <legend>Ready to get your evenings back? Pick your start:</legend>
      <div class="start-options">
        <label><input type="radio" name="routine_start" value="This week"> This week</label>
        <label><input type="radio" name="routine_start" value="Next week"> Next week</label>
      </div>
      <p class="form-note">We'll confirm your free meet-and-greet and schedule your first visit so we can get started right away!</p>
    </fieldset>
  </div>

  <div class="form-row">
    <label for="dates" id="dates-label">Dates or schedule</label>
    <input type="text" id="dates" name="dates" placeholder="e.g. weekly Tuesdays, or Aug 4–11">
  </div>

  <script>
    (function () {
      var service = document.getElementById('service');
      var start = document.getElementById('routine-start');
      var label = document.getElementById('dates-label');
      var dates = document.getElementById('dates');
      function update() {
        var routine = service.value.indexOf('Routine:') === 0 ||
          new URLSearchParams(window.location.search).get('care') === 'routine';
        start.style.display = routine ? 'block' : 'none';
        label.textContent = routine ? 'Preferred day(s) and time' : 'Dates or schedule';
        dates.placeholder = routine ? 'e.g. Tuesday or Thursday evenings' : 'e.g. weekly Tuesdays, or Aug 4–11';
      }
      service.addEventListener('change', update);
      update();
    })();
  </script>

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
