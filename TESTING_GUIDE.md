# Testing Guide - Crown Dental Store

## How to Test All Changes

### 1. Test Product Display
1. Open `products.html` or `index.html`
2. Verify products show images from category folders
3. Check that each product has only ONE image
4. Verify "Add to Cart" buttons appear (not "Order Now")

### 2. Test Shopping Cart
1. Click "Add to Cart" on any product
2. Adjust quantity using +/- buttons before adding
3. Should redirect to `cart.html`
4. Verify product appears in cart with correct quantity
5. Test quantity adjustment in cart
6. Test removing items
7. Verify total calculations are correct

### 3. Test Cart Icon
1. Look for floating cart icon (🛒) on left side
2. Should show badge with item count
3. Click icon - should go to cart page
4. Badge should update when adding/removing items

### 4. Test WhatsApp Integration
1. Click floating WhatsApp button (green)
2. Should open WhatsApp with number: +20 102 826 0186
3. In cart, click "Order Now via WhatsApp"
4. Verify formatted order message opens in WhatsApp

### 5. Test Call Us Feature
1. Click "Call Us" button anywhere on site
2. Should show prompt with 3 phone numbers:
   - +20 102 826 0186
   - +20 155 655 5784
   - +20 155 655 5784
3. Select a number - should initiate call

### 6. Test Contact Form
1. Go to `about-contact.html`
2. Fill out contact form (no email field should be visible)
3. Click "Send via WhatsApp"
4. Should open WhatsApp with formatted message

### 7. Test Floating Buttons
From bottom to top on left side:
1. 📍 Blue - Location/Directions
2. 🛒 Orange - Shopping Cart
3. 💬 Green - WhatsApp

All should be visible and clickable.

### 8. Test Mobile Responsiveness
1. Open site on mobile or resize browser to mobile width
2. Verify:
   - Navbar collapses properly
   - Cart displays in single column
   - Buttons are touch-friendly
   - Floating buttons positioned correctly
   - WhatsApp button may hide on very small screens

### 9. Test No Email References
1. Search all pages for email mentions
2. Verify no "info@crowndentalstore.com" appears
3. Check footer has only Phone, WhatsApp, and Location

### 10. Test Product Categories
1. Verify Consumables products use images from `/images/categories/Consumbles/`
2. Verify Restorative products use images from `/images/categories/Restorative/`
3. All images should load correctly

## Quick Check List

- [ ] Cart icon visible and functional
- [ ] Add to Cart buttons work
- [ ] Cart page displays correctly
- [ ] Order via WhatsApp works
- [ ] Call Us shows 3 numbers
- [ ] No email references anywhere
- [ ] WhatsApp number is +20 102 826 0186
- [ ] Floating buttons all work
- [ ] Mobile responsive
- [ ] Products use category folder images
- [ ] Contact form sends to WhatsApp

## Common Issues & Solutions

### Cart icon not showing
- Clear browser cache
- Check browser console for errors
- Verify cart.js is loaded

### Add to Cart not working
- Verify cart.js is included in page
- Check browser localStorage is enabled
- Clear localStorage and try again

### WhatsApp not opening
- On desktop, WhatsApp Web may be blocked
- Try on mobile device
- Check number format in code (should be 201028260186)

### Images not loading
- Verify image files exist in category folders
- Check file names match exactly (case-sensitive)
- Check image file extensions

## Browser Testing
Test on:
- [ ] Chrome/Edge (Windows)
- [ ] Firefox (Windows)
- [ ] Safari (Mac/iPhone)
- [ ] Chrome (Android)

## Final Verification
After testing, verify:
1. All functionality works as expected
2. No console errors
3. Site loads quickly
4. All links work
5. Mobile experience is smooth
6. Cart persists across page refreshes

---

**If any issues are found, check:**
1. Browser console for JavaScript errors
2. Network tab for failed requests
3. localStorage in browser dev tools
4. File paths are correct and case-sensitive
