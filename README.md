# LOOPIN New
1. Supabase SQL editor: run supabase/schema.sql (first time only), then supabase/upgrade.sql.
2. Auth > Email Templates: in "Confirm signup" and "Reset password" replace the body with: Your LOOPIN code is {{ .Token }}
3. Make yourself admin (SQL editor): update profiles set role='admin' where id=(select id from auth.users where email='YOUR EMAIL');
4. Put URL + anon key in config.js (already filled). Push to GitHub, deploy on Netlify (publish dir ".").
