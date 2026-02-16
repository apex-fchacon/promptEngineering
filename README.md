# QA Prompt Engineering Interactive Training Platform

A comprehensive interactive training platform for learning AI-powered Quality Assurance and Prompt Engineering. Complete the entire course in **8-10 hours** with 19 exercises and 4 module challenges. All code consolidated in a single HTML file for easy deployment.

## 🎯 Project Overview

This interactive training platform guides QA professionals through a structured learning journey with practical, hands-on exercises. The course uses a clean, minimalist WordPress-inspired design built with Tailwind CSS.

### Course Structure

**Duration:** 8-10 Hours Total  
**Level:** Intermediate  
**Target Audience:** QA Engineers, Testers, Quality Analysts with basic testing experience

## ✨ Key Features

### 📚 Comprehensive Curriculum
- **Module 1: Fundamentals** - "Your First Prompts" (2 hours | 5 exercises + 1 challenge)
- **Module 2: Intermediate** - "Smarter Prompts" (2-3 hours | 5 exercises + 1 challenge)
- **Module 3: Advanced** - "Patterns & Workflows" (2-3 hours | 5 exercises + 1 challenge)
- **Module 4: Professional** - "Integration & Governance" (2 hours | 4 exercises + 1 challenge)

### 🎯 Interactive Learning
- 19 daily exercises with clear objectives
- Detailed prompt templates ready to use
- Practice sites and real-world scenarios
- Submission forms for student work
- Reflection and learning capture

### 🏆 Module Challenges
- 4 comprehensive projects testing cumulative knowledge
- Point-based evaluation system (100 points per challenge)
- Professional deliverables (test plans, documentation, portfolios)
- Realistic enterprise scenarios

### 📊 Progress Tracking
- Real-time completion tracking
- Visual progress dashboard with Chart.js
- Per-module progress indicators
- Total points and completion percentage
- **File-based persistence** (downloadable JSON files)
- **Auto-save on completion** (automatic download)
- **Import/Export functionality** (load previous progress)

### 🎨 Modern Design
- **Tailwind CSS framework** for clean, minimalist styling
- WordPress-inspired professional appearance
- Fully responsive (mobile, tablet, desktop)
- Smooth animations and transitions
- Accessible interface

### 💾 Data Storage
All data stored in **downloadable JSON files**:
- Exercise submissions and progress
- Challenge completions and scores
- Student notes and reflections
- **Auto-download after every completion**
- **Manual export/import anytime**
- **No server or database required**
- **No localStorage limitations** (no 5MB quota issues)
- **Progress can be reset per module or entirely**
- **Completed modules list with re-take option**
- **Portable progress files** (move between devices/browsers)

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- File download/upload permissions enabled
- Internet connection (for Tailwind CSS CDN, Chart.js, Font Awesome)
- Folder to save progress files (e.g., "QA Training Progress")

### Installation
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start learning immediately - no setup required!

### File Structure
```
/
├── index.html              # Single-file application (108KB)
└── README.md              # This documentation
```

That's it! Everything is contained in one HTML file.

## 💾 File-Based Progress System

### Why File-Based Instead of localStorage?

This training platform uses a **file-based approach** for storing progress instead of browser localStorage. This provides several key advantages:

✅ **No Storage Limits** - No 5MB localStorage quota restrictions  
✅ **Full Portability** - Move progress files between devices and browsers  
✅ **Version Control** - Keep multiple versions of your progress  
✅ **Backup & Recovery** - Easy to backup, share, or restore progress  
✅ **No Browser Dependency** - Not tied to a specific browser's storage  
✅ **Privacy Control** - You physically own your data files  
✅ **Collaboration Ready** - Share progress files with instructors or mentors  

### How It Works

#### 1. **Automatic Save on Completion**
Every time you complete an exercise or challenge:
- ✅ Your progress is **automatically saved** to a JSON file
- ✅ File is **downloaded** to your browser's Downloads folder
- ✅ Filename includes **timestamp**: `qa-training-progress-2024-02-12T14-30-45.json`
- ✅ No manual intervention required

#### 2. **Manual Export Anytime**
- Click the **"Download Progress File"** button (blue button)
- Creates a snapshot of your current progress
- Downloads immediately to your Downloads folder
- Use this to create backups at any time

