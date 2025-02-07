---
title: "Chapter Director Application"
description: "Apply to become a Chapter Director of an existing chapter or start a new chapter."
image: "/assets/img/support-us/chapter-director/chapter-director-application.jpg"
noTimeEstimate: true
hideImage: true
aliases:
  - /chapter-director-application/
  - /support-us/chapter-director/application/
  - /support-us/chapter-director/chapter-director-application/
---

<form name="Become a Chapter Director" method="POST" data-netlify-recaptcha="true" data-netlify="true" action="/success/chapter-director/" class="form--centered mt-2 no-ids" id="form_become_a_member">
  <input type="hidden" aria-label="Subject" name="_subject" value="Techqueria - Become a Chapter Director">
  {{< fields/name help="Please include your first name and last name. Make sure to capitalize your name." >}}
  {{< fields/email help="Please use a personal email address to avoid being locked out if you lose access to your work or school email. Make sure to check for typos in your email." >}}
  {{< fields/organization label="Where do you currently work or study?" >}}
  {{< fields/title label="What is your current role?" help="e.g. Software Engineer, Recruiter, Product Designer, Student, etc." >}}
  {{< fields/linkedin >}}
  {{< fields/new_chapter >}}
  {{< fields/yes_no label="Are you at least 21 years old?" help="This is a hard requirement as our events may have alcohol." required="true" name="age_chapter_director" >}}
  {{< fields/yes_no label="Do you have at least 3 years of professional experience in tech?" help="This is a requirement but we may be flexible with this depending on your other answers." required="true" name="yoe_chapter_director" >}}
  {{< fields/yes_no label="Can you commit to holding at least 2 events or more per year?" help="This is a hard requirement." required="true" name="events_per_year" >}}
  {{< fields/yes_no label="Have you read through the Reimbursement Guidelines and Chapter Tiers documentation?" help="We will cover this in the onboarding session as well." required="true" name="read_documentation" >}}
  {{< fields/message label="Why do you want to start or lead a Techqueria chapter?" placeholder="" name="why_lead_techqueria_chapter" required="true" >}}
  {{< fields/message label="What would be the topic of your first event?" placeholder="" name="topic_of_first_event" required="true" >}}
  {{< fields/message label="Do you have past experience hosting events or building communities?" placeholder="" name="past_community_building_experience" required="true" >}}
  {{< fields/message label="Each city chapter has their own Slack channel and email newsletter you can maintain. How would you keep your community engaged between in-person events?" placeholder="" name="community_engagement_between_events" required="true" >}}
  {{< fields/message label="What excites you most about potentially leading a Techqueria Chapter?" placeholder="" name="excites_most_techqueria_chapter" required="true" >}}
  {{< fields/message label="Anything else you want to add or share with us?" placeholder="" name="add_anything_else">}}
  {{< fields/referral >}}
  {{< fields/coc >}}
  {{< fields/submit label="SUBMIT APPLICATION" classes="button is-primary is-large is-fullwidth is-size-5 has-text-weight-semibold" >}}
</form>
