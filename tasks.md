### Setup

1. Create a new branch for your changes: `git checkout -b first-tasks`
2. After you finish each task, add your changes: `git add .`
4. Then, commit your changes: `git commit -m "Completed task 1"`
5. Once all tasks are done, push your branch: `git push origin first-tasks`


---

### Task 1: Fix a Typo in the About Page
**Time estimate**: 5-10 minutes  
**File**: `app/views/static_pages/about.html.erb`

**What to do**:
1. Open the file `app/views/static_pages/about.html.erb`
2. Find line 9 (or search for the text "hack it")
3. Change "hack it on their own" to "figure it out on their own"
4. Save the file
5. Reload the about page to verify the change.

---

### Task 2: Update Copyright Year
**Time estimate**: 5-10 minutes  
**File**: Search for files containing "copyright" or look in footer/layout files

**What to do**:
1. Use your editor's search function (Ctrl+Shift+F or Cmd+Shift+F) to search for "copyright" across all files
2. Find where the copyright year is displayed
3. Make sure it shows 2024 (or current year)
4. Save the file
5. Reload the app to verify that the copyright has been updated

---

### Task 3: Change Button Text
**Time estimate**: 5-10 minutes  
**File**: `app/views/static_pages/about.html.erb`

**What to do**:
1. Open `app/views/static_pages/about.html.erb`
2. Find line 34 (or search for "Chat on Discord")
3. Change the button text from "Chat on Discord" to "Join Our Discord Community"
4. Save the file
5. Reload the about page to verify the change.

---

### Task 4: Add a CSS Class to Make Text Blue⭐
**Time estimate**: 10-15 minutes  
**File**: `app/views/static_pages/about.html.erb`

**What to do**:
1. Find the heading "Want to contact us?" (around line 28)
2. Look for the `class=` attribute in that heading
3. Add `text-blue-600` to the existing classes
4. It should look something like: `class="mb-4 font-bold text-2xl text-blue-600"`
5. Save the file
6. Verify that the button text color is updated in the app

---

### Task 5: Add a Comment to Ruby Code⭐
**Time estimate**: 10-15 minutes  
**File**: `app/models/user.rb`

**What to do**:
1. Open `app/models/user.rb`
2. Find line 10 that starts with `validates :email`
3. Add a comment on the line above it: `# Ensures email is unique and properly formatted`
4. Make sure the comment line starts with `#` and has proper spacing
5. Save the file

---

### Task 6: Add a New Link (Advanced)
**Time estimate**: 15-20 minutes  
**File**: Look for footer files in `app/views/shared/` or `app/views/layouts/`

**What to do**:
1. Find the footer template (search for files containing "footer" or look in layout files)
2. Add a new link for "Code of Conduct" next to existing footer links
3. Use this HTML: `<a href="/code-of-conduct" class="footer-link">Code of Conduct</a>`
4. Match the style of existing footer links
5. Save the file
6. Verify that links have been added in the app.

---