#### 3. **Import Previous Progress**
- Click the **"Load Progress File"** button (green button)
- Select a previously saved `.json` file
- Your progress is **instantly restored**
- All exercises, challenges, scores reload

#### 4. **File Management Best Practices**

**Recommended Setup:**
```
Documents/
└── QA Training Progress/
    ├── qa-training-progress-2024-02-10T09-00-00.json  (Day 1)
    ├── qa-training-progress-2024-02-11T16-30-00.json  (Day 2)
    └── qa-training-progress-2024-02-12T14-30-45.json  (Latest)
```

**Tips:**
- Create a dedicated folder: **"QA Training Progress"**
- Keep the **most recent file** for active work
- Keep **older files** as backups/checkpoints
- Files are **timestamped** for easy identification
- File size is typically **< 100KB** (very small)

#### 5. **Cross-Device Usage**

**Scenario:** Start on laptop, continue on desktop
1. Complete exercises on your laptop
2. Progress file downloads automatically
3. Email or cloud-save the JSON file
4. Open training page on desktop
5. Click "Load Progress File" and select your file
6. Continue exactly where you left off!

**Works with:**
- Different computers
- Different browsers (Chrome → Firefox → Safari)
- Mobile devices (tablet, phone)
- Shared team computers

#### 6. **Collaboration & Submission**

**Submit Progress to Instructor:**
1. Complete your exercises/challenges
2. Download latest progress file
3. Email or upload the `.json` file to your instructor
4. Instructor can import and review your work

**Instructor Review:**
1. Instructor opens `index.html` in browser
2. Clicks "Load Progress File"
3. Selects student's submitted `.json` file
4. Reviews all completed exercises and scores

### Technical Details

**File Format:** JSON (JavaScript Object Notation)  
**File Size:** Typically 10-100KB  
**Max Size:** 10MB (safety limit)  
**Encoding:** UTF-8  
**Structure:** Validated on import  

**Security:**
- ✅ Files stored on **your local device**
- ✅ No data sent to external servers
- ✅ No tracking or analytics
- ✅ You control access and sharing

**Browser Compatibility:**
- ✅ Chrome, Firefox, Safari, Edge all supported
- ✅ Works in incognito/private mode
- ✅ No special permissions required
- ✅ Uses standard File API (supported since 2014)

## 📂 What's Included

### Single HTML File Contains:
- ✅ Complete HTML structure
- ✅ Embedded CSS (Tailwind + custom styles)
- ✅ All JavaScript functionality
- ✅ 19 exercise contents with prompts
- ✅ 4 challenge scenarios
- ✅ Progress tracking system
- ✅ **File-based data management** (JSON export/import)
- ✅ **Auto-download on completion**
- ✅ **Manual export/import buttons**
- ✅ **Completed modules list with progress bars**
- ✅ **Module reset functionality (re-take option)**
- ✅ **Full progress reset option**

### External Dependencies (CDN):
- Tailwind CSS
- Chart.js
- Font Awesome Icons

## 🎓 Module Breakdown

### Module 1: Fundamentals (2 hours)
- Exercise 1: Your First Test Case (20 min)
- Exercise 2: Generating Test Data (20 min)
- Exercise 3: Writing a Bug Report (20 min)
- Exercise 4: Expanding Test Cases (20 min)
- Exercise 5: Creating a Testing Checklist (20 min)
- **Challenge:** My First AI-Generated Test Suite (45-60 min)

### Module 2: Intermediate Techniques (2-3 hours)
- Exercise 1: Using Examples (Few-Shot) (30 min)
- Exercise 2: Step-by-Step Reasoning (30 min)
- Exercise 3: Role-Playing with AI (30 min)
- Exercise 4: Structured Format Outputs (30 min)
- Exercise 5: Iterative Refinement (30 min)
- **Challenge:** Enterprise Test Documentation (90-120 min)

### Module 3: Advanced Patterns (2-3 hours)
- Exercise 1: ReAct Pattern for Requirements (35 min)
- Exercise 2: Prompt Chain for Shopping Cart (35 min)
- Exercise 3: Synthetic Data with Constraints (35 min)
- Exercise 4: Critical Reviewer Pattern (35 min)
- Exercise 5: Output Evaluation with Rubric (35 min)
- **Challenge:** My QA Copilot Library (90-120 min)

