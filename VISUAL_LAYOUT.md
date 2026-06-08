# Visual Layout Guide - Crown Dental Store

## Floating Action Buttons Layout

```
┌─────────────────────────────────────┐
│                                     │
│  Navbar: Logo | Menu | Social Icons│
│                                     │
├─────────────────────────────────────┤
│                                     │
│           Main Content              │
│                                     │
│         [Product Cards]             │
│                                     │
│    [Add to Cart] [View Details]    │
│                                     │
│                                     │
│                                     │
└─────────────────────────────────────┘
           │
           │ LEFT SIDE BUTTONS:
           │
           ├─ 💬 WhatsApp (Green)
           │  Top button
           │  52x52px
           │  Link: +20 102 826 0186
           │
           ├─ 🛒 Cart (Orange)
           │  Middle button
           │  52x52px
           │  Badge: Item count
           │  Link: cart.html
           │
           └─ 📍 Location (Blue)
              Bottom button
              52x52px
              Link: Google Maps
```

---

## Cart Page Layout

### Desktop View:
```
┌─────────────────────────────────────────────────────┐
│  Home > Shopping Cart                               │
├───────────────────────────┬─────────────────────────┤
│                           │                         │
│   CART ITEMS              │   ORDER SUMMARY        │
│                           │                         │
│  ┌─────────────────────┐  │   Subtotal: 1,500 EGP │
│  │ [Image] Product 1   │  │   Total:    1,500 EGP │
│  │ Price: 500 EGP      │  │                         │
│  │ [-] 2 [+]  Remove   │  │   [Order Now via       │
│  │ Subtotal: 1,000 EGP │  │    WhatsApp 💬]        │
│  └─────────────────────┘  │                         │
│                           │   [Continue Shopping]  │
│  ┌─────────────────────┐  │                         │
│  │ [Image] Product 2   │  │                         │
│  │ Price: 500 EGP      │  │                         │
│  │ [-] 1 [+]  Remove   │  │                         │
│  │ Subtotal: 500 EGP   │  │                         │
│  └─────────────────────┘  │                         │
│                           │                         │
└───────────────────────────┴─────────────────────────┘
```

### Mobile View:
```
┌─────────────────────┐
│ Order Summary       │
│ Total: 1,500 EGP   │
│ [Order Now 💬]     │
│ [Continue Shop]    │
├─────────────────────┤
│ CART ITEMS         │
│                    │
│ ┌───────────────┐  │
│ │   [Image]     │  │
│ │  Product 1    │  │
│ │  500 EGP      │  │
│ │  [-] 2 [+]    │  │
│ │  [Remove 🗑️]  │  │
│ └───────────────┘  │
│                    │
│ ┌───────────────┐  │
│ │   [Image]     │  │
│ │  Product 2    │  │
│ │  500 EGP      │  │
│ │  [-] 1 [+]    │  │
│ │  [Remove 🗑️]  │  │
│ └───────────────┘  │
└─────────────────────┘
```

---

## Contact Methods Layout

```
┌────────────────────────────────────────────────┐
│           ABOUT & CONTACT US                   │
├────────────┬────────────┬─────────────────────┤
│            │            │                      │
│    📞      │     💬     │         📍          │
│   Phone    │  WhatsApp  │      Location       │
│            │            │                      │
│ [Call Us]  │ [Contact]  │  [Get Directions]   │
│            │            │                      │
│  Shows 3   │  +20 102   │   Mansoura, Egypt   │
│  numbers   │  826 0186  │                      │
│            │            │                      │
└────────────┴────────────┴─────────────────────┘
```

---

## Product Card Layout

```
┌─────────────────────────┐
│      [Product Image]    │  ← Single image from category folder
│      📦 Badge           │
├─────────────────────────┤
│  Category: Consumables  │
│  Product Name           │
│  1,200 EGP             │
│  ✓ In Stock            │
│                         │
│  Quantity: [-] 1 [+]   │  ← Quantity selector
│                         │
│  [View Details]         │
│  [Add to Cart]          │  ← Changed from "Order Now"
└─────────────────────────┘
```

---

## WhatsApp Order Message Format

```
🛒 *New Order from Crown Dental Store*

*Order Details:*
━━━━━━━━━━━━━━━━━━━━

1. *Nitrile Gloves*
   • Category: Consumables
   • Price: 390 EGP
   • Quantity: 2
   • Subtotal: 780 EGP

2. *Composite 3M Z250*
   • Category: Restorative
   • Price: 1850 EGP
   • Quantity: 1
   • Subtotal: 1850 EGP

━━━━━━━━━━━━━━━━━━━━
*Total Amount: 2630 EGP*

Please confirm this order and provide delivery details.
```

---

## Call Options Prompt

```
┌──────────────────────────────────────┐
│  Choose a phone number to call:     │
│                                      │
│  1. Primary: +20 102 826 0186       │
│  2. Secondary 1: +20 155 655 5784   │
│  3. Secondary 2: +20 155 655 5784   │
│                                      │
│  Enter 1, 2, or 3:                  │
│  [___]                               │
└──────────────────────────────────────┘
```

---

## Footer Layout (Home Page)

```
┌─────────────────────────────────────────────────────────┐
│  Crown Dental Store  │  Quick Links  │    Contact      │
│                      │               │                  │
│  Premium dental      │  • Home       │  📞 [Call Us]   │
│  tools & supplies    │  • Products   │  💬 WhatsApp    │
│                      │  • Categories │  📍 Mansoura    │
│                      │  • About      │                  │
├─────────────────────────────────────────────────────────┤
│          Crown Dental Store 2026©                       │
└─────────────────────────────────────────────────────────┘
```

---

## Color Scheme

```
PRIMARY:    #0056B3 (Medical Blue)
SECONDARY:  #17A2B8 (Teal)
SUCCESS:    #28A745 (Green) - WhatsApp
DANGER:     #DC3545 (Red) - Badge
WARNING:    #FFC107 (Yellow)
CART:       #FF6B35-#F7931E (Orange Gradient)

FLOATING BUTTONS:
- Location:  Blue Gradient (#0056B3 → #17A2B8)
- Cart:      Orange Gradient (#FF6B35 → #F7931E)
- WhatsApp:  Green Gradient (#25D366 → #128C7E)
```

---

## Responsive Breakpoints

```
Mobile Small:   ≤320px  (Compact)
Mobile:         ≤480px  (Optimized)
Tablet:         ≤768px  (Adjusted)
Desktop:        ≥1200px (Full)
Large Desktop:  ≥1440px (Expanded)
```

---

## Button Sizes

```
Desktop:
- Floating Buttons: 52x52px
- Regular Buttons: 44px height minimum
- Small Buttons: 34px height

Mobile:
- Floating Buttons: 46-50px
- Touch Targets: 44px minimum (iOS standard)
- Card Buttons: 30-34px
```

---

## Typography Scale

```
Hero Title:       2.25rem (36px)
Section Title:    1.875rem (30px)
Card Title:       1.125rem (18px)
Body:             1rem (16px)
Small Text:       0.875rem (14px)
Tiny Text:        0.75rem (12px)
```

---

This visual guide shows the professional layout and structure of all implemented changes!
