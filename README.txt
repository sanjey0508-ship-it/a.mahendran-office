A. Mahendran Auditor Office – website files

PUBLISH (free): drag this whole folder into https://app.netlify.com/drop  (or use GitHub Pages / Vercel).
Keep logo.webp in the same folder as the .html files.

EDIT LATER: open any .html file in a text editor.
- Phone / WhatsApp / Maps link: top of the <script> at the bottom (CFG), and the contact text in contact.html and the footer.
- Services, FAQs, 'Why choose us' points: the lists SERVICES / WHY / FAQS in the same script block.
- Replace the photo placeholder in about.html with a real office photo.
- After going live, add your real domain to each page title/canonical and submit the site in Google Search Console.

SETTINGS (top of the <script> in each page, the CFG line)
- upiId: office UPI ID, e.g. "name@bank". QR + Pay button on fees.html appear automatically once set.
- formEndpoint: Formspree URL (https://formspree.io/f/xxxx) so enquiries also reach the office email.
- announce: one-line banner shown at top of every page (e.g. holiday notice). Leave "" to hide.
Set the same values in every page (search for "var CFG=").
