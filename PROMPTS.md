# DevConf 2026 - FAQ Section Discussion

---

**User:** I am building a landing page for DevConf 2026, a developer conference featuring prominent speakers from the AI and tech industry. The page currently has a navbar, hero section, speakers section, pricing section, and footer. I need you to suggest a new section to add between the pricing section and the footer. The section should be relevant to a developer conference. Here are some ideas but feel free to suggest your own:

- Sponsors
- Venue details
- FAQ
- Newsletter signup
- Hackathon details
- Past event highlights
- Job board
- Conference schedule/agenda

Please suggest 2 to 3 options with a short explanation of why each one would work well for this type of website. Then I will pick one and we will build it together.

---

**Assistant:** Great question! Here are my top 3 suggestions:

**1. FAQ (Frequently Asked Questions)**
This is almost essential for any conference landing page. Visitors always have questions like "Where is the venue?", "Is it online or in person?", "Can I get a refund?". Having a FAQ section reduces friction and helps people make the decision to register. It fits naturally after pricing because people read the prices and immediately have questions.

**2. Conference Schedule / Agenda**
This is probably the most valuable section for a dev conference. People want to know what talks are happening, what time, and which speakers are presenting when. It directly supports the "Register Now" call to action because seeing an exciting schedule convinces people to buy a ticket.

**3. Newsletter Signup**
Simple but very effective. Not everyone is ready to buy a ticket right away. A newsletter signup captures those visitors with something like "Stay updated on speaker announcements and early bird deals". It is a low commitment ask that keeps potential attendees engaged.

My personal recommendation is FAQ because:
- It is quick to build cleanly
- It directly follows the pricing section which is where people have the most doubts
- It does not require extra assets or data

---

**User:** Ok go for FAQ section. You can come up with questions and answers. Only using HTML and CSS.

---

**Assistant:** So that means click to expand using `<details>` and `<summary>` tags since it only needs HTML and CSS, no JavaScript.

---

**User:** Do we need images? If so what should I search for?

---

**Assistant:** No, we don't need any images for the FAQ section! It is purely text based. Just questions and answers, clean and simple.

---

**User:** Yes, go ahead and write the code.

---

**Assistant:** Here are the FAQ questions and answers used in the section:

**Q: When and where is DevConf 2026 taking place?**
A: DevConf 2026 will be held on September 18-20, 2026 at the San Francisco Convention Center, San Francisco, California.

**Q: Is the conference available online?**
A: Yes! All keynotes and main stage talks will be live streamed. Pro and Team ticket holders also get lifetime access to all session recordings.

**Q: What is the refund policy?**
A: Full refunds are available up to 30 days before the event. After that, tickets can be transferred to another person but are non-refundable.

**Q: Are meals included in the ticket price?**
A: Standard and Pro tickets include networking lunch and coffee breaks on all three days. Pro ticket holders also get access to the VIP networking dinner.

**Q: Can I switch my ticket type after purchasing?**
A: Yes, you can upgrade your ticket at any time before the event by paying the difference. Downgrades are not permitted after purchase.

**Q: Is there a discount for students or groups?**
A: Yes! Students get a 40% discount with a valid student ID. For groups of 5 or more, please contact us directly for special pricing.