# How to Add Your Project Images

## Step 1: Prepare Your Images
1. Create screenshots or images of your projects
2. Recommended size: **600x400 pixels** or similar aspect ratio (3:2)
3. Save them as JPG or PNG files

## Step 2: Add Images to the Folder
1. Put your project images in the `images` folder
2. Name them: `project1.jpg`, `project2.jpg`, `project3.jpg`, etc.

## Step 3: Update the Links
In `port.html`, change the `href="#"` to your actual project URLs:

```html
<a href="https://yourproject.com" class="project-card">
```

Or if you want to link to a local page:

```html
<a href="project-details.html" class="project-card">
```

## Step 4: Add More Projects
To add more projects, copy this code inside the `projects-grid` div:

```html
<a href="#" class="project-card">
    <div class="project-image">
        <img src="images/project4.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Short description</p>
    </div>
</a>
```

## Current Structure
- Responsive grid layout (automatically adjusts columns)
- Hover effects (cards lift up and scale image)
- Clean borders and shadows
- Mobile-friendly

## Tips
- Keep image file sizes under 500KB for fast loading
- Use descriptive alt text for accessibility
- Update project titles and descriptions in the HTML
- The grid automatically adjusts to screen size!
