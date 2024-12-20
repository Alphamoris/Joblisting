# 🚀 Modern Job Board Platform

<div align="center">
  <img src="demo/banner.png" alt="Job Board Banner" width="100%"/>
  
  <p align="center">
    <a href="https://github.com/alphamoris/joblisting/stargazers">
      <img src="https://img.shields.io/github/stars/alphamoris/joblisting?style=for-the-badge" alt="GitHub stars"/>
    </a>
    <a href="https://github.com/alphamoris/joblisting/network/members">
      <img src="https://img.shields.io/github/forks/alphamoris/joblisting?style=for-the-badge" alt="GitHub forks"/>
    </a>
    <a href="https://github.com/alphamoris/joblisting/issues">
      <img src="https://img.shields.io/github/issues/alphamoris/joblisting?style=for-the-badge" alt="GitHub issues"/>
    </a>
  </p>

  <h3>A modern, full-stack job listing platform with automated scraping and real-time search</h3>

  <p align="center">
    <a href="#demo">View Demo</a>
    ·
    <a href="#features">Features</a>
    ·
    <a href="#installation">Installation</a>
    ·
    <a href="#contributing">Contributing</a>
  </p>
</div>

## 🎥 Demo

[https://drive.google.com/file/d/1yHwwJOyTrk9R8iyCIwE__DuPFn-x2APj/view?usp=sharing.mp4]

## 📸 Screenshots

<div align="center">
  <details>
    <summary>🖼️ Click to view screenshots</summary>
    <img src="https://github.com/Alphamoris/Joblisting/tree/main/memo/screenshot1.png" alt="Home Page" width="100%"/>
    <p><em>Home Page with Advanced Search and Filtering</em></p>
    <br/>
    <img src="https://github.com/Alphamoris/Joblisting/tree/main/memo/screenshot2.png" alt="Job Details" width="100%"/>
    <p><em>Detailed Job View with Skills and Application</em></p>
    <br/>
    <img src="https://github.com/Alphamoris/Joblisting/tree/main/memo/screenshot3.png" alt="Search Results" width="100%"/>
    <p><em>Search Results with Real-time Filtering</em></p>
  </details>
</div>

## ✨ Features

<div align="center">
  <table>
    <tr>
      <td align="center">🔍</td>
      <td><strong>Advanced Search</strong><br/>Real-time search with keyword highlighting</td>
      <td align="center">🎯</td>
      <td><strong>Smart Filters</strong><br/>Filter by location, type, and salary</td>
    </tr>
    <tr>
      <td align="center">🤖</td>
      <td><strong>Auto Scraping</strong><br/>Automated job collection from multiple sources</td>
      <td align="center">📱</td>
      <td><strong>Responsive UI</strong><br/>Beautiful interface on all devices</td>
    </tr>
    <tr>
      <td align="center">🔒</td>
      <td><strong>Secure Backend</strong><br/>Django REST with token authentication</td>
      <td align="center">📊</td>
      <td><strong>Analytics</strong><br/>Track applications and success rates</td>
    </tr>
  </table>
</div>

## 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <th>Frontend</th>
      <th>Backend</th>
      <th>Database</th>
      <th>Tools</th>
    </tr>
    <tr>
      <td>
        <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
        <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind"/>
      </td>
      <td>
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/DRF-red?style=for-the-badge&logo=django&logoColor=white" alt="DRF"/>
        <img src="https://img.shields.io/badge/Scrapy-60A839?style=for-the-badge&logo=python&logoColor=white" alt="Scrapy"/>
      </td>
      <td>
        <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
      </td>
      <td>
        <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
        <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
      </td>
    </tr>
  </table>
</div>

## 🚀 Quick Start

### Prerequisites

<details>
<summary>Click to expand</summary>

- Node.js 18+
- Python 3.11+
- MySQL 8.0+
- Git

</details>

### Frontend Setup

<details>
<summary>Click to expand</summary>

1. Clone and install dependencies:
```bash
git clone https://github.com/yourusername/job-board.git
cd job-board
npm install
```

2. Create `.env.local`:
```env
NEXT_PUBLIC_API_URL=http://localhost:8000
```

3. Start development server:
```bash
npm run dev
```
</details>

### Backend Setup

<details>
<summary>Click to expand</summary>

1. Set up virtual environment:
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

2. Create `.env`:
```env
DJANGO_SECRET_KEY=your-secret-key
DEBUG=True
DB_NAME=joblisting_db
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_HOST=localhost
DB_PORT=3306
DICE_API_KEY=your_dice_api_key
BACKEND_URL=http://localhost:8000
ALLOWED_HOSTS=localhost,127.0.0.1
CORS_ALLOWED_ORIGINS=http://localhost:3000
```

3. Run migrations and server:
```bash
python manage.py migrate
python manage.py runserver
```
</details>

## 📊 Key Features Demo

### 1. Advanced Search & Filtering
![Search Demo](demo/search.gif)
- Real-time search suggestions
- Multiple filter combinations
- Salary range slider

### 2. Job Scraping System
![Scraper Demo](demo/scraper.gif)
- Automated data collection
- Multiple source support
- Duplicate detection

### 3. Application Tracking
![Application Demo](demo/application.gif)
- One-click applications
- Status tracking
- Email notifications

## 🔧 Configuration

<details>
<summary>Click to expand configuration files</summary>

### Next.js Config
```typescript
/** @type {import('next').NextConfig} */
const nextConfig = {
  images: {
    domains: ['logo.clearbit.com'],
  },
  env: {
    NEXT_PUBLIC_API_URL: process.env.NEXT_PUBLIC_API_URL,
  },
}

export default nextConfig;
```

### Django Settings
```python
INSTALLED_APPS = [
    # ...
    'rest_framework',
    'corsheaders',
    'jobs',
]

MIDDLEWARE = [
    'corsheaders.middleware.CorsMiddleware',
    # ...
]
```
</details>

## 📝 API Documentation

<details>
<summary>Click to view API endpoints</summary>

### Jobs API
- `GET /api/jobs/` - List all jobs
- `POST /api/jobs/` - Create new job(s)
- `GET /api/jobs/{id}/` - Get job details
- `PUT /api/jobs/{id}/` - Update job
- `DELETE /api/jobs/{id}/` - Delete job

### Search API
- `GET /api/search/` - Search jobs
- Parameters:
  - `q`: Search query
  - `location`: Location filter
  - `type`: Job type filter
  - `salary_min`: Minimum salary
  - `salary_max`: Maximum salary
</details>

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

<details>
<summary>Click to view contribution steps</summary>

1. Fork the repository
2. Create your feature branch:
```bash
git checkout -b feature/AmazingFeature
```
3. Commit your changes:
```bash
git commit -m 'Add some AmazingFeature'
```
4. Push to the branch:
```bash
git push origin feature/AmazingFeature
```
5. Open a Pull Request
</details>

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Support

<div align="center">
  <p>If you like this project, please consider giving it a ⭐!</p>
  
  <a href="https://www.buymeacoffee.com/yourusername">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me A Coffee"/>
  </a>
</div>

## 📧 Contact

<div align="center">
  <a href="mailto:your.email@example.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://linkedin.com/in/yourusername">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://twitter.com/yourusername">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
</div>

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/yourusername">Your Name</a>
</div>
