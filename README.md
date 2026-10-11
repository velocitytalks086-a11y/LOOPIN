# LOOPIN (starter)
Static site + Supabase backend. Deploy to Netlify: drag this folder/zip onto app.netlify.com/drop.
1. Create a Supabase project. 2. SQL editor: run supabase/schema.sql. 3. Auth > URL config: add your Netlify URL as Site URL/redirect. 4. Put Project URL + anon key in config.js. 5. Redeploy.
Never put the service-role key in this project.
Included: landing page, email/password auth + verification + reset, requests (create/search/filter/respond/close), offers (create/search/pause), RLS policies.
Not yet built: messaging, matching, exchanges, communities, reputation, notifications, admin portal, uploads, PWA manifest, tests.