### Module 4: Professional Integration (2 hours)
- Exercise 1: Internal Policy for AI Use (30 min)
- Exercise 2: Metrics Dashboard Design (30 min)
- Exercise 3: Prompt A/B Testing (30 min)
- Exercise 4: Stakeholder Communication Pack (30 min)
- **Final Capstone:** End-to-End QA with AI (120 min)

## 📋 Features Overview

### ✅ What's Implemented

1. **Complete Training Content**
   - All 19 exercises with detailed instructions
   - All 4 module challenges with scenarios
   - Prompt templates for every exercise
   - Learning objectives and tasks

2. **Interactive UI**
   - Collapsible module sections
   - Modal-based exercise viewer
   - Submission forms with validation
   - Progress tracking dashboard

3. **File-Based Storage System**
   - Automatic JSON file download on completion
   - Exercise completion tracking
   - Challenge scores and submissions
   - Manual export/import anytime
   - Portable between devices and browsers
   - No localStorage quota limitations

4. **Visual Progress**
   - 4 key metric cards
   - Chart.js bar graph
   - Per-module completion rates
   - Overall percentage tracker

5. **Professional Design**
   - Clean WordPress-inspired layout
   - Tailwind CSS styling
   - Responsive grid system
   - Smooth transitions

## 🌐 Deployment Options

### Option 1: Local Use (Simplest)
1. Download `index.html`
2. Double-click to open in browser
3. Start using immediately

### Option 2: Web Server
Upload to any static hosting:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Azure Static Web Apps

### Option 3: Microsoft SharePoint (Recommended for Teams)

#### SharePoint Deployment Instructions

**Method A: Upload to Document Library (Quick Setup)**

1. **Prepare the File**
   - Save `index.html` to your local computer
   - Note: SharePoint may block certain HTML features for security

2. **Upload to SharePoint**
   - Navigate to your SharePoint site
   - Go to **Documents** library (or create a new document library)
   - Click **Upload** → **Files**
   - Select `index.html`
   - Click **Open** to upload

3. **Access the File**
   - Once uploaded, click on the file name
   - SharePoint will attempt to render it in the browser
   - **Note:** Some features may be limited due to SharePoint security policies

4. **Share with Team**
   - Click the file's **Share** button
   - Add team members or get shareable link
   - Set permissions (View or Edit)

**Method B: SharePoint Pages (Recommended)**

1. **Create a New Page**
   - Navigate to your SharePoint site
   - Click **+ New** → **Page**
   - Choose a page template (blank recommended)
   - Give it a name: "QA Prompt Engineering Training"

2. **Add Embed Web Part**
   - Click **+** to add a web part
   - Search for "Embed"
   - Select **Embed** web part

3. **Host the HTML File**
   - Upload `index.html` to a public hosting service (GitHub Pages, Netlify)
   - Copy the public URL
   - Paste the URL into the Embed web part
   - Adjust size as needed

4. **Publish the Page**
   - Click **Publish** in the top right
   - Share the page link with your team

**Method C: SharePoint Site Collection (Full Control)**

1. **Enable Custom Scripts** (Admin Required)
   - Go to SharePoint Admin Center
   - Navigate to **Settings**
   - Enable "Custom Script" for site collections
   - **Warning:** This reduces security; consult IT first

2. **Create a Site Collection**
   - Create a dedicated site collection for training
   - Upload `index.html` as the default page

3. **Set as Home Page**
   - Upload file to "Site Pages" library
   - Set as welcome/home page for the site

**Method D: Microsoft Teams Integration**

1. **Create a Teams Channel**
   - In Microsoft Teams, create a channel for training
   - Go to the channel's **Files** tab

2. **Upload to Files**
   - Click **Upload** in the Files tab
   - Upload `index.html`
   - Click on the file to open

3. **Pin as Tab**
   - Click **+** to add a tab
   - Choose **Document Library**
   - Select your uploaded HTML file
   - Pin it for easy access

**SharePoint Limitations & Solutions**

