# 橙皮 Stock List

Single-page liquid stock register (Code, Name, Weight, Particular Year, Place of Stock, Detail, Pic) with live team data in Supabase.

- Table: `public.orange_peel_stock` (codes OP001, OP002… are assigned by a database trigger)
- Access: team sign-in (Supabase Auth). Everyone in `app_user_roles` can view; only users with `can_edit = true` can add, edit or delete.
- Items saved in the old local-storage version are offered for one-time upload after sign-in.

## Deploy on Vercel
Import this repo, Framework Preset **Other**, leave Build Command and Output Directory empty, Deploy.
