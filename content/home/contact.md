+++
# Contact widget.
widget = "contact"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight =8 # Order that this section will appear.

title = "Contact"
subtitle = ""

# Automatically link email and phone?
autolink = true

# Email form provider
#   0: Disable email form
#   1: Netlify (requires that the site is hosted by Netlify)
#   2: formspree.io

+++


<!-- modify this form HTML and place wherever you want your form -->



<form
  action="https://formspree.io/f/myybqzpz"
  method="POST"
>
  <label>
    Your email:
    <input type="text" name="_replyto">
  </label>
  <label>
    Your message:
    <textarea rows = "5" cols = "60" name="message"></textarea>
  </label>

  <!-- your other form fields go here -->

  <button type="submit">Send</button>
  
</form>




