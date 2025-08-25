# Minh Phúc - Personal Portfolio

A modern, responsive portfolio website showcasing my journey as a Computer Science student at Ho Chi Minh City University of Technology (HCMUT).

## 🚀 Live Demo

Visit the live website: [https://phuc-cnpm.github.io/GitPages](https://phuc-cnpm.github.io/GitPages)

## 📋 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Fast Loading**: Lightweight HTML/CSS/JS with optimized performance
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Accessible**: Following web accessibility guidelines

## 🛠️ Built With

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactive features and animations
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter font family)

## 📁 Project Structure

```
├── .github/
│   └── workflows/
│       └── deploy.yml              # GitHub Actions workflow for gh-pages deployment
├── index.html                      # Main HTML file
├── styles.css                      # CSS styles
├── script.js                       # JavaScript functionality
├── README.md                       # Project documentation
└── package.json                    # Project configuration
```

## 🚀 Deployment to GitHub Pages

### Method 1: Automatic Deployment với GitHub Actions (Khuyến nghị) 🤖

Repository này đã được cấu hình với **GitHub Actions** để tự động deploy lên GitHub Pages:

1. **Push code lên GitHub**:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```

2. **Kích hoạt GitHub Pages**:
   - Vào repository trên GitHub
   - Click tab **Settings**
   - Scroll xuống **Pages** section
   - Trong **Source**, chọn **Deploy from a branch**
   - Chọn **gh-pages** branch và **/ (root)** folder
   - Click **Save**
   - Website sẽ tự động deploy mỗi khi push code lên **main**!
   - **Nhánh gh-pages sẽ được tự động tạo** bởi GitHub Actions

3. **Xem quá trình deployment**:
   - Vào tab **Actions** để theo dõi quá trình build
   - Website available tại: `https://phuc-cnpm.github.io/GitPages`

### Method 2: Manual Deployment

1. **Push your code to GitHub**:
   - Make sure all files are committed and pushed to your repository

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on **Settings** tab
   - Scroll down to **Pages** section
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

### Method 3: Using GitHub CLI

```bash
# Enable GitHub Pages với gh-pages branch
gh repo edit --enable-pages --pages-branch gh-pages --pages-path /
```

## 🌿 Về nhánh gh-pages

- **Nhánh gh-pages được tự động tạo** bởi GitHub Actions
- **Không cần tạo thủ công** - workflow sẽ lo việc này
- **Chứa code đã được deploy** từ main branch
- **GitHub Pages serve từ nhánh này**, không phải từ main

## 🔄 GitHub Actions Workflow

Repository này có **1 workflow file duy nhất**:

- **`.github/workflows/deploy.yml`**: Tự động deploy lên gh-pages branch

**Tính năng của workflow**:
- ✅ **Tự động tạo nhánh `gh-pages`** khi chạy lần đầu
- ✅ **Deploy từ main branch** mỗi khi có push
- ✅ **2 deployment methods** trong cùng 1 file (peaceiris & JamesIves)
- ✅ **Build support** (có thể uncomment nếu cần build process)
- ✅ **Manual trigger** (có th�� chạy thủ công từ Actions tab)
- ✅ **Node.js setup** (sẵn sàng cho future projects)

## 🔧 Local Development

To run the website locally:

```bash
# Using Python (recommended)
python3 -m http.server 3000

# Or using Node.js if you have it
npx serve .

# Or simply open index.html in your browser
```

Then visit: `http://localhost:3000`

## 📝 Customization

### Updating Personal Information

1. **Edit index.html**:
   - Update name, university, and personal information
   - Modify contact links (email, Facebook, LinkedIn)

2. **Edit styles.css**:
   - Change colors by modifying CSS custom properties
   - Adjust layout and typography as needed

3. **Edit script.js**:
   - Customize animations and interactive features

### Adding New Sections

1. Add new section HTML in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu if needed

## 🌟 Performance Optimizations

- Minified CSS and JavaScript
- Optimized images and icons
- Efficient animations using CSS transforms
- Lazy loading for better performance

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📞 Contact

- **Email**: phuc26062005@gmail.com
- **Facebook**: [facebook.com/phuclinhutrau](https://facebook.com/phuclinhutrau)
- **LinkedIn**: [Connect with me](https://linkedin.com/in/minh-phuc-nguyen)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ by Minh Phúc for learning and growth 🚀
