# Shane Foster - Portfolio Website

The modeling and acting portfolio of Shane Foster.

## Website Structure

This is a 2-page portfolio website:

### Page 1: Social Media Links (index.html)
- Clean, modern landing page with links to all social media profiles
- Features profile photo and name
- Includes a prominent link to the portfolio page
- Social media platforms included:
  - Instagram
  - Twitter
  - LinkedIn
  - TikTok
  - YouTube
  - Email contact

### Page 2: Portfolio (portfolio.html)
- Professional portfolio showcasing Shane Foster
- About section with bio and background information
- Gallery with 6 placeholder images for portfolio photos
- Statistics section highlighting experience
- Call-to-action section for collaboration inquiries

## Customization

To customize the website for your needs:

1. **Replace placeholder images**: 
   - Replace images in the `/images` folder with actual photos
   - Keep the same filenames or update references in HTML
   - Recommended: profile.jpg (400x400px), photo1-6.jpg (600x800px)

2. **Update social media links**:
   - Edit `index.html` and replace the placeholder URLs with actual social media profile links
   - Update the email address from `contact@example.com` to your actual email

3. **Customize bio and content**:
   - Edit `portfolio.html` to update the "About Me" section with your actual bio
   - Update statistics (years experience, projects completed, etc.)
   - Modify gallery overlay text to describe your actual work

4. **Adjust styling**:
   - Edit `styles.css` to change colors, fonts, or layout
   - Current color scheme uses purple/blue gradients - easily customizable

## Deployment

To deploy this website:

1. **GitHub Pages**: 
   - Go to repository Settings > Pages
   - Under "Build and deployment":
     - Source: Select "Deploy from a branch"
     - Branch: Select "main" (or your default branch) and "/ (root)"
     - Click "Save"
   - Wait a few minutes for the site to build
   - Your site will be available at `https://op-era.github.io/ShaneFoster/`
   - Note: The `.nojekyll` file is included to ensure the static HTML files are served correctly without Jekyll processing

2. **Other hosting**: Upload all files (HTML, CSS, images folder) to any web host

## Technologies Used

- Pure HTML5
- CSS3 with modern features (Grid, Flexbox, animations)
- Responsive design for mobile and desktop
- No JavaScript required - fast and lightweight
