TOP IMAGE HUB V5

PUBLIC SITE:
index.html
Public visitors only see: Home | Editor | About
No login button, no admin button.

SECRET ADMIN PAGE:
admin.html
Example after deploy:
https://your-domain.vercel.app/admin.html

SETUP:
1. Create Supabase project.
2. Run the SQL setup from V4's supabase-setup.sql.
3. Create public Storage bucket named gallery-images.
4. Put the SAME Supabase URL and anon key in BOTH index.html and admin.html.
5. Create your admin Email/Password in Supabase Authentication.
6. Deploy both files to Vercel.

IMPORTANT:
Do not publish/admin-link admin.html from the public menu.
For stronger security, add an admin email allowlist policy in Supabase before production.