| Challenge | Solution |
|-----------|----------|
| HTML may not render fully | Host externally (GitHub Pages) and embed |
| Security restrictions | Use Method B (Embed web part) |
| Custom scripts blocked | Request IT to enable or use external hosting |
| CDN resources blocked | Download and host Tailwind/Chart.js locally |
| File download restrictions | Check browser settings for download permissions |
| File upload restrictions | Ensure file input is enabled in browser |

**Best Practice for SharePoint:**
- Host the `index.html` file on **GitHub Pages** (free, fast, reliable)
- Embed the GitHub Pages URL in a SharePoint page using the Embed web part
- This approach avoids SharePoint's HTML rendering limitations

#### GitHub Pages + SharePoint Integration

1. **Setup GitHub Pages**
   ```bash
   # Create a GitHub repository
   # Upload index.html to the repository
   # Enable GitHub Pages in repository Settings
   # Your URL will be: https://username.github.io/repo-name/
   ```

2. **Embed in SharePoint**
   - Copy your GitHub Pages URL
   - In SharePoint, add an **Embed** web part
   - Paste the URL
   - Set width: 100%, height: 800px (or full screen)

3. **Benefits**
   - ✅ Full HTML/CSS/JS support
   - ✅ CDN resources load properly
   - ✅ File download/upload works normally
   - ✅ Easy updates (just push to GitHub)
   - ✅ Shareable via SharePoint

#### Managing Progress Files in SharePoint

**Student Workflow:**

1. **Access Training**
   - Open the embedded training page (GitHub Pages in SharePoint)
   - Complete exercises and challenges
   - Progress files auto-download to your Downloads folder

2. **Store Progress in SharePoint**
   - Navigate to SharePoint document library
   - Create a folder: "Student Progress Files"
   - Upload your progress JSON files regularly
   - Use SharePoint version history as backup

3. **Resume on Different Device**
   - Access SharePoint from any device
   - Download your latest progress file
   - Open training page
   - Click "Load Progress File" and select downloaded file
   - Continue where you left off

**Instructor Workflow:**

1. **Collect Student Progress**
   - Students upload progress files to shared SharePoint folder
   - Organize by student name or date
   - Example structure:
     ```
     SharePoint/Training Progress/
     ├── John_Doe/
     │   └── qa-training-progress-2024-02-12T14-30-45.json
     ├── Jane_Smith/
     │   └── qa-training-progress-2024-02-12T15-20-30.json
     └── Bob_Johnson/
         └── qa-training-progress-2024-02-12T16-45-12.json
     ```

2. **Review Student Work**
   - Open `index.html` locally or via GitHub Pages
   - Download student's progress file from SharePoint
   - Click "Load Progress File"
   - Select student's file
   - Review all completed exercises, scores, and submissions

3. **Provide Feedback**
   - Use SharePoint comments on student folders
   - Track completion rates via Dashboard view
   - Export progress statistics if needed

**SharePoint + File-Based Benefits:**

| Feature | Benefit |
|---------|---------|
| **Centralized Storage** | All student progress in one secure location |
| **Version History** | SharePoint tracks file versions automatically |
| **Access Control** | Set permissions per folder/student |
| **Audit Trail** | Track who uploaded/modified files and when |
| **Backup & Recovery** | SharePoint backup policies apply |
| **Mobile Access** | Students can download files via SharePoint mobile app |
| **Collaboration** | Instructors can share feedback via SharePoint |

**Best Practice Setup:**

1. **SharePoint Site Structure**
   ```
   QA Training Site/
   ├── Training Materials/
   │   └── index.html (or link to GitHub Pages)
   ├── Student Progress/
   │   ├── Student_1/
   │   ├── Student_2/
   │   └── Student_3/
   └── Resources/
       ├── Guides/
       └── Templates/
   ```

2. **Permissions Setup**
   - **Training Materials:** Read-only for all students
   - **Student Progress:** Each student folder = read/write for owner only
   - **Instructor Folder:** Read access to all student folders
   - **Resources:** Read-only for all

3. **Automated Workflow** (Optional)
   - Use Power Automate to send notifications when students upload progress
   - Track submission deadlines
   - Auto-archive old progress files

## 🔧 Technical Stack

### Frontend Technologies
- **HTML5** - Semantic structure
- **Tailwind CSS** - Utility-first styling via CDN
- **JavaScript (ES6+)** - Object-oriented architecture
- **Chart.js** - Progress visualization
- **Font Awesome** - Professional icons

