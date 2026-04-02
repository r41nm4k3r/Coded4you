---
title: "Send Us A Message"
subtitle: "We'd love to hear from you."
type: "page"
layout: "contact"
---
<form class="contact-form" action="#" method="POST" style="display: flex; flex-direction: column; gap: 1rem;">
  <div style="display: flex; gap: 1rem;">
    <input type="text" placeholder="First Name" style="flex:1; padding: 0.8rem; border-radius: 4px; border: 1px solid #ccc; background-color: var(--bg-light); color: var(--text-dark);">
    <input type="text" placeholder="Last Name" style="flex:1; padding: 0.8rem; border-radius: 4px; border: 1px solid #ccc; background-color: var(--bg-light); color: var(--text-dark);">
  </div>
  <input type="email" placeholder="Email Address" required style="padding: 0.8rem; border-radius: 4px; border: 1px solid #ccc; background-color: var(--bg-light); color: var(--text-dark);">
  <input type="tel" placeholder="Phone Number" style="padding: 0.8rem; border-radius: 4px; border: 1px solid #ccc; background-color: var(--bg-light); color: var(--text-dark);">
  <textarea placeholder="Message" rows="5" required style="padding: 0.8rem; border-radius: 4px; border: 1px solid #ccc; background-color: var(--bg-light); color: var(--text-dark);"></textarea>
  <button type="submit" class="cta-button" style="border: none; cursor: pointer; align-self: flex-start;">Send Message</button>
</form>
