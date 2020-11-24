SHIPLIFY EMAILS!
===============

Templates Included:
---------------
- `default` - Standard transactional email with no buttons
- `default_1_button` - Standard transactional email with 1 button
- `default_2_button` - Standard transactional email with 2 buttons
- `flag` - Flag update email with all update types included ("kitchen sink")
- `flag_no_comment` - Same as flag, but without a comment included
- `flag_no_issues` - Flag update email where there were zero updates made

Things to Know:
---------------
1. Before using, move all images in the "images" subdirectory to a web-accessible location, and update MJML/template links.
2. You will notice this repo has both .mjml and .html files. The HTML templates were output created by MJML. If you want a less cumbersome way to edit these email templates, head to [MJML.io](https://mjml.io)
3. These templates have been cross-platform tested with 56 different email clients. EDIT NON-TEXT ELEMENTS WITH CARE!
4. For map/pin images, use a 350 ✕ 350 pixel image (it will be scaled down to 175 ✕ 175).
5. Note that there is a zero-length joiner (&zlj;) in front of the "Pro #" in the code. This is intentional! It will prevent iOS from auto-linking it as a telephone number.

Questions?
---------------
Email [Martin Parets](martin@armyofbees.com)