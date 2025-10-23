INSTALL & USAGE
1) Replace phonepe_qr.png with your actual PhonePe QR image (filename must match).
2) Upload index.html, style.css, phonepe_qr.png to your GitHub Pages repo root.
3) Flow:
   - Buyer scans QR and taps 'I PAID' (this sets payment request flag)
   - Seller clicks 'Seller: Confirm Payment' and enters pass '8989' to verify
   - After verification the Login (auto) screen appears and buyer taps 'Access Panel'
   - WhatsApp number is shown
Note: This is a client-side simulation. For real auto-verification use a payment gateway + server webhook.
