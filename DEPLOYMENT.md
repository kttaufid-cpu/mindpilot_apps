# Deployment Guide: Vercel + Supabase

## 1. Setup Supabase (Database)

1.  Go to [Supabase.com](https://supabase.com) and create a new project.
2.  Go to **SQL Editor** in your Supabase dashboard.
3.  Copy the content of `supabase/schema.sql` from this repository and run it to create the tables.
4.  Go to **Project Settings -> API** and copy:
    *   Project URL (`NEXT_PUBLIC_SUPABASE_URL`)
    *   `anon` public key (`NEXT_PUBLIC_SUPABASE_ANON_KEY`)

## 2. Deploy to Vercel (Server)

1.  Push your code to a GitHub repository.
2.  Go to [Vercel.com](https://vercel.com) and import your repository.
3.  In the **Environment Variables** section, add the keys from Supabase:
    *   `NEXT_PUBLIC_SUPABASE_URL`
    *   `NEXT_PUBLIC_SUPABASE_ANON_KEY`
4.  Click **Deploy**.

## 3. Self-Hosting (Docker)

If you prefer to run it yourself (without Vercel/Supabase cloud):

1.  Uncomment `output: 'standalone'` in `next.config.mjs`.
2.  Build the Docker image:
    ```bash
    docker build -t mindpilot-ai .
    ```
3.  Run it:
    ```bash
    docker run -p 3000:3000 mindpilot-ai
    ```
