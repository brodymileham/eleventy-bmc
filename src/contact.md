---
title: 'Contact us'
layout: 'layouts/page.html'
---

<form id="signupForm" action="/" class="[ signup__form ] [ flow ]" method="POST">
  <label for="name">Name</label>
  <div class="inline-field-control">
    <input
      type="text"
      name="name"
      id="name"
      autocapitalize="none"
      autocorrect="off"
      required"
    />
  </div>
  <label for="email">Email address</label>
  <div class="inline-field-control">
    <input
      type="email"
      name="email"
      id="email"
      autocapitalize="none"
      autocorrect="off"
      required
      pattern="[^@]+@[^\.]+\..+"
    />
  </div>
  <label for="message">Message</label>
  <div class="inline-field-control">
    <input
      type="text"
      name="message"
      id="message"
      autocapitalize="none"
      autocorrect="off"
      required"
    />
  </div>
  <button type="submit" class="button">
      <span class="visually-hidden">Submit email</span>Submit
      </button>
</form>
<div aria-atomic="true" role="alert" class="signup__alert"></div>

