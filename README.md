# NXY Capital Website

This is the official website for NXY Capital, built with HTML and CSS.

## Deployment Instructions

1. Create a new repository on GitHub named `nxycapital.com`
2. Push this code to the repository
3. Go to repository Settings > Pages
4. Under "Source", select "main" branch
5. Under "Custom domain", enter `nxycapital.com`
6. Click Save
7. Add these DNS records at your domain registrar:
   ```
   Type: A
   Name: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153

   Type: CNAME
   Name: www
   Value: yourusername.github.io
   ```

8. Wait for DNS propagation (can take up to 24 hours)

## Local Development

To test the website locally, you can use Python's built-in HTTP server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.
