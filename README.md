# vercel-bug-reproducible-steps
Hey y'all, after your recent update (which I was notified wouldn't affect my running functions) I started getting 504 on my revalidate workflow. The revalidate endpoint runs within 15s. But your revalidation API (HEAD requests) timeout after 15s. I think I might need to set it to 40 or 45. Can you please help me with that?
