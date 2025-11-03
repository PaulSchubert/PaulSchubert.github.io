# Setup Checklist

## Before Publishing

1. **Install dependencies locally** (for preview):
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
   Then visit http://localhost:4000 to preview

2. **GitHub Pages Configuration**:
   - Go to Settings → Pages in your GitHub repository
   - Source: Deploy from a branch
   - Branch: main / root
   - Save

3. **Test the build** (optional):
   ```bash
   bundle exec jekyll build
   ```

## Content to Add Later

- [ ] Replace `assets/img/prof_pic.jpg` with your photo
- [ ] Update `_pages/about.md` with your bio
- [ ] Add publications to `_bibliography/papers.bib`
- [ ] Add real projects to `_projects/`
- [ ] Write blog posts in `_posts/`
- [ ] Update CV details in `_data/cv.yml`
- [ ] Add your social media links in `_config.yml`
- [ ] Customize theme colors in `_sass/_themes.scss`

## Notes

- Site will be available at https://PaulSchubert.github.io after GitHub Pages is enabled
- First deployment may take 10-20 minutes
- The theme supports dark mode automatically
- You can add Google Analytics later by updating `_config.yml`