### Data Storage
- **File API** - Browser download/upload
- **Blob API** - Efficient memory management
- **JSON** - Data serialization
- **FileReader API** - Import progress files

### No Backend Required
- Pure static HTML file
- No server needed
- No database required
- No build process

## 📊 Progress Tracking

### File-Based Storage Structure

**Filename Format:** `qa-training-progress-YYYY-MM-DDTHH-MM-SS.json`

```javascript
{
  "exercises": {
    "module1": {
      "day1": {
        "completed": true,
        "completedAt": "2024-02-12T10:30:00Z",
        "prompts": "...",
        "results": "...",
        "documentUrl": "..."
      }
    }
  },
  "challenges": {
    "module1": {
      "completed": true,
      "completedAt": "2024-02-12T12:00:00Z",
      "score": 95,
      "documentLink": "...",
      "summary": "...",
      "reflection": "..."
    }
  },
  "metadata": {
    "createdAt": "2024-02-12T09:00:00Z",
    "lastModified": "2024-02-12T12:00:00Z",
    "version": "2.0",
    "totalExercises": 19,
    "completedExercises": 1,
    "completedChallenges": 1,
    "totalPoints": 95
  }
}
```

### How It Works

1. **Auto-Save on Completion**
   - Every time you complete an exercise or challenge
   - Progress is automatically saved to a JSON file
   - File is downloaded to your browser's Downloads folder
   - Filename includes timestamp for version tracking

2. **Manual Export**
   - Click "Download Progress File" button anytime
   - Creates a snapshot of current progress
   - Saves with timestamp in filename

3. **Import Previous Progress**
   - Click "Load Progress File" button
   - Select a previously saved `.json` file
   - Progress is instantly restored
   - Works across different browsers and devices

4. **File Organization Tip**
   - Create a folder: "QA Training Progress"
   - Save all progress files there
   - Keep latest versions for backup
   - Files are timestamped for easy tracking

### Metrics Tracked
- Exercises completed (out of 19)
- Challenges completed (out of 4)
- Total points earned (max 400)
- Overall completion percentage
- Per-module progress

## 🔐 Privacy & Security

### Data Storage
- All data stored in **downloadable JSON files**
- Files saved to your Downloads folder
- No data transmitted to external servers
- Students control their own data
- **Full data portability** - move files between devices
- **No browser dependency** - import on any browser
- **Version control** - keep multiple file versions
- Delete files to reset progress

### Important Security Note
**DO NOT SHARE SENSITIVE INFORMATION** when using AI tools:
- ❌ No passwords or credentials
- ❌ No institutional branding
- ❌ No financial data
- ❌ No personal identifiable information (PII)
- ❌ No proprietary company information

## 🤝 AI Tools Covered

The course teaches prompt engineering with:
- **Microsoft Copilot** (Preferred)
- **Google Gemini**

All tools used through web interfaces - no coding required.

## 📚 Learning Resources

