# VIP Shop BD — Supabase Store

Mobile-first e-commerce website connected to the existing Supabase project `md rayhan`.

## Included
- VIP/app plans + fashion/borka/men/women/electronics/other products
- Product search and categories
- Cart + checkout
- Email/password auth
- Google OAuth button (enable Google provider in Supabase Auth)
- bKash/Nagad payment method selection
- Customer order history
- Admin product add/edit/soft-delete
- Responsive mobile bottom navigation
- GitHub Pages compatible static files

## Admin
Set a user's `profiles.role` to `admin` in Supabase. Then log in and open Account → Admin Panel.

## Deploy on GitHub Pages
Upload all files to a repository. No build step is required. Open `index.html` through GitHub Pages.

## Important
The frontend uses the Supabase publishable key. This is intended for browser use; security is enforced by Supabase RLS policies. Do not put a service-role key in the frontend.
