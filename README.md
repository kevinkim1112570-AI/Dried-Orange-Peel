# 橙皮 Stock List

Single-page liquid stock register (Code, Name, Weight, Particular Year, Place of Stock, Detail, Pic) with live team data in Supabase.

- Table: `public.orange_peel_stock` (codes OP001, OP002… are assigned by a database trigger)
- Access: team sign-in (Supabase Auth) with Create Account (email confirmation required) and an Admin page. New confirmed accounts are Read Only; the Admin sets Edit Access, resets passwords or removes accounts. Roles live in `orange_members`; every add, edit and delete is logged to `orange_peel_log` and shown on the Record page; the admin password is checked server-side.
- Items saved in the old local-storage version are offered for one-time upload after sign-in.

## Deploy on Vercel
Import this repo, Framework Preset **Other**, leave Build Command and Output Directory empty, Deploy.