### Official Documentation
- [Microsoft Learn: Effective Prompts](https://learn.microsoft.com/en-us/azure/copilot/write-effective-prompts)
- [Learn Prompting](https://learnprompting.org/)
- [DeepLearning.AI Courses](https://www.deeplearning.ai/short-courses/)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook)

### Best Practices
- [Responsible AI Principles](https://learn.microsoft.com/ai/responsible-ai/)
- [NIST AI Risk Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [WCAG Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)

### Practice Site
- [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/) - Live testing environment

## 🎨 Design System

### WordPress-Inspired Styling
- Clean, minimalist layout
- Card-based content organization
- Subtle shadows and borders
- Professional color palette
- Sans-serif typography

### Color Palette
- **Primary:** Blue-600 (#2563eb) - Main actions and highlights
- **Success:** Green-600 (#16a34a) - Completed items
- **Warning:** Yellow-600 (#ca8a04) - Challenges and important notes
- **Gray Scale:** Gray-50 to Gray-900 - UI elements

### Responsive Breakpoints
- Mobile: 320px - 639px
- Tablet: 640px - 1023px
- Desktop: 1024px+

## 🏆 Success Metrics

Students who complete this course will be able to:
- ✅ Write effective prompts for various QA tasks
- ✅ Generate comprehensive test cases using AI
- ✅ Create realistic test data at scale
- ✅ Improve documentation quality
- ✅ Implement AI workflows in testing processes
- ✅ Evaluate AI output quality systematically
- ✅ Apply governance and ethical AI practices
- ✅ Demonstrate ROI of AI in QA workflows

## ⚙️ Browser Compatibility

### Supported Browsers
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

### Required Features
- JavaScript enabled
- File download/upload permissions enabled
- CSS Grid and Flexbox support
- ES6 JavaScript support
- Blob and FileReader API support

## 🐛 Troubleshooting

### Common Issues

**Progress File Not Downloading**
- Check browser download settings and permissions
- Ensure pop-ups and downloads are not blocked
- Check Downloads folder for files (may download automatically)
- Look for browser notification about blocked downloads
- Try manual export using "Download Progress File" button

**Cannot Upload Progress File**
- Ensure file is in `.json` format
- Verify file is not corrupted (open in text editor to check)
- Check file size (must be under 10MB)
- Clear file input and try again
- Try a different browser if issue persists

**File Format Error on Import**
- Ensure you're uploading a valid progress file
- File must have `exercises` and `challenges` keys
- Don't manually edit JSON (may break structure)
- Try exporting a new file and use that

**CDN Resources Not Loading**
- Verify internet connection
- Check if corporate firewall blocks CDNs
- Try accessing Tailwind CSS, Chart.js, Font Awesome URLs directly

**SharePoint Not Displaying HTML**
- Use Method B (Embed web part with external hosting)
- Check SharePoint custom script settings
- Contact IT for security policy exceptions

**Chart Not Displaying**
- Ensure Chart.js CDN is accessible
- Check browser console for errors
- Verify canvas element is present

## 📝 Customization

### Modifying Content
All content is in the single `index.html` file:
- **Exercise Data:** Search for `const exerciseData`
- **Challenge Data:** Search for `const challengeData`
- **Styling:** Modify Tailwind classes or `<style>` section
- **Branding:** Update header text and colors

### Adding New Exercises
1. Add exercise to `exerciseData` object
2. Update module HTML section
3. Increment total exercise count in progress calculation

## 📄 License

This project is created for educational purposes. Content is based on the QA Prompt Engineering course curriculum.

## 🙏 Acknowledgments

- Course content based on industry best practices
- UI/UX inspired by WordPress and modern learning platforms
- Tailwind CSS for styling framework
- Chart.js for data visualization
- Font Awesome for icons

## 📞 Support

### Getting Help
- Review exercise instructions carefully
- Check the Resources section for additional learning
- Use AI tools to debug prompts
- Experiment and iterate

### For Instructors
- Customize content by editing the HTML file
- Add your own exercises and challenges
- Modify evaluation criteria
- Brand with your organization's colors

## 🔄 Version History

### v2.0.0 (Current - Redesigned)
- ✅ Single-file architecture (all HTML/CSS/JS in one file)
- ✅ Tailwind CSS for WordPress-inspired design
- ✅ LocalStorage for all data (no database)
- ✅ 8-10 hour completion timeline
- ✅ Module-based structure (not weeks)
- ✅ Intermediate level focus
- ✅ SharePoint deployment instructions

### v1.0.0 (Previous)
- Multi-file architecture
- Custom CSS
- 4-week structure
- Beginner to Intermediate level

---

## 🚀 Ready to Deploy?

### Quick Deployment Checklist

**For Individual Use:**
- [ ] Download `index.html`
- [ ] Open in browser
- [ ] Start learning!

**For Team/SharePoint:**
- [ ] Upload to GitHub Pages (recommended)
- [ ] Create SharePoint page
- [ ] Add Embed web part
- [ ] Paste GitHub Pages URL
- [ ] Publish and share with team

**For Custom Hosting:**
- [ ] Upload `index.html` to hosting service
- [ ] Verify CDN resources load
- [ ] Test progress saving
- [ ] Share URL with students

---

**Ready to start learning?** Open `index.html` in your browser and begin your journey to becoming an AI-powered QA professional! 🎓✨

For the best team collaboration experience, follow the **GitHub Pages + SharePoint** integration method described above.