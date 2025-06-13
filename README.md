project:
  name: Responsive UI Component Design Project
  tech_stack:
    - HTML5
    - CSS3 or Tailwind CSS
  description: >
    A collaborative frontend development project where 4 groups of students design and implement
    5 real-world UI components using HTML and CSS. The focus is on responsive design, clean structure,
    reusable components, and optionally using Tailwind CSS for utility-first styling.

structure:
  folders:
    - Group-A/responsive-card-grid/
    - Group-B/sticky-navbar-dropdown/
    - Group-C/contact-form/
    - Group-C/toggle-switch/
    - Group-D/product-card-hover/
    - shared-assets/ # optional
    - README.md
  files:
    each_component:
      - index.html
      - style.css or tailwind.css

components:
  - name: Responsive Card Grid
    group: Group A
    members: [Pooja, Pratistha, Pemba]
    folder: Group-A/responsive-card-grid/
  - name: Sticky Navbar with Dropdown
    group: Group B
    members: [Sirish, Robij]
    folder: Group-B/sticky-navbar-dropdown/
  - name: Contact Form with Validation Feedback
    group: Group C
    members: [Srijana, Hriyan, Karan]
    folder: Group-C/contact-form/
  - name: Custom Toggle Switch
    group: Group C
    members: [Srijana, Hriyan, Karan]
    folder: Group-C/toggle-switch/
  - name: Product Card with Hover Animation
    group: Group D
    members: [Himal, Bhuwan]
    folder: Group-D/product-card-hover/

git_repository:
  name: responsive-ui-components-project
  host: GitHub or GitLab
  workflow:
    - Clone repository:
        command: git clone https://github.com/your-org/responsive-ui-components-project.git
    - Create group-specific branch:
        command: git checkout -b group-a-card-grid
    - Stage and commit:
        command: |
          git add .
          git commit -m "Group A: Added responsive card grid"
    - Push branch:
        command: git push origin group-a-card-grid
    - Pull Request (PR):
        description: >
          After pushing, group members create a Pull Request for review and merge
          into the main branch.

git_best_practices:
  - Use meaningful commit messages with group names.
  - Each group works only in their own folder to avoid merge conflicts.
  - Always pull latest changes before pushing: git pull origin main
  - Maintain proper folder structure and file naming.
  - Keep CSS modular; use Tailwind CDN if preferred.
  - Comment code where necessary.
  - Use .gitignore to exclude unnecessary files.

optional:
  tailwind_usage:
    cdn: https://cdn.tailwindcss.com
    example: |
      <script src="https://cdn.tailwindcss.com"></script>
  bonus_challenges:
    - Add Tailwind transitions and hover animations
    - Implement dark mode toggle using checkbox + Tailwind dark class
    - Use CSS Grid or Flexbox effectively for responsive layout

notes:
  - No JavaScript is required; interactivity should be achieved using CSS only.
  - This project can serve as a portfolio piece or assignment submission.
  - Consider extending with JavaScript functionality in future versions.

