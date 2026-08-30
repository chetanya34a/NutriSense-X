NutriSense X — REAL FOOD POSITION FIX

Root cause fixed:
The Healthy Food Library section was outside the .main container while the sidebar was fixed.
Therefore it started from the full page's left edge and rendered underneath the sidebar.

This version explicitly reserves sidebar width for the body-level Food Library:
Desktop: 255px
Tablet: 72px
Mobile: 0px
